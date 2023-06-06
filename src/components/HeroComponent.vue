<template>
  <section class="mt-5 hero">
            <div class="container">
                <div class="row">
                    <div class="col-6 d-flex flex-column justify-content-center align-items-center">
                        <div class="welcome-text w-75">
                            <h1 class="display-5 fw-bolder mb-3">
                                Plan Your Business with Nganuin
                            </h1>
                            <p>
                                Lorem ipsum dolor sit amet consectetur
                                adipisicing elit. Corporis necessitatibus
                                deserunt molestiae? lorem ipsum dolor sit amet
                                hahahahhahaha
                            </p>
                            <button
                                class="btn btn-primary btn-lg px-4 rounded-pill mt-5"
                            >
                                Get Started
                            </button>
                        </div>
                    </div>
                    <div class="col-6">
                        <lottie-player src="https://assets3.lottiefiles.com/packages/lf20_sk5h1kfn.json" background="transparent" speed="1"
                        style="width: 100%; height: auto;" loop autoplay></lottie-player>
                    </div>
                </div>
            </div>
        </section>
</template>

<script>
export default {
  name: 'HeroComponent',
  props: {
    // msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
