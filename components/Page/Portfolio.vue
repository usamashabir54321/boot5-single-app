<template>
	<div class="container-fluid">
		<div class="row">
			<div class="col-lg-8 col-xl-9 order-1 order-lg-0 pt-10 pt-lg-7 pt-xxl-8 pb-0">
				<div class="row flex-center">
					<div class="col-lg-10 col-xl-7">
						<div class="text-center mb-5 mb-lg-6">
							<h2><span class="fw-medium">Our</span> Lates Works</h2>
						</div>

						<div class="mb-5 sortable" data-filter-nav="data-filter-nav">
							<ul class="nav menu justify-content-center mb-2" data-filter-nav="data-filter-nav">
								<li class="nav-item ls">
									<div class="isotope-nav px-3 px-lg-2 px-xl-3 text-decoration-none active" data-filter="*"> <i class="fas fa-th fs-0 me-2"></i>All</div>
								</li>
								<li class="nav-item ls me-2">
									<div class="isotope-nav px-3 px-lg-2 px-xl-3 text-decoration-none" data-filter=".photography"> <i class="fas fa-camera fs-0 me-2 fs-0"></i>Photography</div>
								</li>
								<li class="nav-item ls">
									<div class="isotope-nav px-3 px-lg-2 px-xl-3 text-decoration-none" data-filter=".studio"> <i class="fas fa-lightbulb fs-0 me-2 fs-0"></i>Studio</div>
								</li>
								<li class="nav-item ls">
									<div class="isotope-nav px-3 px-lg-2 px-xl-3 text-decoration-none" data-filter=".interior"> <i class="fas fa-home fs-0 me-2 fs-0"></i>Interior</div>
								</li>
								<li class="nav-item ls">
									<div class="isotope-nav px-3 px-lg-2 px-xl-3 text-decoration-none" data-filter=".illustration"> <i class="fas fa-pen fs-0 me-2 fs-0"></i>Illustration</div>
								</li>
							</ul>
						</div>

						<div class="row g-2 mt-2" id="portfolio-gallery" data-isotope='{"layoutMode":"packery"}'>
							<div class="col-6 masonry-item interior">
								<div class="card hoverbox overflow-hidden"><img class="img-fluid" src="/assets/img/projects/portfolio-1.png" alt="" />
									<div class="card-img-overlay">
										<div class="px-4 hoverbox-content d-flex flex-column flex-center"><a class="stretched-link" href="#" data-bs-toggle="modal" data-bs-target="#modalFullscreen"><i class="fas fa-eye fs-2 text-light"> </i></a></div>
									</div>
								</div>
							</div>
							<div class="col-6 col-md-3 masonry-item photography">
								<div class="card hoverbox overflow-hidden"><img class="img-fluid" src="/assets/img/projects/portfolio-2.png" alt="" />
									<div class="card-img-overlay">
										<div class="px-4 hoverbox-content d-flex flex-column flex-center"><a class="stretched-link" href="#" data-bs-toggle="modal" data-bs-target="#modalFullscreen"><i class="fas fa-eye fs-2 text-light"> </i></a></div>
									</div>
								</div>
							</div>
							<div class="col-6 col-md-3 masonry-item photography">
								<div class="card hoverbox overflow-hidden"><img class="img-fluid" src="/assets/img/projects/portfolio-3.png" alt="" />
									<div class="card-img-overlay">
										<div class="px-4 hoverbox-content d-flex flex-column flex-center"><a class="stretched-link" href="#" data-bs-toggle="modal" data-bs-target="#modalFullscreen"><i class="fas fa-eye fs-2 text-light"> </i></a></div>
									</div>
								</div>
							</div>
							<div class="col-6 masonry-item studio">
								<div class="card hoverbox overflow-hidden"><img class="img-fluid" src="/assets/img/projects/portfolio-4.png" alt="" />
									<div class="card-img-overlay">
										<div class="px-4 hoverbox-content d-flex flex-column flex-center"><a class="stretched-link" href="#" data-bs-toggle="modal" data-bs-target="#modalFullscreen"><i class="fas fa-eye fs-2 text-light"> </i></a></div>
									</div>
								</div>
							</div>
							<div class="col-6 masonry-item interior">
								<div class="card hoverbox overflow-hidden"><img class="img-fluid" src="/assets/img/projects/portfolio-8.png" alt="" />
									<div class="card-img-overlay">
										<div class="px-4 hoverbox-content d-flex flex-column flex-center"><a class="stretched-link" href="#" data-bs-toggle="modal" data-bs-target="#modalFullscreen"><i class="fas fa-eye fs-2 text-light"> </i></a></div>
									</div>
								</div>
							</div>
							<div class="col-6 col-md-3 masonry-item photography">
								<div class="card hoverbox overflow-hidden"><img class="img-fluid" src="/assets/img/projects/portfolio-5.png" alt="" />
									<div class="card-img-overlay">
										<div class="px-4 hoverbox-content d-flex flex-column flex-center"><a class="stretched-link" href="#" data-bs-toggle="modal" data-bs-target="#modalFullscreen"><i class="fas fa-eye fs-2 text-light"> </i></a></div>
									</div>
								</div>
							</div>
							<div class="col-6 col-md-3 masonry-item photography">
								<div class="card hoverbox overflow-hidden"><img class="img-fluid" src="/assets/img/projects/portfolio-6.png" alt="" />
									<div class="card-img-overlay">
										<div class="px-4 hoverbox-content d-flex flex-column flex-center"><a class="stretched-link" href="#" data-bs-toggle="modal" data-bs-target="#modalFullscreen"><i class="fas fa-eye fs-2 text-light"> </i></a></div>
									</div>
								</div>
							</div>
							<div class="col-6 col-md-3 masonry-item studio illustration">
								<div class="card hoverbox overflow-hidden"><img class="img-fluid" src="/assets/img/projects/portfolio-7.png" alt="" />
									<div class="card-img-overlay">
										<div class="px-4 hoverbox-content d-flex flex-column flex-center"><a class="stretched-link" href="#" data-bs-toggle="modal" data-bs-target="#modalFullscreen"><i class="fas fa-eye fs-2 text-light"> </i></a></div>
									</div>
								</div>
							</div>
							<div class="col-6 col-md-3 masonry-item photography">
								<div class="card hoverbox overflow-hidden"><img class="img-fluid" src="/assets/img/projects/portfolio-10.png" alt="" />
									<div class="card-img-overlay">
										<div class="px-4 hoverbox-content d-flex flex-column flex-center"><a class="stretched-link" href="#" data-bs-toggle="modal" data-bs-target="#modalFullscreen"><i class="fas fa-eye fs-2 text-light"> </i></a></div>
									</div>
								</div>
							</div>
							<div class="col-6 col-md-3 masonry-item photography">
								<div class="card hoverbox overflow-hidden"><img class="img-fluid" src="/assets/img/projects/portfolio-12.png" alt="" />
									<div class="card-img-overlay">
										<div class="px-4 hoverbox-content d-flex flex-column flex-center"><a class="stretched-link" href="#" data-bs-toggle="modal" data-bs-target="#modalFullscreen"><i class="fas fa-eye fs-2 text-light"> </i></a></div>
									</div>
								</div>
							</div>
							<div class="col-6 masonry-item illustration">
								<div class="card hoverbox overflow-hidden"><img class="img-fluid" src="/assets/img/projects/portfolio-9.png" alt="" />
									<div class="card-img-overlay">
										<div class="px-4 hoverbox-content d-flex flex-column flex-center"><a class="stretched-link" href="#" data-bs-toggle="modal" data-bs-target="#modalFullscreen"><i class="fas fa-eye fs-2 text-light"> </i></a></div>
									</div>
								</div>
							</div>
							<div class="col-6 col-sm-3 masonry-item studio illustration">
								<div class="card hoverbox overflow-hidden"><img class="img-fluid" src="/assets/img/projects/portfolio-11.png" alt="" />
									<div class="card-img-overlay">
										<div class="px-4 hoverbox-content d-flex flex-column flex-center"><a class="stretched-link" href="#" data-bs-toggle="modal" data-bs-target="#modalFullscreen"><i class="fas fa-eye fs-2 text-light"> </i></a></div>
									</div>
								</div>
							</div>
						</div>

					</div>
					
					<div class="col-12">
						<div class="row justify-content-center pt-3d">
							<div class="col-lg-8 col-xl-7 mb-n5 mb-md-n8 mb-lg-n6 mb-xl-n9 mt-8">
								<div class="card bg-backdrop">
									<div class="card-body p-2 px-lg-2 px-xl-5">
										<div class="py-5 text-center">
											<h2 class="fs-1 fs-xxl-2 fw-bolder">Start your next project with us</h2>
											<p class="mb-4 text-900">Join the talented group of artists and imaginators</p><a class="btn hover-top btn-boots-purple" href="#!">Join Boots5 </a>
										</div>
									</div>
								</div>
							</div>
							<div class="col-lg-10"><img class="w-100" src="/assets/img/cta/cta-portfolio.png" alt="..." style="border-radius:1rem;" /></div>
						</div>
						<div class="row justify-content-center my-3">
							<div class="col-12 col-lg-10">
								<div class="card bg-soft-orange-2">
									<div class="card-body py-3">
										<div class="row">
											<div class="col-lg-6 text-center text-lg-start">
												<p class="fs--1 my-2 fw-bold text-gradient-orange-soft-2">All rights Reserved &copy; Your Company, 2021</p>
											</div>
											<div class="col-lg-6 d-lg-flex align-self-center justify-content-end text-center">
												<p class="fs--1 mb-0 text-gradient-orange-soft-2">Made with <span class="fas fa-heart mx-1 text-warning"></span>by<a href="https://themewagon.com/"> Themewagon</a></p>
											</div>
										</div>
									</div>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
			<div class="col-lg-4 col-xl-3 col-12 position-absolute position-lg-relative ps-lg-0">
				<div class="sticky-top py-4 sticky-area" data-sidebar-close="sidebar-close">
					<div @click="$emit('goIndex')" class="btn-close-boots-container times">
						<div class="btn-close-boots"></div>
					</div>
					<div class="bg-holder sidebar-rounded" style="background-image:url(/assets/img/sidebars/portfolio.png);"></div>
					<!--/.bg-holder-->
					<div class="position-relative d-lg-flex flex-column justify-content-end align-items-end h-100 px-lg-4 px-xxl-5">
						<h1 class="text-white text-vertical px-5 px-lg-0 opacity-50 fs-xl-3 fs-xxl-4">Blogs</h1><img class="d-none d-lg-block line-icons mt-5" src="/assets/img/lineicons/trophy.png" alt="icon" />
						<hr class="my-4 w-100 d-none d-lg-block opacity-25" />
						<div class="flex-between-center d-none d-lg-flex w-100 opacity-75" data-sidebar-link="page-link">
							<a @click="$emit('goPage','gallery')" class="sidebar-nav btn btn-link text-decoration-none px-1">
								<i class="me-lg-2 me-xl-2 me-xxl-4">&#8592;</i>
								<span class="text-capitalize">Gallery</span>
							</a>
							<a @click="$emit('goPage','faq')" class="sidebar-nav btn btn-link text-decoration-none px-1">
								<span class="text-capitalize">Faq</span>
								<i class="ms-lg-2 ms-xl-2 ms-xxl-4">&#8594;</i>
							</a>
						</div>
					</div>
				</div>
			</div>
		</div>

		<!-- MODAL FULL SCREEN -->
		<div class="modal fade" id="modalFullscreen">
			<div class="modal-dialog modal-xl">
				<div class="modal-content">
					<div class="d-flex justify-content-end border-bottom-0 py-5 px-5"><button class="btn-close position-fixed z-index-1" type="button" data-bs-dismiss="modal" aria-label="Close"></button></div>
					<section class="pt-7">
						<div class="container-fluid">
							<div class="row justify-content-center pb-5">
								<div class="col-lg-8 col-xl-7">
									<div class="modal-body"><img class="img-fluid" src="/assets/img/projects/p-modal-9.png" alt="...">
										<div class="row my-5">
											<h2 class="mb-5 text-start">Abstraction of the blues</h2>
											<div class="col-lg-6 col-xl-5 text-start">
												<h5>Category </h5>
												<p>Branding</p>
												<h5>Client </h5>
												<p>ThemeWagon</p><a class="text-800 text-" href="https://themewagon.com"><i class="fas fa-link me-2"></i>https://themewagon.com</a>
											</div>
											<div class="col-lg-6 col-xl-7 border-start text-start mt-4 mt-lg-0">
												<h5>Brief</h5>
												<p>I must explain to you how all this mistaken idea of reprobating pleasure and extolling pain arose. To do so, I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness.</p>
											</div>
										</div>
										<div class="mb-6">
											<p class="my-3 text-start">I must explain to you how all this mistaken idea of reprobating pleasure and extolling pain arose. To do so, I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness. No one rejects, dislikes or avoids pleasure itself, because it is pleasure, but because those who do not know how to pursue pleasure rationally encounter consequences that are extremely painful.</p>
											<p class="my-3 text-start">To do so, I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness.No one rejects, dislikes or avoids pleasure itself, because it is pleasure, but because those who do not know how to pursue pleasure rationally encounter consequences that are extremely painful.</p>
										</div><img class="mb-4 img-fluid" src="/assets/img/projects/portfolio-modal-2.png" alt="...">
										<h4>Etaoin shrdlu</h4>
										<div class="mb-6">
											<p class="my-3 text-start"> Must explain to you how all this mistaken idea of reprobating pleasure and extolling pain arose. To do so, I will give you a complete account of the system, and expound the actual teachings of the great explorer of the truth, the master-builder of human happiness.</p>
											<p class="my-3 text-start">The discovery of the text's origin is attributed to Richard McClintock, a Latin scholar at Hampden–Sydney College. McClintock connected Lorem ipsum to Cicero's writing sometime before 1982 while searching for instances of the Latin word consectetur, which was rarely used in classical literature</p>
										</div>
										<div class="row">
											<div class="col-lg-6 text-center text-lg-start mb-6 mb-lg-0"><img class="img-fluid" src="/assets/img/projects/portfolio-modal-5.png" alt="...">
												<h4 class="mt-3">Etaoin shrdlu</h4>
												<p class="px-3 px-lg-0">He rejects pleasures to secure other greater pleasures, or else he endures pains to avoid worse pains. </p>
											</div>
											<div class="col-lg-6 text-center text-lg-start mb-6 mb-lg-0"> <img class="img-fluid" src="/assets/img/projects/portfolio-modal-7.png" alt="...">
												<h4 class="mt-3">Etaoin shrdlu</h4>
												<p class="px-3 px-lg-0">The wise man therefore always holds in these matters to this principle of selection. </p>
											</div>
										</div>
										<div class="row">
											<div class="col-lg-6 text-center text-lg-start mb-6 mb-lg-0"><img class="img-fluid" src="/assets/img/projects/portfolio-modal-6.png" alt="..."></div>
											<div class="col-lg-6 text-center text-lg-start mb-6 mb-lg-0"> <img class="img-fluid" src="/assets/img/projects/portfolio-modal-8.png" alt="...">
												<h4 class="mt-3">Etaoin shrdlu</h4>
												<p class="px-3 px-lg-0">What follows is H. Rackham's translation, as printed in the Loeb Classical Library edition</p>
											</div>
										</div>
										<img class="mb-2 mt-2 img-fluid" src="/assets/img/projects/portfolio-modal-1.png" alt="...">
										<img class="mb-2 img-fluid" src="/assets/img/projects/portfolio-modal-3.png" alt="...">
										<img class="mb-2 img-fluid" src="/assets/img/projects/portfolio-modal-4.png" alt="...">
										<h4 class="mt-3">Etaoin shrdlu</h4>
										<p>He rejects pleasures to secure other greater pleasures, or else he endures pains to avoid worse pains. </p>
									</div>
								</div>
							</div>
						</div><!-- end of .container-->
					</section>
				</div>
			</div>
		</div>

	</div>
</template>

<style scoped>
	@media (min-width: 1140px) {
		.modal-xl {
			max-width: 1440px;
		}
	}
</style>