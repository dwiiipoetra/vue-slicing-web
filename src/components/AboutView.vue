<template>
  <div class="about">
    <div class="title text-center">
      <h1>Lifecycle & Hook pada vue js</h1>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-xl-12">
          <div id="belajar-hook">{{message}}</div>
          <br>
          <button v-on:click="RenderVirtualDOM()" class="btn btn-secondary">Render Virtual DOM {{rendered}}</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: function(){
    return{
      message: 'Hello Sinau Coding',
      rendered: 0
    }
  },
  mounted(){
    console.log('log dari mounted()')
    console.log('message: ' + this.message);
    this.RenderVirtualDOM()
    console.log(document.getElementById('belajar-hook'));
    console.log(' ')
  },
  created(){
    console.log('log dari created()');
    console.log('message: ' + this.message);
    this.RenderVirtualDOM()
    console.log(document.getElementById('belajar-hook'));
    console.log(' ')
  },
  methods:{
    RenderVirtualDOM(){
      this.rendered += 1;
      console.log('event :' + this.rendered)
    }
  }
}
</script>
