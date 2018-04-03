<template>
  <button>
    <!-- @slot The button label -->
    <slot />
  </button>
</template>

<script>
export default {
  name: 'Button',
}
</script>

<docs>
```vue
<Button>Hello world</Button>
```
</docs>
