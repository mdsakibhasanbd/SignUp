

<template>
 <main>
    <Nav />
    <SignUp />


 </main>
</template>


<script>
import Nav from './components/Nav.vue';
import SignUp from './components/Home/SignUp.vue';

export default {
  components: {
    Nav,
    SignUp
  }
}
</script>