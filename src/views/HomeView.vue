<template>
  <div class="home">
    <MyComponent/>
  </div>
</template>

<script>
import MyComponent from '@/components/MyComponent.vue';
// @ is an alias to /src

export default {
    name: "HomeView",
    components: { MyComponent }
}
</script>
