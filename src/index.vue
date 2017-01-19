<template>
  <div class="pz-article-body">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'pz-article-body',
  props: ['content']
}
</script>

<style src="./style.css"></style>
