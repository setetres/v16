<template>
  <div class="grid grid-cols-3">
    <dt class="font-medium text-gray-700 px-2">
      {{ name }}
    </dt>
    <dd class="mt-0 flex text-gray-700 px-2 col-span-2">
      <span class="flex-grow">
        <slot />
      </span>
    </dd>
  </div>
</template>
<script>
  export default {
    props: [
      'name'
    ]
  }
</script>
