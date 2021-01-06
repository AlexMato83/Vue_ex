<template>
    <div class="text-center">
        <h1>Alessandro Matonti</h1>
        <h3>{{profession}}</h3>
        <button @click="profession ='fruttivendolo'">Cambia</button>
        <hr>
    </div>
</template>

<script>
export default {
    name: 'MioPrimoComponente',
    data: function () {
    return {
      profession: 'Web Developer'
    }
  },
}
</script>