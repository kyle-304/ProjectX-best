<script lang="ts">
	import hero_cars from '$lib/assets/hero_cars.svg';
	import pfp1 from '$lib/assets/pfp1.svg'
	import pfp2 from '$lib/assets/pfp2.svg'
</script>

<main class="mx-auto max-w-screen-lg space-y-4">

	<!-- welcome section -->
	<section>
		<div class="container mx-auto flex px-5 py-10 md:flex-row flex-col items-center">
		  <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
			<h1 class="italic text-4xl md:text-4 lg:text-9xl text-center lg:text-left mb-6">
				<span class="gradient-heading ">Project X</span>
			</h1>
			<h2 class="italic text-2xl md:text-4 lg:text-4xl text-center lg:text-left mb-6 font-PoppinsBlack">
				The Ultimate Driving School
			</h2>
			<p class="mb-8 leading-relaxed">
				Since our founding in 2008, we at Project X have been dedicated to offering
				 the best driver education programs. In addition to being a top provider of truck and bus
				  instruction, we also provide top-notch classes for drivers of saloon cars and
				   motorcyclists. 
				</p>
			
		  </div>
		  <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
			<img class="object-cover object-center rounded" alt="hero" src={hero_cars}>
		  </div>
		</div>
	</section>

	<!-- summary of services Section -->
	<section>
		<div class="container px-5 py-8 mx-auto">
			<hr class="!border-t-2 !border-double">
				<div class="grid place-items-center py-4">
					<p class="italic text-base md:text-lg lg:text-3xl ">
					 	<span class="gradient-heading">Services</span>
					</p>
					<p class="mb-8 leading-relaxed font-PoppinsBlack py-4 px-2">
						Our management team, with over thirty years of experience, guarantees
						integrity, forbearance, and an excellent NTSA curriculum taught by fully trained,
						screened driving teachers in contemporary cars.	
					</p>
				</div>
			<hr class="!border-t-2 !border-double">
		</div>
		
	</section>

	<!-- contact Section -->
	<section>
		<div class="container px-5 py-8 mx-auto flex flex-wrap">
			<div class="flex flex-col text-center w-full mb-20">
				<h2 class="text-xs tracking-widest font-medium title-font mb-1">
					WHY CHOOSE US
				</h2>
				<h1 class="sm:text-3xl text-2xl font-medium title-font">
					Partners that have worked with us before
				</h1>
			</div>
			<div class="flex flex-wrap m-4 justify-center">
				<!-- card one -->
				<div class="side-line relative md:w-1/4 m-4">
					<div class="card">
							<header class="card-header flex items-center mb-3">
								<!-- title -->
								<h2 class="title-font">Kenya Forest Research Institute (KFRI)</h2>
							</header>
							<!-- body -->
							<section class="p-4 flex-grow">
								<p class="leading-relaxed">
									A government agency dedicated to conducting research and providing scientific
									 expertise to support sustainable forest management and conservation in Kenya.
								</p>
							</section>
					</div>
				</div>
				<!-- card two -->
				<div class="side-line relative md:w-1/4 m-4">
					<div class="card">
							<header class="card-header flex items-center mb-3">
								<!-- title -->
								<h2 class="title-font">Kenya Defense Forces (KDF) </h2>
							</header>
							<!-- body -->
							<section class="p-4 flex-grow">
								<p class="leading-relaxed">
									The military of the Republic of Kenya, comprising the Army,
									 Air Force, and Navy, tasked with safeguarding national security
									  and contributing to regional peacekeeping efforts.	
								</p>
							</section>
					</div>
				</div>
				<!-- card three -->
				<div class="side-line relative md:w-1/4 m-4">
					<div class="card">
							<header class="card-header flex items-center mb-3">
								<!-- title -->
								<h2 class="title-font">National Government Constituencies Development Fund (NG-CDF) </h2>
							</header>
							<!-- body -->
							<section class="p-4 flex-grow">
								<p class="leading-relaxed">
									A financial allocation mechanism that allocates funds directly to constituencies
									 for local development projects, aiming to empower communities and enhance
									  socio-economic development.	
								</p>
							</section>
					</div>
				</div>
			</div>
		</div>
	</section>
	<!-- Testimonials Section -->
	<section>
		<div class="container px-5 py-24 mx-auto">
			<hr class="!border-t-2 !border-double">
				<div class="grid place-items-center py-4">
					<p class=" italic text-base md:text-lg lg:text-4xl ">
					 	<span class="gradient-heading">Testimonials</span>
					</p>
				</div>
				<!-- the people talking -->
				<div class="flex flex-wrap -m-4 py-8">
					<!-- person one -->
					<div class="p-4 md:w-1/2 w-full">
						<div class="h-full p-8 rounded">
							<svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="block w-5 h-5 text-gray-500 mb-4" viewBox="0 0 975.036 975.036">
								<path d="M925.036 57.197h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.399 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l36 76c11.6 24.399 40.3 35.1 65.1 24.399 66.2-28.6 122.101-64.8 167.7-108.8 55.601-53.7 93.7-114.3 114.3-181.9 20.601-67.6 30.9-159.8 30.9-276.8v-239c0-27.599-22.401-50-50-50zM106.036 913.497c65.4-28.5 121-64.699 166.9-108.6 56.1-53.7 94.4-114.1 115-181.2 20.6-67.1 30.899-159.6 30.899-277.5v-239c0-27.6-22.399-50-50-50h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.4 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l35.9 75.8c11.601 24.399 40.501 35.2 65.301 24.399z"></path>
							</svg>
							<p class="leading-relaxed mb-6">Regarding the D3 (33 plus Seater) course, I'm really pleased with the services provided by Abiria Driving School.
								 The training was extensive, the instructors were excellent, and I'm happy to report that I was able to obtain my license. Bravo to Abiria for creating such a wonderful and
								  fulfilling experience out of the process of becoming a professional driver!
							</p>
							<!-- portrait -->
							<div class="inline-flex items-center">
								<img alt="testimonial" src={pfp1} class="w-12 h-12 rounded-full flex-shrink-0 object-cover object-center"/>
								<span class="flex-grow flex flex-col pl-4">
									<span class="title-font font-medium">Jacob Ombati</span>
									<span class="text-gray-500 text-sm">FORMER STUDENT</span>
								</span>
							</div>
						</div>
					</div>
					<!-- person two -->
					<div class="p-4 md:w-1/2 w-full">
						<div class="h-full bg-opacity-40 p-8 rounded">
							<svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="block w-5 h-5 text-gray-500 mb-4" viewBox="0 0 975.036 975.036">
								<path d="M925.036 57.197h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.399 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l36 76c11.6 24.399 40.3 35.1 65.1 24.399 66.2-28.6 122.101-64.8 167.7-108.8 55.601-53.7 93.7-114.3 114.3-181.9 20.601-67.6 30.9-159.8 30.9-276.8v-239c0-27.599-22.401-50-50-50zM106.036 913.497c65.4-28.5 121-64.699 166.9-108.6 56.1-53.7 94.4-114.1 115-181.2 20.6-67.1 30.899-159.6 30.899-277.5v-239c0-27.6-22.399-50-50-50h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.4 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l35.9 75.8c11.601 24.399 40.501 35.2 65.301 24.399z"></path>
							</svg>
							<p class="leading-relaxed mb-6">I'm excited to talk about my experience with the B Light (Saloon Car)
								 course at Project X. The teachers were excellent; they gave me in-depth
								  instruction that increased my self-assurance when driving. My learning process was made
								   pleasurable by the effective and well-structured classes, which helped me successfully
								    obtain a driver's license. Thank you for the wonderful services at Project X!
							</p>
							<!-- portrait -->
							<div class="inline-flex items-center">
								<img alt="testimonial" src={pfp2} class="w-12 h-12 rounded-full flex-shrink-0 object-cover object-center"/>
								<span class="flex-grow flex flex-col pl-4">
									<span class="title-font font-medium">Ann Maina</span>
									<span class="text-gray-500 text-sm">FORMER STUDENT</span>
								</span>
							</div>
						</div>
					</div>
				</div>
			<hr class="!border-t-2 !border-double">
		</div>
	</section>
	<!-- contacts section -->
	<section class="body-font relative">
		<div class="container px-5 py-24 mx-auto">
		  <div class="flex flex-col text-center w-full mb-12">
			<h1 class="sm:text-3xl text-2xl font-medium title-font mb-4">Contact Us</h1>
			<p class="lg:w-2/3 mx-auto leading-relaxed text-base">We are located at the Heart of Kenya, Nairobi.</p>
		  </div>
		  <div class="lg:w-1/2 md:w-2/3 mx-auto">
			<div class="flex flex-wrap -m-2">
			  <div class="p-2 w-1/2">
				<div class="relative">
				  <label for="name" class="leading-7 text-sm text-gray-600">Name</label>
				  <input type="text" id="name" name="name" class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-white focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
				</div>
			  </div>
			  <div class="p-2 w-1/2">
				<div class="relative">
				  <label for="email" class="leading-7 text-sm text-gray-600">Email</label>
				  <input type="email" id="email" name="email" class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-white focus:ring-2 focus:ring-indigo-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
				</div>
			  </div>
			  <div class="p-2 w-full">
				<div class="relative">
				  <label for="message" class="leading-7 text-sm text-gray-600">Message</label>
				  <textarea id="message" name="message" class="w-full bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:border-indigo-500 focus:bg-white focus:ring-2 focus:ring-indigo-200 h-32 text-base outline-none text-gray-700 py-1 px-3 resize-none leading-6 transition-colors duration-200 ease-in-out"></textarea>
				</div>
			  </div>
			  <div class="p-2 w-full">
				<button class="flex mx-auto text-white bg-indigo-500 border-0 py-2 px-8 focus:outline-none hover:bg-indigo-600 rounded text-lg">Button</button>
			  </div>
			  <div class="p-2 w-full pt-8 mt-8 border-t border-gray-200 text-center">
				<a class="" href="/about">ProjectX@email.com</a>
				<p class="leading-normal my-5">Kilimani.
				  <br>Kirichwa RD.
				</p>
				<span class="inline-flex">
				  <a class="text-gray-500" href="/about">
					<svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
					  <path d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z"></path>
					</svg>
				  </a>
				  <a class="ml-4 text-gray-500" href="/about">
					<svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
					  <path d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z"></path>
					</svg>
				  </a>
				  <a class="ml-4 text-gray-500" href="/about">
					<svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
					  <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
					  <path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01"></path>
					</svg>
				  </a>
				  <a class="ml-4 text-gray-500" href="/about">
					<svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
					  <path d="M21 11.5a8.38 8.38 0 01-.9 3.8 8.5 8.5 0 01-7.6 4.7 8.38 8.38 0 01-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 01-.9-3.8 8.5 8.5 0 014.7-7.6 8.38 8.38 0 013.8-.9h.5a8.48 8.48 0 018 8v.5z"></path>
					</svg>
				  </a>
				</span>
			  </div>
			</div>
		  </div>
		</div>
	  </section>
</main>
