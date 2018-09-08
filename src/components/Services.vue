<template>
	<section>
		<div class="service-container">
			<div class="card">
				<div class="card-image waves-effect waves-block waves-light">
					<img class="activator" src="../assets/logo.png">
				</div>
				<div class="card-content">
					<span class="card-title activator grey-text text-darken-4">Exterior Painting</span>
				</div>
				<div class="card-reveal">
					<span class="card-title grey-text text-darken-4">Card Title<i class="material-icons right">X</i></span>
					<p>Here is some more information about this product that is only revealed once clicked on.</p>
				</div>
			</div>
			<div class="card">
				<div class="card-image waves-effect waves-block waves-light">
					<img class="activator" src="../assets/logo.png">
				</div>
				<div class="card-content">
					<span class="card-title activator grey-text text-darken-4">Interior Painting</span>
				</div>
				<div class="card-reveal">
					<span class="card-title grey-text text-darken-4">Card Title<i class="material-icons right">X</i></span>
					<p>Here is some more information about this product that is only revealed once clicked on.</p>
				</div>
			</div>
			<div class="card">
				<div class="card-image waves-effect waves-block waves-light">
					<img class="activator" src="../assets/logo.png">
				</div>
				<div class="card-content">
					<span class="card-title activator grey-text text-darken-4">Kool Decking</span>
				</div>
				<div class="card-reveal">
					<span class="card-title grey-text text-darken-4">Card Title<i class="material-icons right">X</i></span>
					<p>Here is some more information about this product that is only revealed once clicked on.</p>
				</div>
			</div>
			<div class="card">
				<div class="card-image waves-effect waves-block waves-light">
					<img class="activator" src="../assets/logo.png">
				</div>
				<div class="card-content">
					<span class="card-title activator grey-text text-darken-4">New Stucco</span>
				</div>
				<div class="card-reveal">
					<span class="card-title grey-text text-darken-4">Card Title<i class="material-icons right">X</i></span>
					<p>Here is some more information about this product that is only revealed once clicked on.</p>
				</div>
			</div>
			<div class="card">
				<div class="card-image waves-effect waves-block waves-light">
					<img class="activator" src="../assets/logo.png">
				</div>
				<div class="card-content">
					<span class="card-title activator grey-text text-darken-4">New Stucco</span>
				</div>
				<div class="card-reveal">
					<span class="card-title grey-text text-darken-4">Card Title<i class="material-icons right">X</i></span>
					<p>Here is some more information about this product that is only revealed once clicked on.</p>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.service-container {
  display: flex;
  justify-content: center;
  height: 350px;
  background-color: cadetblue;

  .card {
    padding: 0 10px;
    margin: 10px;

    &:hover {
      background-color: orange;
    }
  }
}
</style>