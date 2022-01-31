<script>
	let itemsVisiable = true;
</script>

<div class="w-auto">

		<!--Nav Bar Div -->

		<div class="bg-gray-200">
			<!--Nav Bar start-->
			<nav class="bg-blue-300">
				<!--Container-->
				<div class="container px-4 mx-auto py-2 flex lg:flex-row flex-col">
					<div class="flex">
						<a
							href="#"
							class="inline-flex p-2 text-xl font-bold flex flex-wrap  uppercase tracking-wider text-white active"
							>AM GROUP</a
						>
						<!--Toogle-->
						<div class="ml-auto justify-end">
							<button
								class="inline-flex items-center justify-center border h-10 w-10 text-white rounded-md outline-none focus:outline-none lg:hidden"
								on:click={()=>itemsVisiable=!itemsVisiable}
							>
								<svg
									xmlns="http://www.w3.org/2000/svg"
									class="h-6 w-6"
									fill="none"
									viewBox="0 0 24 24"
									stroke="currentColor"
								>
									<path
										stroke-linecap="round"
										stroke-linejoin="round"
										stroke-width="2"
										d="M4 6h16M4 12h16M4 18h16"
									/>
								</svg>
							</button>
						</div>
					</div>

					<!--Toogle End-->
					<!--menu start-->
					<div class="w-full lg:inline-flex  flex justify-center  lg:w-auto  mt-4  lg:mt-0 {!itemsVisiable ? 'hidden' : ''}">
						<ul class="flex lg:flex-row flex-col space-y-2  lg:space-y-0 lg:space-x-10">
							<li>        
								<button
									href="#"
									class="flex px-4 py-2 rounded-md font-medium text-white hover:bg-blue-400 
                  transition ease-in-out delay-150 hover:-translate-y-0 hover:scale-110  duration-500"
									>Home</button
								>
							</li>
							<li>        
								<button
									href="#"
									class="flex px-4 py-2 rounded-md font-medium text-white hover:bg-blue-400 
                  transition ease-in-out delay-150 hover:-translate-y-0 hover:scale-110  duration-500"
									>About us</button
								>
							</li>
							<li>
								<button
									href="#"
									class="flex px-4 py-2 rounded-md font-medium text-white hover:bg-blue-400
                  transition ease-in-out delay-150 hover:-translate-y-0 hover:scale-110  duration-500"
									>Services</button
								>
							</li>
							<li>
								<button
									href="#"
									class="flex px-4 py-2 rounded-md font-medium text-white hover:bg-blue-400
                  transition ease-in-out delay-150 hover:-translate-y-0 hover:scale-110  duration-500"
								>
									Products</button
								>
							</li>
							<li>
								<button
									href="#"
									class="flex px-4 py-2 rounded-md font-medium text-white hover:bg-blue-400
                  transition ease-in-out delay-150 hover:-translate-y-0 hover:scale-110  duration-500"
									>Contact us</button
								>
							</li>
						</ul>
					</div>
				</div>
			</nav>
		</div>

		<!-- End Nav Bar Div -->

		<!--2ND PORTION/IMAGE DIV START-->

        <div class="grid grid-cols-2 hover:grid-2 bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-400 w-full">
                <div>
                    <h1 class="mt-60 ml-10 text-6xl italic text-white transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110  duration-500">Give Your Workout</h1>
				<h1 class=" text-6xl ml-10 italic text-white transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110  duration-500">A new Style!</h1>
				<h1 class=" text-lg ml-10 italic mt-4 text-white transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110  duration-500">
					Success isn't always about greatness.It's about consistency.
				</h1>
				<h1 class=" text-lg italic ml-10 mt-2 text-white transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110  duration-500">
					Consistent hard work gains success. Greatness will come.
				</h1>
				<button class="btn btn-error w-40 mt-5 rounded-2xl ml-10
                bg-gradient-to-r from-green-400 to-blue-500 hover:from-pink-500 hover:to-yellow-500
                ">Explore Now --></button>
                <div class="mt-10">

                </div>

                    
        </div>
                <div class=" mt-60 w-74 h-74  ml-10 ">

                    <img src="newpic.png" alt="abc" class="object-cover" />

                </div>
                
            </div>

        <!-- End 2ND PORTION/IMAGE DIV START-->
        <!--  About us DIV START-->

        <div class="grid grid-cols-1 mt-8 my-10">

          <h1 class="text-5xl text-center font-bold font-serif mb-24  mt-16">About Us</h1>
        </div>
        
        <div class="grid grid-cols-2 mx-8">          
          <div class="">
            <h1 class="text-5xl font-bold font-serif md:ml-10 sm:ml-5">WE ARE CREATIVE</h1>

            <h1 class="font-serif mt-6 ">Web development is the work involved in developing a website for the 
              Internet or an intranet. Web development 
              can range from developing a simple single static 
              page of plain text to complex web applications, electronic businesses,
               and social network services.</h1>          

          </div>
          <div class="ml-10"> 

            <img src="newpic.png" alt="abc" class="object-cover" />
          </div>


        </div>



        <!-- End About us DIV START-->



           <!-- Service PORTION DIV START-->

        <div class="grid grid-cols-1 mt-14">

            <h1 class="text-5xl text-center font-bold font-serif mt-20 mb-24">SERVICES</h1>
        </div>

        <div class="grid sm:grid-cols-1 md:grid-cols-2 lg:grid-cols-3 mt-0">

            <!-- 1st Service PORTION -->
            <div class="card card-bordered ml-6 mr-6">
                <figure>
                  <img src="web_developmentimage.png">
                </figure> 
                <div class="card-body">
                  <h2 class="card-title font-bold text-center font-serif">WEB DEVELOPMENT
                  </h2> 
                  <p class="text-center font-serif">We Provide Web services for our client</p> 
                  <div class="justify-center card-actions">
                    <button class="btn btn-error w-40 rounded-2xl 
                bg-gradient-to-r from-green-400 to-blue-500 hover:from-pink-500 hover:to-yellow-500
                ">MORE INFO --></button>
                  </div>
                </div>
            </div> 
           <!-- 2nd Service PORTION -->
            <div class="card card-bordered ml-6 mr-6">
                <figure>
                  <img src="app_dev.png">
                </figure> 
                <div class="card-body">
                  <h2 class="card-title mt-10 text-center font-bold font-serif">App DEVELOPMENT
                  </h2> 
                  <p class="text-center font-serif">We Provide Web services for our client</p> 
                  <div class="justify-center card-actions">
                    <button class="btn btn-error w-40 rounded-2xl 
                bg-gradient-to-r from-green-400 to-blue-500 hover:from-pink-500 hover:to-yellow-500
                ">MORE INFO --></button>
                  </div>
                </div>
            </div> 
            <!-- 3rd Service PORTION -->
            <div class="card card-bordered ml-6 mr-6">
                <figure>
                  <img src="iosapp_dev.png">
                </figure> 
                <div class="card-body">
                  <h2 class="card-title text-center font-bold font-serif">IOS APP DEVELOPMENT
                  </h2> 
                  <p class="text-center font-serif">We Provide Web services for our client</p> 
                  <div class="justify-center card-actions">
                    <button class="btn btn-error w-40 rounded-2xl 
                bg-gradient-to-r from-green-400 to-blue-500 hover:from-pink-500 hover:to-yellow-500
                ">MORE INFO --></button>
                  </div>
                </div>
            </div> 
        </div>

        <!-- End Service PORTION DIV START-->

         <!-- product PORTION DIV START-->

         <div class="grid grid-cols-1 mt-8">

            <h1 class="text-5xl text-center font-bold font-serif mb-10 mt-10">Products</h1>
        </div>

        <div class="grid sm:grid-cols-1 md:grid-cols-2 lg:grid-cols-3 mt-10">

            <!-- 1st Product PORTION -->
            <div class="card card-bordered ml-6 mr-6">
                <figure>
                  <img src="seo.png">
                </figure> 
                <div class="card-body">
                  <h2 class="card-title text-center font-bold">SEO
                  </h2> 
                  <p class="text-center ">We Provide Web services for our client</p> 
                  <div class="justify-center card-actions">
                    <button class="btn btn-error w-40 rounded-2xl 
                bg-gradient-to-r from-green-400 to-blue-500 hover:from-pink-500 hover:to-yellow-500
                ">MORE INFO --></button>
                  </div>
                </div>
            </div> 
           <!-- 2nd Product PORTION -->
            <div class="card card-bordered ml-6 mr-6">
                <figure>
                  <img src="social_media.png ">
                </figure> 
                <div class="card-body">
                  <h2 class="card-title text-center font-bold">Social Media Marketing
                  </h2> 
                  <p class="text-center">We Provide Web services for our client</p> 
                  <div class="justify-center card-actions">
                    <button class="btn btn-error w-40 rounded-2xl 
                bg-gradient-to-r from-green-400 to-blue-500 hover:from-pink-500 hover:to-yellow-500
                ">MORE INFO --></button>
                  </div>
                </div>
            </div> 
            <!-- 3rd Product PORTION -->
            <div class="card card-bordered ml-6 mr-6">
                <figure>
                  <img src="web.png">
                </figure> 
                <div class="card-body">
                  <h2 class="card-title text-center font-bold">Web Development
                  </h2> 
                  <p class="text-center">We Provide Web services for our client</p> 
                  <div class="justify-center card-actions">
                    <button class="btn btn-error w-40 rounded-2xl 
                bg-gradient-to-r from-green-400 to-blue-500 hover:from-pink-500 hover:to-yellow-500
                ">MORE INFO --></button>
                  </div>
                </div>
            </div> 
        </div>
          <!-- End product PORTION DIV START-->
           <!--Contact PORTION DIV START-->

            <div class="grid grid-cols-1 mt-8 my-10">

               <h1 class="text-5xl text-center font-bold font-serif transition ease-in-out delay-150 hover:-translate-y-1 hover:scale-110  duration-500 mb-10">Contact us</h1>
            </div>

            <div class=" md:w-full  border border-slate-400 rounded-xl ">

            <div class="p-6 border border-gray-500 sm:rounded-md">
              <form method="POST" action="">
                <label class="block mb-6">
                  <span class="text-gray-700 font-bold font-serif">Your name</span>
                  <input
                    type="text"
                    name="name"
                    class="
                    border border-current
                    block
                      w-full
                      mt-2
                      border-gray-300
                      rounded-md
                      shadow-sm
                      focus:border-indigo-300
                      focus:ring
                      focus:ring-indigo-200
                      focus:ring-opacity-50
                    "
                    placeholder="Name"
                  />
                </label>
                
                <label class="block mb-6">
                  <span class="text-gray-700 font-bold font-serif">Email address</span>
                  <input
                    name="email"
                    type="email"
                    class="
                    border border-current
                      block
                      w-full
                      mt-2
                      border-gray-300
                      rounded-md
                      shadow-sm
                      focus:border-indigo-300
                      focus:ring
                      focus:ring-indigo-200
                      focus:ring-opacity-50
                    "
                    placeholder="username@gmail.com"
                    required
                  />
                </label>
                <label class="block mb-6">
                  <span class="text-gray-700 font-bold font-serif">Message</span>
                  <textarea
                    name="message"
                    class="
                    border border-current
                      block
                      w-full
                      mt-1
                      border-gray-300
                      rounded-md
                      shadow-sm
                      focus:border-indigo-300
                      focus:ring
                      focus:ring-indigo-200
                      focus:ring-opacity-50
                    "
                    rows="3"
                    placeholder="Tell us what you're thinking about..."
                  ></textarea>
                </label>
                <div class="mb-6 text-center">
                  <button
                    type="submit"
                    class="
                      h-10
                      px-5
                      btn btn-primary
                      font-bold
                      font-serif
                      text-indigo-100
                      bg-indigo-700
                      rounded-lg
                      transition-colors
                      duration-150
                      focus:shadow-outline
                      hover:bg-indigo-800
                    "
                  >
                    Contact Us
                  </button>
                </div>
              </form>
            </div>
            
            </div>
           <!--End Contact PORTION DIV START-->

           <!--Footer PORTION DIV START-->

           <footer class="p-10 footer bg-gray-200 mt-10  text-base-content">

            <div>
              <span class="footer-title">Services</span> 
              <a class="link link-hover">Web Development</a> 
              <a class="link link-hover">App Develolpment</a> 
              <a class="link link-hover">ISO App development</a> 
              <a class="link link-hover">Social Media Marketing</a>
            </div> 
            <div>
              <span class="footer-title">Company</span> 
              <a class="link link-hover">Services</a> 
              <a class="link link-hover">Contact us</a> 
              <a class="link link-hover">Products</a> 
            </div> 
            <div>
              <span class="footer-title">Legal</span> 
              <a class="link link-hover">Terms of use</a> 
              <a class="link link-hover">Privacy policy</a> 
              <a class="link link-hover">Cookie policy</a>
            </div> 
            <div>
              <span class="footer-title">Newsletter</span> 
              <div class="form-control w-80">
                <label class="label">
                  <span class="label-text">Enter your email address</span>
                </label> 
                <div class="relative">
                  <input type="text" placeholder="username@gmail.com" class="w-full pr-16 input input-bordered"> 
                  <button class="absolute top-0 right-0 rounded-l-none btn btn-primary">Subscribe</button>
                </div>
              </div>
            </div>
          </footer>
           
           <!-- End Footer PORTION DIV START-->


        


</div>
