<script lang="ts">
import hero_branches from '$lib/assets/hero_branches.svg'
</script>

<main class="mx-auto max-w-screen-lg space-y-4">

	<!-- welcome section -->
	<section>
		<div class="container mx-auto flex px-5 py-10 md:flex-row flex-col items-center">
		  <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
			<h1 class="italic text-4xl md:text-4 lg:text-9xl text-center lg:text-left mb-6">
				<span class="gradient-heading ">ABIRIA</span>
			</h1>
			<h2 class="italic text-2xl md:text-4 lg:text-4xl text-center lg:text-left mb-6 font-PoppinsBlack">
				Driving School
			</h2>
			<p class="mb-8 leading-relaxed">
				Since our founding in 2008, we at ABIRIA Driving School have been dedicated to offering
				 the best driver education programs. In addition to being a top provider of truck and bus
				  instruction, we also provide top-notch classes for drivers of saloon cars and
				   motorcyclists. 
				</p>
			
		  </div>
		  <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
			<img class="object-cover object-center rounded" alt="hero" src={hero_branches}>
		  </div>
		</div>
	</section>
</main>
