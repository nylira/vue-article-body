<template>
  <div class="ni-article-body">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'ni-article-body',
  props: ['content']
}
</script>

<style src="./style.css"></style>
