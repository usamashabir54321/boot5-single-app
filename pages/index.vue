<template>
	<main class="main" id="top">

			<!-- PRELOADER -->
		<div v-show="is_prelod" class="preloader" id="preloader">
			<div class="loader"><span> </span><span></span><span></span><span></span><span></span></div>
		</div>
			<!-- HOME INDEX PAGE PART - 1 -->
		<div class="offcanvas offcanvas-start home-content" :class="!actve_comp ? 'show' : ''" id="offcanvasStart">
			<div class="bg-holder overlay overlay-youtube" style="background-image:url(assets/img/header-split-youtube-backgroundd.png);">
				<!-- <iframe v-show="!is_prelod" class="yt-video loaded" style="width: 1160px; height: 852.5px; min-height: 1349px; min-width: 1864.89px;" width="640" height="560" src="https://www.youtube.com/embed/efHyAyT4Fko?&autoplay=1&loop=1&rel=0&showinfo=0&color=white&controls=0&playlist=efHyAyT4Fko&mute=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->
			</div>
			<!--/.bg-holder-->
			<div class="offcanvas-body d-flex flex-center">
				<div class="z-index-2">
					<h1 class="fw-bold fs-3 fs-lg-4 fs-xl-5 text-light">We are <span class="fw-bolder text-light">boots5</span></h1>
					<p class="fs-1 text-light" style="line-height: 1.2; opacity: 1;">For over 20 years we’ve worked with <br class="d-none d-lg-block">companies all around the globe.</p>
					<div class="mt-5">
						<a class="btn btn-outline-light mr-3" href="nav-eight-item-four-column.html#doc">Get a quote</a>
						<a class="btn btn-link mt-3 mt-sm-0 pl-0" href="nav-eight-item-four-column.html#portfolio">See works<span class="ms-2 fas fa-chevron-right"></span></a>
					</div>
				</div>
			</div>
		</div>
			<!-- HOME INDEX PAGE PART - 2 -->
		<div class="offcanvas offcanvas-end home-nav px-0" :class="!actve_comp ? 'show' : ''" id="offcanvasEnd">
			<div class="offcanvas-body p-0 position-lg-fixed position-relative">
				<div class="row vh-100 g-0 pt-3">
					<div class="col-12 vh-12 bg-black w-100 position-relative text-white nav-hover-zoom nav-blue-soft">
						<img class="nav-img" src="assets/img/card-bg-dark-img.png" alt="..." />
						<div class="card-img-overlay d-flex align-items-center h-100 px-5">
							<img class="nav-icons" src="assets/img/lineicons/diamond-4-1.png" alt="icon" />
							<a @click="actve_comp = 'about'" id="my_about_btn" class="text-light fs-1 fs-xl-2 fs-xxl-3 stretched-link items fw-bold text-decoration-none ps-4">About</a>
						</div>
					</div>
					<div class="col-12 vh-12 bg-black w-100 position-relative text-white nav-hover-zoom nav-cyan-soft">
						<img class="nav-img" src="assets/img/card-bg-dark-img.png" alt="..." />
						<div class="card-img-overlay d-flex align-items-center h-100 px-5">
							<img class="nav-icons" src="assets/img/lineicons/thunder-4-1.png" alt="icon" />
							<a @click="actve_comp = 'services'" class="text-light fs-1 fs-xl-2 fs-xxl-3 stretched-link items fw-bold text-decoration-none ps-4">Services</a>
						</div>
					</div>
					<div class="col-12 vh-12 bg-black w-100 position-relative text-white nav-hover-zoom nav-purple-soft">
						<img class="nav-img" src="assets/img/card-bg-dark-img.png" alt="..." />
						<div class="card-img-overlay d-flex align-items-center h-100 px-5">
							<img class="nav-icons" src="assets/img/lineicons/camera-4-1.png" alt="icon" />
							<a @click="actve_comp = 'gallery'" class="text-light fs-1 fs-xl-2 fs-xxl-3 stretched-link items fw-bold text-decoration-none ps-4">Gallery</a>
						</div>
					</div>
					<div class="col-12 vh-12 bg-black w-100 position-relative text-white nav-hover-zoom nav-indigo-soft">
						<img class="nav-img" src="assets/img/card-bg-dark-img.png" alt="..." />
						<div class="card-img-overlay d-flex align-items-center h-100 px-5">
							<img class="nav-icons" src="assets/img/lineicons/pencil-4-1.png" alt="icon" />
							<a @click="actve_comp = 'blogs'" class="text-light fs-1 fs-xl-2 fs-xxl-3 stretched-link items fw-bold text-decoration-none ps-4">Blogs</a>
						</div>
					</div>
					<div class="col-12 vh-12 bg-black w-100 position-relative text-white nav-hover-zoom nav-orange-dark">
						<img class="nav-img" src="assets/img/card-bg-dark-img.png" alt="..." />
						<div class="card-img-overlay d-flex align-items-center h-100 px-5">
							<img class="nav-icons" src="assets/img/lineicons/bubble-8-4.png" alt="icon" />
							<a @click="actve_comp = 'faq'" class="text-light fs-1 fs-xl-2 fs-xxl-3 stretched-link items fw-bold text-decoration-none ps-4">Faq</a>
						</div>
					</div>
					<div class="col-12 vh-12 bg-black w-100 position-relative text-white nav-hover-zoom nav-green-soft">
						<img class="nav-img" src="assets/img/card-bg-dark-img.png" alt="..." />
						<div class="card-img-overlay d-flex align-items-center h-100 px-5">
							<img class="nav-icons" src="assets/img/lineicons/map-8-4.png" alt="icon" />
							<a @click="actve_comp = 'contact'" class="text-light fs-1 fs-xl-2 fs-xxl-3 stretched-link items fw-bold text-decoration-none ps-4">Contact</a>
						</div>
					</div>
					<div class="col-12 vh-12 bg-black w-100 position-relative text-white nav-hover-zoom nav-indigo-dark">
						<img class="nav-img" src="assets/img/card-bg-dark-img.png" alt="..." />
						<div class="card-img-overlay d-flex align-items-center h-100 px-5">
							<img class="nav-icons" src="assets/img/lineicons/trophy-8-4.png" alt="icon" />
							<a @click="actve_comp = 'portfolio'" id="my_portfolio_btn" class="text-light fs-1 fs-xl-2 fs-xxl-3 stretched-link items fw-bold text-decoration-none ps-4">Portfolio</a>
						</div>
					</div>
				</div>
			</div>
		</div>

			<!-- PORTFOLIO PAGE -->
		<section class="page p-0" :class="actve_comp == 'portfolio' ? '' : 'd-none'" id="portfolio"><PagePortfolio @goIndex="actve_comp = ''" @goPage="goMyPage"/></section>
			<!-- ABOUT PAGE -->
		<section class="p-0 page" v-if="actve_comp == 'about'" id="about"><LazyPageAbout @goIndex="actve_comp = ''" @goPage="goMyPage"/></section>
			<!-- SERVICES PAGE -->
		<section class="p-0 page" v-if="actve_comp == 'services'" id="services"><LazyPageServices @goIndex="actve_comp = ''" @goPage="goMyPage"/></section>
			<!-- GALLERY PAGE -->
		<section class="p-0 page" v-if="actve_comp == 'gallery'" id="gallery"><LazyPageGallery @goIndex="actve_comp = ''" @goPage="goMyPage"/></section>
			<!-- BLOG PAGE -->
		<section class="p-0 page" v-if="actve_comp == 'blogs'" id="blogs"><LazyPageBlogs @goIndex="actve_comp = ''" @goPage="goMyPage"/></section>
			<!-- FAQ PAGE -->
		<section class="p-0 page" v-if="actve_comp == 'faq'" id="faq"><LazyPageFaq @goIndex="actve_comp = ''" @goPage="goMyPage"/></section>
			<!-- CONTACT PAGE -->
		<section class="page p-0" v-if="actve_comp == 'contact'" id="contact"><LazyPageContact @goIndex="actve_comp = ''" @goPage="goMyPage"/></section>

		<script src="/assets/js/bootstrap.js"></script>
		<script src="/assets/js/anchor.js" defer></script>
		<script src="/assets/js/lodash.min.js" defer></script>
		<script src="/assets/js/imagesloaded.pkgd.js" defer></script>
		<script src="/assets/js/theme.js" defer></script>
		<script src="/assets/js/isotope.pkgd.min.js" defer></script>
		<script src="/assets/js/packery-mode.pkgd.min.js" defer></script>
		<script src="/assets/js/countUp.umd.js" defer></script>

	</main>
</template>

<script>
	export default {
		name: 'Home',
		data () {
			return {
				is_prelod: true,
				actve_comp: '',
			}
		},
		mounted () {
			setTimeout(() => { this.is_prelod = false; },200);
		},
		methods: {
			goMyPage (comp_name) {this.actve_comp = comp_name;},
		},
	}
</script>

<style>
	body {overflow: unset !important;}
	.offcanvas-backdrop.fade.show {display: none;}
	a {cursor: pointer;}
	.modal-backdrop.show {opacity: 0.2 !important;}
	.swiper-pagination {
	    position: absolute;
	    transition: .3s opacity;
	    transform: translate3d(0,0,0);
	    z-index: 10;
	    display: contents;
	}
	.swiper-pagination span {
	    border-radius: 50%;
	    background-color: #000;
	    opacity: .2;
	    height: 15px;
	    width: 15px;
	    display: inline-block;
	    margin-right: 10px;
	}
	.swiper-pagination span.active {
		background: blue;
		opacity: 1;
	}
	.swiper-slide {
	    animation: fadeIn .3s linear;
	}
	@keyframes fadeIn {
		0% {opacity: 0.8;},
		100% {opacity: 1;}
	}
</style>