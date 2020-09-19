<template>
  <div id="app">
    <h1>hello</h1>
    <!-- <Counter 
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

    <Counter 
      buttonTitle="ボタン4"
      :initialCount="1000"
    /> -->

    <Button title="ぼたん1" />

    <Button
    title="ぼたん2"
    @onClick="hello"
    />
    
  </div>
</template>

<script>
import Button from './components/Button'
// import Counter from './components/Counter'

export default {
  name: 'fukufuku',
  components: {
    Button
    // Counter
  },
  methods: {
    hello() {
      console.log('Hello!!!!!!');
    }
  }
}

</script>

<style>

</style>
