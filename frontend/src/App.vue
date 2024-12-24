

<template>
 <main>
    <Nav />
    <Sign />


 </main>
</template>


<script>
import Nav from './components/Nav.vue';
import Sign from './components/Home/SignUp.vue';

export default {
  components: {
    Nav,
    Sign
  }
}
</script>