<template>
  <view class="container">
<!-- Create -->
    <view>
      <text>Username</text>
      <text-input 
        class="textInput" 
        placeholder="username"
        v-model="tname"
      />
    </view>
    <button :on-press="create" title="Create"/>
    <view>      
      <text>Address</text>
      <text-input 
        class="textInput" 
        placeholder="xxxxx-xxxxx-xxxxx-xxxxx-xxxxx"
        v-model="taddress"
      />
    </view>
    <view>      
      <text>Publickey</text>
      <text-input 
        class="textInput" 
        placeholder="xxxxx-xxxxx-xxxxx-xxxxx-xxxxx"
        v-model="tpublickey"
      />
    </view>
    <view>      
      <text>Privatekey</text>
      <text-input 
        class="textInput" 
        placeholder="xxxxx-xxxxx-xxxxx-xxxxx-xxxxx"
        v-model="tprivatekey"
      />
    </view>
<!-- Account Info -->
    <view>
      <text>Check Account Info By Username</text>
      <Dropdown
        label='Username Account'
        :data="usernames"
        :onChangeText="text => onChangeSender(text)"
      />
      <text>Amount XPX</text>
      <text-input 
        class="textInput" 
        placeholder="0"
        v-model="tamountXPX"
      />
    </view>
  </view>
</template>


<script>
import { Dropdown } from 'react-native-material-dropdown';
import { AsyncStorageDbProvider } from '../../providers/async_db';
import { SirusProvider } from '../../providers/sirus';


export default {
  data () { return objData() },
  methods: {
    create: create,
    remove: remove,
    getAllData: getAllData,
    onChangeSender: onChangeSender
  },
  components: {
    Dropdown 
  }
}

const userNames = [];
const asyncDB   = new AsyncStorageDbProvider();

function objData() {
    setup();
    return data;
}

const data = {
  usernames: userNames,
  tname: "",
  taddress: "",
  tpublickey: "",
  tprivatekey: "",
  tamountXPX: ""
}

function setup() {
  getAllData();
}

function create() {
  // asyncDB.setData("Rathara", "000-1");
  // getAllData();
    //   if (!data.tname) return alert("Please enter user name!");

    // const newAcc = SirusProvider.recoveryAccount("0123456789012345678901234567890123456789012345678901234567890124");
    // console.log("create -> newAcc", newAcc)
    // setData(newAcc, userName);
    // setUserNameInCombobox();
}

async function getAllData() {
  let keys = await asyncDB.getAllKeys();
  keys.map(key => userNames.push({ value: key }));
}

function remove() {
  asyncDB.clearData();
}

function onChangeSender(text) {
  data.name = text;
}



</script>

<style>
.textInput {
  height: 40; 
  width: 250; 
  color: red;
}
</style>