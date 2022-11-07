<template>
  <div class="home">
    <div class="propertiMethod p-3" style="border: 1px solid grey">
      <h1>Properti Method</h1>
      <label for="value1">
        <input type="number" v-model="value1">
      </label>
      <span>+</span>
      <label for="value2">
        <input type="number" v-model="value2">
      </label>
      <span> = </span>
      <span> {{total}} </span>
      <div class="my-2">
        <button @click="addValue" class="btn btn-primary">Total</button>
      </div>
      <hr>
      <input type="text" v-model="textInput">
      <button @click="changeText" class="btn btn-secondary mx-2">Change</button>
      <p>{{textChange}}</p>
    </div>
    <div class="propertiComputed p-3" style="border: 1px solid grey">
      <h1>Properti Computed</h1>
      <label for="firstname">
        Fisrtname
        <input type="text" v-model="firstName">
      </label>
      <label class="mx-2" for="lastname">
        LastName
        <input type="text" v-model="lastName">
      </label>
      <p class="my-2">Fullname : {{fullName}}</p>
      <hr>
      <label for="number1">
        <input type="number" v-model="number1">
      </label>
      <span>+</span>
      <label for="number2">
        <input type="number" v-model="number2">
      </label>
      <span> = </span>
      <span> {{totalComputed}} </span>
    </div>
    <div class="propertiWatch p-3" style="border: 1px solid grey">
      <h1>Properti Watch</h1>
      <label for="textInput">
        text 
        <input type="text" v-model="textInputan"> {{ keterangan }}
      </label>
      <hr>
      <label for="firstname">
        Fisrtname
        <input type="text" v-model="firstNamewatch">
      </label>
      <label class="mx-2" for="lastname">
        LastName
        <input type="text" v-model="lastNamewatch">
      </label>
      <p class="my-2">Fullname : {{fullNamewatch}}</p>
    </div>
  </div>
</template>

<script>
  // @ is an alias to /src

  export default {
    name: 'HomeView',
    data: function(){
      return {
        value1: 0,
        value2: 0,
        total: 0,
        textInput: '',
        textChange: '',
        firstName: '',
        lastName: '',
        fullName: '',
        firstNamewatch: '',
        lastNamewatch: '',
        fullNamewatch: '',
        number1: 0,
        number2: 0,
        totalComputed: 0,
        textInputan: '',
        keterangan: ''
      }
    },
    watch:{
      firstNamewatch: function(){
        return this.fullNamewatch = this.firstNamewatch + ' ' + this.lastNamewatch
      },
      lastNamewatch: function(){
        return this.fullNamewatch = this.firstNamewatch + ' ' + this.lastNamewatch
      },
    },
    computed:{
      fullName: function(){
        return this.firstName + ' ' + this.lastName
      },
      totalComputed: function(){
        return this.number1 + this.number2
      }
    },
    methods:{
      addValue(){
        return this.total = this.value1 + this.value2
      },
      changeText(){
        return this.textChange = this.textInput + '.vue'
      }
    }
  }
</script>