<template>
    <section id="home" class="section welcome-area d-flex align-items-center h-100vh pt-0">
        <div class="container">
            <div class="row align-items-center justify-content-center">
                <!-- Welcome Intro Start -->
                <div class="col-12 col-md-10 col-lg-8">
                    <div class="welcome-intro text-center mt-0">
                        <h1 class="text-white">Appo <span class="badge badge-pill badge-light fw-4">v1.0</span></h1>
                        <h2 class="cd-headline clip fw-3 mt-2 mt-sm-3">
                            <span class="text-white">Built for</span>
                            <span class="cd-words-wrapper ml-2">
                                <b class="text-white is-visible">App Landing Page</b>
                                <b class="text-white">Software Landing Page</b>
                                <b class="text-white">Modern Web Design</b>
                                <b class="text-white">Product Landing</b>
                                <b class="text-white">Startup Business</b>
                            </span>
                        </h2>
                        <p class="text-white my-3">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto beatae, asperiores tempore repudiandae saepe aspernatur unde voluptate sapiente quia ex.</p>
                        <div class="button-group">
                            <a href="#" class="btn btn-bordered-white"><span>Buy Now</span></a>
                            <a href="#" class="btn btn-bordered-white">Explore Demos</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="shapes-container">
            <div class="wave-animation">
                <!-- Wave Animation -->
                <svg class="waves" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 24 150 28" preserveAspectRatio="none" shape-rendering="auto">
                    <defs>
                        <path id="gentle-wave" d="M-160 44c30 0 58-18 88-18s 58 18 88 18 58-18 88-18 58 18 88 18 v44h-352z" />
                    </defs>
                    <g class="parallax">
                        <use xlink:href="#gentle-wave" x="48" y="0" fill="rgba(255,255,255,0.7" />
                        <use xlink:href="#gentle-wave" x="48" y="3" fill="rgba(255,255,255,0.5)" />
                        <use xlink:href="#gentle-wave" x="48" y="5" fill="rgba(255,255,255,0.3)" />
                        <use xlink:href="#gentle-wave" x="48" y="7" fill="#fff" />
                    </g>
                </svg>
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>

</style>