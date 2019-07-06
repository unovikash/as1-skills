<template>
	<div class="about">
		<h1>About</h1>
		<p>Hello {{their_name}}</p>
		<p>The skills application was developed to learn more about the Vue framework. I could have added some random things as well, but you know what, at this point of time, I am just a tired soul, trying to get done with it. So, yes, hurray, I am almost done.</p>
	</div>
</template>

<script>
export default {
  name: 'Skills',
  data(){
    return {
      their_name: this.$route.params.name
    }
  }
}
</script>