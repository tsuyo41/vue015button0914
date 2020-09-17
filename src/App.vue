<template>
  <div id="app">
    <h1>hello</h1>
    <Counter 
      buttonTitle="ボタン1"
    />
    <Counter 
      button-title="ボタン2"
      :initial-count="10"
    />
    <Counter 
      buttonTitle="ボタン3"
      :initialCount="100"
    />
    
  </div>
</template>

<script>
// import Button from './components/Button'
import Counter from './components/Counter'

export default {
  name: 'fukufuku',
  components: {
    // Button,
    Counter
  }
}

</script>

<style>

</style>
