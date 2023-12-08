<script lang="ts">
	import hero_courses from '$lib/assets/hero_courses.svg'

	
	</script>
	
	<main class="mx-auto max-w-screen-lg space-y-4">
		<!-- welcome section -->
		<section>
			<div class="container mx-auto flex px-5 py-10 md:flex-row flex-col items-center">
			  <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
				<h1 class="italic text-4xl md:text-4 lg:text-4xl text-center lg:text-left mb-6 ">
					<span class="gradient-heading ">Courses</span>
				</h1>
				<p class="mb-8 leading-relaxed">Being one of the top driving schools in Kenya,
					 we provide a wide choice of courses that meet the requirements of different
					  driving situations and are all compliant with the National Transport and
					   Safety Authority's (NTSA) standards.
					</p>
				<p class="mb-8 leading-relaxed">Our goal is to provide drivers with
						top-notch instruction that satisfies NTSA requirements while also giving
						them the know-how and abilities needed to drive responsibly and safely
							on Kenyan roads.
					</p>
			
			  </div>
			  <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
				<img class="object-cover object-center rounded" alt="hero" src={hero_courses}>
			  </div>
			</div>
		</section>

		<!-- Promise Section -->
	<section>
		<div class="container px-5 py-8 mx-auto">
			<hr class="!border-t-2 !border-double">
				<div class="grid place-items-center py-4">
					<p class="italic text-base md:text-lg lg:text-3xl ">
					 	<span class="gradient-heading">Summary</span>
					</p>
					<p class="mb-8 leading-relaxed font-PoppinsBlack py-4 px-2">Our courses include
						 A2 Above 50cc (Motorcycle) and A2 Test (Motorcycle) for those seeking
						  motorcycle licenses, B Light (Saloon Car) for novice drivers, and B
						   Professional (PSV) for those interested in passenger service vehicle
						    operation. We also provide B Refresher courses to reinforce existing
							 skills. Our offerings extend to C1 (Light Truck) and C1 Refresher
							  courses, ensuring proficiency in light truck operation. For individuals
							   aspiring to drive passenger vehicles, we offer D1 (14 Seater), D2
							    (14 - 32 Seater), and D3 (33 plus Seater) courses, each tailored
								 to the specific requirements of different vehicle categories.
					</p>

					<p class="text-lg bold py-2">Classes are available on weekdays and Saturdays. Sundays are upon prior arrangement.</p>
				</div>
			<hr class="!border-t-2 !border-double">
		</div>
		
	</section>

		<!-- Categories section -->
	<section>
		<div class="container px-5 py-8 mx-auto grid place-items-center">
			<div class="-my-8 divide-y-2 divide-gray-400">
				<!-- Category 1 -->
				<div class="py-8 flex flex-wrap md:flex-nowrap">
					<div class="md:w-64 md:mb-0 mb-6 flex-shrink-0 flex flex-col">
						<span class="font-semibold title-font">MOTORCYCLE</span>
						<span class="mt-1 text-sm">Minimum age 18 years</span>
					</div>
					<div class="md:flex-grow">
						<h2 class="text-2xl font-medium title-font mb-2">
							A2 - Above 50cc	
						</h2>
						<p class="leading-relaxed">
							• Enables one to ride a motorcycle above 50cc.<br>
							• Can carry a maximum load of 60kg(for up to 400cc).<br>
							• Can carry a passenger.
						</p>
					</div>
				</div>
				<!-- Category 2 -->
				<div class="py-8 flex flex-wrap md:flex-nowrap">
					<div class="md:w-64 md:mb-0 mb-6 flex-shrink-0 flex flex-col">
						<span class="font-semibold title-font">SALOON CAR</span>
						<span class="mt-1 text-sm">Minimum age 18 years</span>
					</div>
					<div class="md:flex-grow">
						<h2 class="text-2xl font-medium title-font mb-2">
							B - Light	
						</h2>
						<p class="leading-relaxed">
							• Enables one to drye a light vehicle passenger car With a 
							maximum Gross Vehicle Weight (GVW) of 3500 kg with one light 
							trailer (not exceeding 750 kg).<br>
							• Can drive a vehicle equipped with both a manual or automatic 
							gearbox.<br>
							• Can carry up to maximum of 7 passengers. 
						</p>
					</div>
				</div>
				<!-- Category 3 -->
				<div class="py-8 flex flex-wrap md:flex-nowrap">
					<div class="md:w-64 md:mb-0 mb-6 flex-shrink-0 flex flex-col">
						<span class="font-semibold title-font">PUBLIC SERVICE VEHICLE(PSV)</span>
						<span class="mt-1 text-sm">Minimum age 18 years</span>
					</div>
					<div class="md:flex-grow">
						<h2 class="text-2xl font-medium title-font mb-2">
							B - Professional	
						</h2>
						<p class="leading-relaxed">
							• Enable one to drive a light vehicle (passenger car) with an automatic
							 gear box and a maximum Gross Vehicle Weight (GVW) of3500 kg with one
							  light trailer (not exceeding 750 kg)<br>
							  • Cannot drive a vehicle equipped with a manual gearbox.<br>
							• Can carry up to maximum of 7 passenger. 
						</p>
					</div>
				</div>
				<!-- Category 4 -->
				<div class="py-8 flex flex-wrap md:flex-nowrap">
					<div class="md:w-64 md:mb-0 mb-6 flex-shrink-0 flex flex-col">
						<span class="font-semibold title-font">REFRESHER</span>
						<span class="mt-1 text-sm">Minimum age 21 years</span>
					</div>
					<div class="md:flex-grow">
						<h2 class="text-2xl font-medium title-font mb-2">
							B Refresher	
						</h2>
						<p class="leading-relaxed">
							• Enable one to drive a light vehicle (passenger car) with a maximum
							Gross Vehicle Weight (GVW) of3500 kg with one light trailer
							 (not exceeding 750 kg)<br>
							• Equipped with a manual or automatic gearbox.<br>
							• Can carry up to maximum of 7 passengers. 
						</p>
					</div>
				</div>
				<!-- Category 5 -->
				<div class="py-8 flex flex-wrap md:flex-nowrap">
					<div class="md:w-64 md:mb-0 mb-6 flex-shrink-0 flex flex-col">
						<span class="font-semibold title-font">LIGHT TRUCK</span>
						<span class="mt-1 text-sm ">Minimum age 22 years</span>
						<span class="mt-1 text-sm ">Two years' experience of<br> driving category C1</span>
						<span class="mt-1 text-sm ">Required to undergo training</span>
					</div>
					<div class="md:flex-grow">
						<h2 class="text-2xl font-medium title-font mb-2">
							C1 - Light Truck	
						</h2>
						<p class="leading-relaxed">
							• Enables one to drive a light truck with a Gross Vehicle
							Weight (GVW) exceeding 3500 kg and a maximum of
							7500 kg with maximum one light trailer not exceeding 750
							kg.<br>
							• Equipped with a manual or automatic gearbox.
						</p>
					</div>
				</div>
				<!-- Category 6 -->
				<div class="py-8 flex flex-wrap md:flex-nowrap">
					<div class="md:w-64 md:mb-0 mb-6 flex-shrink-0 flex flex-col">
						<span class="font-semibold title-font">REFRESHER</span>
						<span class="mt-1 text-sm">Minimum age 22 years</span>
					</div>
					<div class="md:flex-grow">
						<h2 class="text-2xl font-medium title-font mb-2">
							C1 - Refresher	
						</h2>
						<p class="leading-relaxed">
							• Enables one to drive a light truck with a Gross Vehicle
							Weight (GVW) exceeding 3500 kg and a maximum of
							7500 kg with maximum one light trailer not exceeding 750
							kg.<br>
							• Equipped with a manual or automatic gearbox.
						</p>
					</div>
				</div>
				<!-- Category 7 -->
				<div class="py-8 flex flex-wrap md:flex-nowrap">
					<div class="md:w-64 md:mb-0 mb-6 flex-shrink-0 flex flex-col">
						<span class="font-semibold title-font">VAN</span>
						<span class="mt-1 text-sm">Minimum age 22 years</span>
					</div>
					<div class="md:flex-grow">
						<h2 class="text-2xl font-medium title-font mb-2">
							D1 - 14 Seater
						</h2>
						<p class="leading-relaxed">
							• Enables one to drive a van with a maximum of 14 passengers.<br>
							• Equipped with a manual or automatic gearbox.
						</p>
					</div>
				</div>
				<!-- Category 8 -->
				<div class="py-8 flex flex-wrap md:flex-nowrap">
					<div class="md:w-64 md:mb-0 mb-6 flex-shrink-0 flex flex-col">
						<span class="font-semibold title-font">MINIBUS</span>
						<span class="mt-1 text-sm">Minimum age 25 years</span>
					</div>
					<div class="md:flex-grow">
						<h2 class="text-2xl font-medium title-font mb-2">
							D2 - 32 Seater
						</h2>
						<p class="leading-relaxed">
							• Enables one to drive a van with to 14 to 32 passengers.<br>
							• Equipped with a manual or automatic gearbox.
						</p>
					</div>
				</div>
				<!-- Category 9 -->
				<div class="py-8 flex flex-wrap md:flex-nowrap">
					<div class="md:w-64 md:mb-0 mb-6 flex-shrink-0 flex flex-col">
						<span class="font-semibold title-font">LARGE BUS</span>
						<span class="mt-1 text-sm">Minimum age 25 years</span>
						<span class="mt-1 text-sm">Minimum experience of 3 years<br> driving category D1</span>
						<span class="mt-1 text-sm">Required to undergo training<br> and retesting for category D3</span>
					</div>
					<div class="md:flex-grow">
						<h2 class="text-2xl font-medium title-font mb-2">
							D2 - 32 Seater
						</h2>
						<p class="leading-relaxed">
							• Enables one to drive a van with 33 or more passengers.<br>
							• Equipped with a manual or automatic gearbox.
						</p>
					</div>
				</div>
			</div>
		</div>
	</section>
		<!-- NTSA Section -->
		<section>
			<div class="container px-5 py-8 mx-auto">
				<hr class="!border-t-2 !border-double">
					<div class="grid place-items-center py-4">
						<p class="italic text-base md:text-lg lg:text-3xl pb-4">
							 <span class="bold">NTSA Charges</span>
						</p>
						<div class="side-line relative md:w-1/4 m-4">
							<div class="card p-4">
								<p>PDL KSH 700<br>
									Test Booking KSH 1050<br>
									Interim KSH 750<br>
									Smart Card License KSH 3050
								</p>
							</div>
						</div>
					</div>
				<hr class="!border-t-2 !border-double">
			</div>
			
		</section>
	</main>
	
	
<style>
	p {
		font-family: 'Poppins', sans-serif;
	}

	
</style>