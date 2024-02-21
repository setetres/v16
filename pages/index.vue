<template>
  <CardDetail class="col-span-2">
    <Detail name="Mode">
      HIATUS
    </Detail>
    <Detail name="Mood">
      😫
    </Detail>
    <Detail name="Name">
      Guilherme
    </Detail>
    <Detail name="Surname">
      Pangnotta
    </Detail>
    <Detail name="Since">
      <Tag color="bg-emerald-500">
        2008
      </Tag>
    </Detail>
    <Detail name="Nationality">
      Brasil
    </Detail>
    <Detail name="Food">
      🍔
    </Detail>
    <Detail name="Family">
      👩🐶🐶🐶🐱🐱
    </Detail>
  </CardDetail>
</template>
<script>
  export default {
    mounted() {
      this.$nextTick(() => {
      })
    },
    beforeRouteLeave(to, from, next) {
      setTimeout(function() {
        next()
      }, 173)
    }
  }
</script>
