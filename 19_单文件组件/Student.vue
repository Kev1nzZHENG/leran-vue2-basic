<template>
  <div class="demo2">
    <h2>学生名字：{{ name }}</h2>
    <h2>年龄：{{ address }}</h2>
  </div>
</template>

<script>
export default {
  name: "Student",
  data() {
    return {
      name: "牛马",
      age: 18,
    };
  },
};
</script>
