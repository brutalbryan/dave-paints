<template>
	<section>
		<div class="row">
			<form class="col s12" @submit.prevent="submit">
				<div class="row">
					<div class="input-field col s6">
						<input placeholder="Placeholder" id="fname" type="text" class="validate" required>
						<label for="fname">First Name</label>
					</div>
				</div>
				<div class="row">
					<div class="input-field col s6">
						<input id="lname" type="text" class="validate" required>
						<label for="lname">Last Name</label>
					</div>
				</div>
				<div class="row">
					<div class="input-field col s6">
						<input id="email" type="email" class="validate" required>
						<label for="email">Email</label>
					</div>
				</div>
				<input type="submit" value="Get Quote!">
			</form>
  		</div>
	</section>
</template>

<script>
export default {
  methods: {
    submit() {
      console.log(fname.value, lname.value, email.value);
    }
  }
};
</script>

<style lang="scss" scoped>
</style>