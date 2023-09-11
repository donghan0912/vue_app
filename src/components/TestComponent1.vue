<template>
  <div>
    <p>测试标题1</p>
    <p>{{ name }}</p>
    <p>{{ gender }}</p>
    <p>{{ age }}</p>
  </div>

</template>

<script>
export default {
  name: "TestComponent1",
  props: {
    name: String,
    gender: String,
    age: Number,
  }
}
</script>

