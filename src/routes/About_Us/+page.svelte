<script lang="ts">
	import hero_aboutus from '$lib/assets/hero_aboutus.svg';
	import { Goal, ListChecks, Clover, Star } from "lucide-svelte";
</script>
<main class="mx-auto max-w-screen-lg p-10 space-y-4">
	<!-- hero section -->
	<section>
		<div class="container mx-auto flex px-5 py-10 md:flex-row flex-col items-center">
			<div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 md:mb-0 mb-10">
				<img class="object-cover object-center rounded" alt="hero" src={hero_aboutus}>
			</div>
			<div class="lg:flex-grow md:w-1/2 lg:pl-24 md:pl-16 flex flex-col md:items-start md:text-left items-center text-center">
				<h1 class="italic text-4xl md:text-4 lg:text-4xl text-center lg:text-left mb-6 ">
					<span class="gradient-heading ">Driving Change The Universe!</span>
				</h1>
				<p class="mb-8 leading-relaxed pb-2">In order to meet the need for professionally
					 qualified PSV professionals in the transportation sector, Project X Driving
					  School was established in 2008.
				</p>
				<p class="mb-8 leading-relaxed"> We have developed over the previous 20+ years
					  into a premier training facility with a focus on truck and bus instruction
					   in addition to offering thorough training for drivers of saloon cars and
						motorcycles.
			   </p>
			</div>
		</div>
	</section>

	<!-- mission vision and values -->
	<section>
		<div class="container px-5 py-8 mx-auto">
			<hr class="!border-t-2 !border-double">

			<!-- part one -->
			<div class="flex items-center lg:w-3/5 mx-auto border-b pb-5 mb-10  sm:flex-row flex-col">
				<div class="sm:w-32 sm:h-32 h-20 w-20 sm:mr-10 inline-flex items-center justify-center rounded-full flex-shrink-0">
					<Goal strokeWidth={1.5} size ={72} />
				</div>
				<div class="flex-grow sm:text-left text-center mt-6 sm:mt-0">
					<h2 class=" text-xl title-font font-medium mb-2">Vision</h2>
					<p class="leading-relaxed text-base">
						Be a leading center of excellence in providing professional driver training programs.
					</p>
					
				</div>
			</div>

			<!-- part two -->
			<div class="flex items-center lg:w-3/5 mx-auto border-b pb-5 mb-10 sm:flex-row flex-col">
				<div class="flex-grow sm:text-left text-center mt-6 sm:mt-0">
					<h2 class=" text-xl title-font font-medium mb-2">Mission</h2>
					<p class="leading-relaxed text-base">
						To professionalize driver training through quality assurance, research, and consultancy.
					</p>
				</div>
				<div class="sm:w-32 sm:h-32 h-20 w-20 sm:mr-10 inline-flex items-center justify-center rounded-full flex-shrink-0">
					<ListChecks strokeWidth={1.5} size ={72}/>
				</div>
			</div>

			<!-- part three -->
			<div class="flex items-center lg:w-3/5 mx-auto border-b pb-5 mb-10  sm:flex-row flex-col">
				<div class="sm:w-32 sm:h-32 h-20 w-20 sm:mr-10 inline-flex items-center justify-center rounded-full flex-shrink-0">
					<Clover strokeWidth={1.5} size ={72} />
					
				</div>
				<div class="flex-grow sm:text-left text-center mt-6 sm:mt-0">
					<h2 class=" text-xl title-font font-medium mb-2">Values</h2>
					<p class="leading-relaxed text-base">
						<strong>Customer Focus: </strong>Exceed customer expectations in line with international best practices.
					</p>
					<br>
					<p class="leading-relaxed text-base">
						<strong> Integrity: </strong>Be open, sincere, and uphold good governance.
					</p>
					<br>
					<p class="leading-relaxed text-base">
						<strong>Teamwork: </strong>Work with and support learners.
					</p>
				</div>
			</div>
			
			<hr class="!border-t-2 !border-double">
		</div>
	</section>

	<!-- Objectives Section -->
	<section>
		<div class="container px-5 py-8 mx-auto flex flex-wrap">
			
			<hr class="!border-t-2 !border-double">

			<div class="flex flex-col text-center w-full mb-1">
				<h2 class="text-xs tracking-widest font-medium title-font mb-1">
					At the end of the learner’s training, they should be able to:
				</h2>
				<h1 class="sm:text-3xl text-2xl font-medium title-font">
					Our Objectives
				</h1>
				<div class="flex flex-col text-center w-full mb-5 py-5">
					
					<p class="lg:w-2/3 mx-auto leading-relaxed text-base py-2">
						<li>Be a competent and safe driver.</li>
					</p>
					<p class="lg:w-2/3 mx-auto leading-relaxed text-base py-2">
						<li>Understand the dynamics and mechanics of the vehicle.</li>
					</p>
					<p class="lg:w-2/3 mx-auto leading-relaxed text-base py-2">
						<li>Be conversant with the Traffic Act, NTSA Act, and Highway Code.</li>
					</p>
				</div>
			</div>
		</div>
	</section>
	
	<!-- Content Section (Teaching style) -->
	<section>
		<div class="container px-5 py-8 mx-auto">

			<hr class="!border-t-2 !border-double">

			<div class="flex flex-col text-center w-full mb-8 py-8">
				<h2 class="text-xs tracking-widest font-medium title-font mb-1">
					Teaching Philosophy: Empowering Safe and Confident Drivers
				</h2>
				<h1 class="sm:text-3xl text-2xl font-medium title-font mb-4">
					Teaching Methodology
				</h1>
				<p class="lg:w-2/3 mx-auto leading-relaxed text-base">the objective is to create
					 responsible, self-assured people who value road safety rather than just licensed
					  drivers by incorporating these techniques into the educational philosophy.
				</p>
			</div>
			<div class="flex flex-wrap">
				<!-- method 1 -->
				<div class=" lg:w-1/2 md:w-full px-8 py-6 border-l-2 border-gray-400">
					<h2 class="text-lg sm:text-xl  font-medium title-font mb-2">
						Individualized Instruction
					</h2>
					<p class="leading-relaxed text-base mb-4">As various people learn to drive in
						 different ways, adjust lessons to meet the needs and learning styles of
						  each student. Give tailored comments to strengthen areas of strength and
						   address areas of weakness.
					</p>
				</div>
				<!-- method 2 -->
				<div class=" lg:w-1/2 md:w-full px-8 py-6 border-l-2 border-gray-400">
					<h2 class="text-lg sm:text-xl  font-medium title-font mb-2">
						Practical Application Emphasis
					</h2>
					<p class="leading-relaxed text-base mb-4">Give practical experience more weight
						 than theoretical understanding. Students gain a deeper grasp of safe
						  driving practices through the application of theoretical principles
						   through real-world settings and simulation exercises.
					</p>
				</div>
				<!-- method 3 -->
				<div class=" lg:w-1/2 md:w-full px-8 py-6 border-l-2 border-gray-400">
					<h2 class="text-lg sm:text-xl  font-medium title-font mb-2">
						Interactive Learning
					</h2>
					<p class="leading-relaxed text-base mb-4">Through conversations, team building
						 exercises, and peer-to-peer learning, promote active engagement.
						  Establishing a stimulating and cooperative learning atmosphere
						   facilitates the exchange of knowledge and perspectives among students,
						    fostering a shared comprehension of safe driving.
					</p>
				</div>
				<!-- method 4 -->
				<div class=" lg:w-1/2 md:w-full px-8 py-6 border-l-2 border-gray-400">
					<h2 class="text-lg sm:text-xl  font-medium title-font mb-2">
						Technology Integration
					</h2>
					<p class="leading-relaxed text-base mb-4">To improve learning, make use of
						 state-of-the-art driving simulations and educational applications.
						  Technology integration guarantees an engaging and dynamic learning
						   environment, giving students the chance to simulate different driving
						    situations in a safe environment.
					</p>
				</div>
				<!-- method 5 -->
				<div class="lg:w-1/2 md:w-full px-8 py-6 border-l-2 border-gray-400">
					<h2 class="text-lg sm:text-xl  font-medium title-font mb-2">
						Real-Life Traffic Situations
					</h2>
					<p class="leading-relaxed text-base mb-4">Introduce pupils to a variety of
						 driving scenarios, such as navigating city traffic, highways, and
						  difficult terrain. Getting hands-on experience in a variety of situations
						   fosters adaptability and self-assurance in varying settings.
					</p>
				</div>
				<!-- method 6 -->
				<div class="lg:w-1/2 md:w-full px-8 py-6 border-l-2 border-gray-400">
					<h2 class="text-lg sm:text-xl  font-medium title-font mb-2">
						Continuous Assessment and Feedback
					</h2>
					<p class="leading-relaxed text-base mb-4">Conduct evaluations on a regular basis
						 to track personal development and pinpoint areas that require attention.
						  Giving students precise feedback to help them improve their abilities
						   and habits throughout the learning process is essential for fostering
						    progress.
					</p>
				</div>
			</div>
		</div>
		<hr class="!border-t-2 !border-double">
	</section>

	<!-- Content Section (safety features) -->
	<section>
		<div class="container px-5 py-8 mx-auto flex flex-wrap">
			
			<div class="text-center mb-4">
				<h1 class="sm:text-3xl text-2xl font-medium text-center title-font mb-4">
					Safety features
				</h1>
				<p class="text-base leading-relaxed xl:w-2/4 lg:w-3/4 mx-auto">
					We will be able to provide additional mirrors inside the car for better
					 visibility, as well as dual pedals (brake and accelerator) for instructor
					  intervention. characteristics that safeguard passengers in the event of an
					   accident. devices for adjusting seatbelts to provide a perfect fit and safety.
					    well stocked with first aid necessities in case of an emergency. An extinguisher for probable
						 car fires should be there for quick action.
				</p>
			</div>
			<!-- features -->
			<div class="flex flex-wrap justify-center lg:w-4/5 sm:mx-auto sm:mb-2 mx-2 pl-20">
				<div class="p-2 sm:w-1/2 w-full">
					<div class=" rounded flex p-4 h-full items-end">
						<Star strokeWidth={1.5} size ={24}/>
						<span class="title-font font-medium px-2">Dual Controls</span>
					</div>
				</div>
				<div class="p-2 sm:w-1/2 w-full">
					<div class=" rounded flex p-4 h-full items-center">
						<Star strokeWidth={1.5} size ={24}/>
						<span class="title-font font-medium px-2">Safety Mirrors</span>
					</div>
				</div>
				<div class="p-2 sm:w-1/2 w-full">
					<div class=" rounded flex p-4 h-full items-center">
						<Star strokeWidth={1.5} size ={24}/>
						<span class="title-font font-medium px-2">Roll Bars and Airbags</span>
					</div>
				</div>
				<div class="p-2 sm:w-1/2 w-full">
					<div class=" rounded flex p-4 h-full items-center">
						<Star strokeWidth={1.5} size ={24}/>
						<span class="title-font font-medium px-2">Adjustable Seat belts</span>
					</div>
				</div>
				<div class="p-2 sm:w-1/2 w-full">
					<div class=" rounded flex p-4 h-full items-center">
						<Star strokeWidth={1.5} size ={24}/>
						<span class="title-font font-medium px-2">First Aid Kit</span>
					</div>
				</div>
				<div class="p-2 sm:w-1/2 w-full">
					<div class=" rounded flex p-4 h-full items-center">
						<Star strokeWidth={1.5} size ={24}/>
						<span class="title-font font-medium px-2">Fire Extinguisher</span>
					</div>
				</div>
			</div>
		</div>
	</section>
</main>
