<template>
  <div class="ny-article-body">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'ny-article-body',
  props: ['content']
}
</script>

<style src="./style.css"></style>
