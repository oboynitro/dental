<script>
    import sliderData from "../data/slider.js"
</script>
<section id="sliderArea">
    <div class="top-slider">
        {#each sliderData as slide (slide.id)}
        <div class="top-slide-inner">
          <div class="slider-img">
            <img src={slide.src} alt={slide.title}>
          </div>
          <div class="slider-text">
            <h2>Hi, <strong>Welcome to</strong> Esperanza Health Plus, Your No. 1 Dental Solution</h2>
            <p>"<strong>Your Perfect Smile, </strong>Our Craft."</p>
          </div>
        </div>
        {/each}
    </div>
</section>