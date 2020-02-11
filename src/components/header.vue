<template>
  <div class="pa2 flex flex-column white tl">
    <div class="fw2 f4 f5-m subtitle">Remeber and share your wishes with</div>
    <div class="fw6 f1 f2-m title">Wishywashy</div>
  </div>
</template>
<script>
export default {
  name: "ww-header"
}
</script>

<style>
.title {
  text-shadow:
    3px 3px 0 #000,
    -1px -1px 0 #000,  
    1px -1px 0 #000,
    -1px 1px 0 #000,
    1px 1px 0 #000;
}
.subtitle {
   text-shadow:
      -1px -1px 0 #000,  
      1px -1px 0 #000,
      -1px 1px 0 #000,
      1px 1px 0 #000;
}
</style>