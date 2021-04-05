<template>
  <div class="card-body">
    <h1>Vue component</h1>
    <Basic/>
    <A06StyleClass/>
    <A05Event/>
    <A04LifeCycle/>
    <A03Repeater/>
    <A02Binding/>
    
  </div>
</template>

<script>
import A02Binding from './components/02Binding.vue';
import A03Repeater from './components/A03.Repeater.vue';
import A04LifeCycle from './components/A04.LifeCycle';
import A05Event from './components/A05.Event';
import A06StyleClass from './components/A06.StyleClass';
import Basic from './components/Basic';



export default {
  name: 'App',
  components: {
    A02Binding,
    A03Repeater,
    A04LifeCycle,
    A05Event,
    A06StyleClass,
    Basic
  }
}
</script>

<style>
</style>
