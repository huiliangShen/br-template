<template>
    <div>
        <input />
    </div>
    <div>
        <button>{{obj.btnText}}</button>
    </div>
   
  </template>
  
  <script>
  export default {
    name: 'form',
    props: {
      obj: {
        type: Object,
        default: () => {},
      },
    },
  }
  </script>
  
  <style></style>
  