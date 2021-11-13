<template>
	<div class="container-fluid">
		<div class="row">
			<div class="col-lg-8 col-xl-9 order-1 order-lg-0 pt-10 pt-xl-7 pt-xxl-8 pb-0">
				<div class="row min-vh-25 flex-center">
					<div class="col-lg-10">

						<div class="text-center mb-5 mb-lg-6">
							<h2><span class="fw-medium">Photos </span>we took</h2>
						</div>

						<section class="py-3" id="swiper">
							<div class="container-fluid">
								<div class="row justify-content-center">
									<div class="col-lg-10 col-xl-8">
											<!-- SLIDER - 1 -->
										<div class="swiper-container theme-slider gallerySwiper">
											<div class="swiper-wrapper h-100">

												<div v-for="(obj , index) in sldr1" :key="index" v-show="index == slctIndx" class="swiper-slide h-100">
													<div class="card h-100"><img class="img-fluid" :src="obj.src" alt="" />
														<div class="card-body h-100 px-2">
															<h5 class="my-3 text-center">{{ obj.title }}</h5>
															<p class="mb-0">On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain and trouble that are bound to ensue; and equal blame belongs to those who fail in their duty through weakness of will, which is the same as saying through shrinking from toil and pain.</p>
														</div>
													</div>
												</div>
												
											</div>
											<div class="text-center">
												<div class="swiper-pagination">
													<span v-for="(num , index) in sldr1.length" :key="index" :class="index == slctIndx ? 'active' : ''" @click="slctIndx = index"></span>
												</div>
											</div>
										</div>

										<div class="row justify-content-between">
											<div class="col-sm-6 my-sm-6 border-lg-end pe-sm-5"><img class="img-fluid" src="/assets/img/gallery/gallery-2.png" alt="" />
												<h5 class="mb-2 mt-4">Product Photography</h5>
												<p class="mb-5">On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain and trouble that are bound to ensue; and equal blame belongs to those who fail in their duty through weakness of will, which is the same as saying through shrinking from toil and pain.</p><img class="img-fluid" src="/assets/img/gallery/gallery-4.png" alt="" />
												<h5 class="mb-2 mt-4">Software Controlled</h5>
												<p class="mb-5">On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain and trouble that are bound to ensue; and equal blame belongs to those who fail in their duty through weakness of will, which is the same as saying through shrinking from toil and pain.</p><img class="img-fluid" src="/assets/img/gallery/gallery-18.png" alt="" />
												<h5 class="mb-2 mt-4">Product Photography</h5>
												<p class="mb-5">On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain and trouble that are bound to ensue; and equal blame belongs to those who fail in their duty through weakness of will, which is the same as saying through shrinking from toil and pain.</p>
											</div>
											<div class="col-sm-6 my-sm-6 border-lg-start ps-sm-5"><img class="img-fluid" src="/assets/img/gallery/gallery-3.png" alt="" />
												<h5 class="mb-2 mt-4">Features</h5>
												<p class="mb-5">On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain and trouble that are bound to ensue; and equal blame belongs to those who fail in their duty through weakness of will, which is the same as saying through shrinking from toil and pain.</p><img class="img-fluid" src="/assets/img/gallery/gallery-5.png" alt="" />
												<h5 class="mb-2 mt-4">Search</h5>
												<p class="mb-5">On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain and trouble that are bound to ensue; and equal blame belongs to those who fail in their duty through weakness of will, which is the same as saying through shrinking from toil and pain.</p><img class="img-fluid" src="/assets/img/gallery/gallery-19.png" alt="" />
												<h5 class="mb-2 mt-4">Grepper Teams</h5>
												<p class="mb-5">On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain and trouble that are bound to ensue; and equal blame belongs to those who fail in their duty through weakness of will, which is the same as saying through shrinking from toil and pain.</p>
											</div>
										</div>
									</div>
								</div>
							</div><!-- end of .container-->
						</section>

						<section class="py-3">
							<div class="container-fluid">
								<div class="row justify-content-center">
									<div class="col-lg-10 col-xl-8">
											<!-- SLIDER - 2 -->
										<div class="swiper-container theme-slider gallerySwiper">
											<div class="swiper-wrapper">

												<div v-for="(obj , index) in sldr2" :key="index" v-show="index == slctIndx" class="swiper-slide h-100">
													<div class="card h-100"><img class="img-fluid" :src="obj.src" alt="" />
														<div class="card-body h-100 px-2">
															<h5 class="my-3 text-center">{{ obj.title }}</h5>
															<p class="mb-0">On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain and trouble that are bound to ensue; and equal blame belongs to those who fail in their duty through weakness of will, which is the same as saying through shrinking from toil and pain.</p>
														</div>
													</div>
												</div>

											</div>
											<div class="text-center">
												<div class="swiper-pagination">
													<span v-for="(num , index) in sldr1.length" :key="index" :class="index == slctIndx ? 'active' : ''" @click="slctIndx = index"></span>
												</div>
											</div>
										</div>

										<div class="row justify-content-between">
											<div class="col-sm-6 my-sm-6 border-lg-end pe-sm-5"><img class="img-fluid" src="/assets/img/gallery/gallery-9.png" alt="" />
												<h5 class="mb-2 mt-4">Finibus Bonorum</h5>
												<p class="mb-5">On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain and trouble that are bound to ensue; and equal blame belongs to those who fail in their duty through weakness of will, which is the same as saying through shrinking from toil and pain.</p><img class="img-fluid" src="/assets/img/gallery/gallery-11.png" alt="" />
												<h5 class="mb-2 mt-4">Finibus Bonorum</h5>
												<p class="mb-5">On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain and trouble that are bound to ensue; and equal blame belongs to those who fail in their duty through weakness of will, which is the same as saying through shrinking from toil and pain.</p>
											</div>
											<div class="col-sm-6 my-sm-6 border-lg-start ps-sm-5"><img class="img-fluid" src="/assets/img/gallery/gallery-10.png" alt="" />
												<h5 class="mb-2 mt-4">Finibus Bonorum</h5>
												<p class="mb-5">On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain and trouble that are bound to ensue; and equal blame belongs to those who fail in their duty through weakness of will, which is the same as saying through shrinking from toil and pain.</p><img class="img-fluid" src="/assets/img/gallery/gallery-8.png" alt="" />
												<h5 class="mb-2 mt-4">Finibus Bonorum</h5>
												<p class="mb-5">But I must explain to you how all this mistaken idea of reprobating pleasure and extolling pain arose. To do so, I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness. </p>
											</div>
										</div>
									</div>
								</div>
							</div><!-- end of .container-->
						</section>

						<section class="py-3">
							<div class="container-fluid">
								<div class="row justify-content-center">
									<div class="col-lg-10 col-xl-8">
											<!-- SLIDER - 3 -->
										<div class="swiper-container theme-slider gallerySwiper">
											<div class="swiper-wrapper">

												<div v-for="(obj , index) in sldr3" :key="index" v-show="index == slctIndx" class="swiper-slide h-100">
													<div class="card h-100"><img class="img-fluid" :src="obj.src" alt="" />
														<div class="card-body h-100 px-2">
															<h5 class="my-3 text-center">{{ obj.title }}</h5>
															<p class="mb-0">On the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain and trouble that are bound to ensue; and equal blame belongs to those who fail in their duty through weakness of will, which is the same as saying through shrinking from toil and pain.</p>
														</div>
													</div>
												</div>

											</div>
											<div class="text-center">
												<div class="swiper-pagination">
													<span v-for="(num , index) in sldr1.length" :key="index" :class="index == slctIndx ? 'active' : ''" @click="slctIndx = index"></span>
												</div>
											</div>
										</div>

										<div class="row pt-5">
											<div class="col-sm-6 my-sm-6 border-lg-end pe-sm-5"><img class="img-fluid" src="/assets/img/gallery/gallery-21.png" alt="" />
												<h5 class="mb-2 mt-4">Asemic writing</h5>
												<p class="mb-5">But I must explain to you how all this mistaken idea of reprobating pleasure and extolling pain arose. To do so, I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness. </p><img class="img-fluid" src="/assets/img/gallery/gallery-16.png" alt="" />
												<h5 class="mb-2 mt-4">Asemic writing</h5>
												<p class="mb-5">But I must explain to you how all this mistaken idea of reprobating pleasure and extolling pain arose. To do so, I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness. </p><img class="img-fluid" src="/assets/img/gallery/gallery-21.png" alt="" />
												<h5 class="mb-2 mt-4">Asemic writing</h5>
												<p class="mb-5">But I must explain to you how all this mistaken idea of reprobating pleasure and extolling pain arose. To do so, I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness. </p>
											</div>
											<div class="col-sm-6 my-sm-6 border-lg-start ps-sm-5"><img class="img-fluid" src="/assets/img/gallery/gallery-15.png" alt="" />
												<h5 class="mb-2 mt-4">Asemic writing</h5>
												<p class="mb-5">But I must explain to you how all this mistaken idea of reprobating pleasure and extolling pain arose. To do so, I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness. </p><img class="img-fluid" src="/assets/img/gallery/gallery-17.png" alt="" />
												<h5 class="mb-2 mt-4">Asemic writing</h5>
												<p class="mb-5">But I must explain to you how all this mistaken idea of reprobating pleasure and extolling pain arose. To do so, I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness. </p><img class="img-fluid" src="/assets/img/gallery/gallery-13.png" alt="" />
												<h5 class="mb-2 mt-4">Asemic writing</h5>
												<p class="mb-5">But I must explain to you how all this mistaken idea of reprobating pleasure and extolling pain arose. To do so, I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness. </p>
											</div>
										</div>
									</div>
								</div>
							</div><!-- end of .container-->
						</section>

					</div>

					<div class="col-12">
						<div class="row justify-content-center pt-3d">
							<div class="col-lg-8 col-xl-7 mb-n5 mb-md-n8 mb-lg-n6 mb-xl-n9 mt-8">
								<div class="card bg-backdrop">
									<div class="card-body p-2 px-lg-2 px-xl-5">
										<div class="py-5 text-center">
											<h2 class="fs-1 fs-xxl-2 fw-bolder">Start your next project with us</h2>
											<p class="mb-4 text-900">Join the talented group of artists and imaginators</p><a class="btn hover-top btn-boots-warning" href="#!">Join Boots5 </a>
										</div>
									</div>
								</div>
							</div>
							<div class="col-lg-10"><img class="w-100" src="/assets/img/cta/cta-gallery.png" alt="..." style="border-radius:1rem;" /></div>
						</div>
						<div class="row justify-content-center my-3">
							<div class="col-12 col-lg-10">
								<div class="card bg-soft-cyan-2">
									<div class="card-body py-3">
										<div class="row">
											<div class="col-lg-6 text-center text-lg-start">
												<p class="fs--1 my-2 fw-bold text-gradient-cyan-soft-2">All rights Reserved &copy; Your Company, 2021</p>
											</div>
											<div class="col-lg-6 d-lg-flex align-self-center justify-content-end text-center">
												<p class="fs--1 mb-0 text-gradient-cyan-soft-2">Made with <span class="fas fa-heart mx-1 text-success"></span>by<a href="https://themewagon.com/"> Themewagon</a></p>
											</div>
										</div>
									</div>
								</div>
							</div>
						</div>
					</div>

				</div>
			</div>
			<div class="col-lg-4 col-xl-3 position-absolute position-lg-relative ps-lg-0">
				<div class="sticky-top py-4 sticky-area" data-sidebar-close="sidebar-close">
					<div @click="$emit('goIndex')" class="btn-close-boots-container times">
						<div class="btn-close-boots"></div>
					</div>
					<div class="bg-holder sidebar-rounded" style="background-image:url(/assets/img/sidebars/gallery.png);"></div>
					<!--/.bg-holder-->
					<div class="position-relative d-lg-flex flex-column justify-content-end align-items-end h-100 px-lg-4 px-xxl-5">
						<h1 class="text-white text-vertical px-5 px-lg-0 opacity-50 fs-xl-3 fs-xxl-4">Gallery</h1><img class="d-none d-lg-block line-icons mt-5" src="/assets/img/lineicons/camera.png" alt="icon" />
						<hr class="my-4 w-100 d-none d-lg-block opacity-25" />
						<div class="flex-between-center d-none d-lg-flex w-100 opacity-75" data-sidebar-link="page-link">
							<a @click="$emit('goPage','blogs')" class="sidebar-nav btn btn-link text-decoration-none px-1">
								<i class="me-lg-2 me-xl-2 me-xxl-4">&#8592;</i>
								<span class="text-capitalize">Blogs</span>
							</a>
							<a @click="$emit('goPage','services')" class="sidebar-nav btn btn-link text-decoration-none px-1">
								<span class="text-capitalize">Services</span>
								<i class="ms-lg-2 ms-xl-2 ms-xxl-4">&#8594;</i>
							</a>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		data () {
			return {
				sldr1: [
					{src:'/assets/img/gallery/gallery-1.png',title:'Why do you use?'},
					{src:'/assets/img/gallery/gallery-28.png',title:'What Does It Mean?'},
					{src:'/assets/img/gallery/gallery-29.png',title:'How to Generate?'},
				],
				sldr2: [
					{src:'/assets/img/gallery/gallery-25.png',title:'Why do you use?'},
					{src:'/assets/img/gallery/gallery-26.png',title:'What Does It Mean?'},
					{src:'/assets/img/gallery/gallery-27.png',title:'How to Generate?'},
				],
				sldr3: [
					{src:'/assets/img/gallery/gallery-15.png',title:'Why do you use?'},
					{src:'/assets/img/gallery/gallery-21.jpg',title:'What Does It Mean?'},
					{src:'/assets/img/gallery/gallery-22.jpg',title:'How to Generate?'},
				],
				slctIndx: 0,
			}
		},
		mounted () {
			setInterval(() => {
				if (this.slctIndx < this.sldr1.length-1) this.slctIndx += 1;
				else this.slctIndx = 0;
			},8000);
		}
	}
</script>