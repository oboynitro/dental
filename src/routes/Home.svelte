<script>
	import { Link } from 'svelte-navigator';
import Choose from '../components/Choose.svelte';
import Counter from '../components/Counter.svelte';
import Services from '../components/Services.svelte';
import Slider from '../components/Slider.svelte';
import Testimonial from '../components/Testimonial.svelte';
</script>
<svelte:head>
        <script src="/esperanza/js/jquery.js"></script>
		<script src="/esperanza/js/bootstrap.min.js"></script>
		<script src="/esperanza/js/slick.min.js"></script>
		<script
			type="text/javascript"
			src="/esperanza/js/modernizr.custom.79639.js"
		></script>
		<script src="/esperanza/js/waypoints.min.js"></script>
		<script src="/esperanza/js/jquery.counterup.min.js"></script>
		<script src="/esperanza/js/snap.svg-min.js"></script>
		<script src="/esperanza/js/hovers.js"></script>
		<script src="/esperanza/js/photoswipe.min.js"></script>
		<script src="/esperanza/js/photoswipe-ui-default.min.js"></script>
		<script src="/esperanza/js/photoswipe-gallery.js"></script>
		<script src="/esperanza/js/custom.js"></script>
</svelte:head>
<main>
    <Slider />
    <section id="topFeature">
      <div class="row">
        <div class="col-lg-6 col-md-6">
          <div class="row">
            <div class="single-top-feature">
              <span class="fa fa-flask"></span>
              <h3>Emergency Care</h3>
              <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.</p>
              <div class="readmore_area">
                <Link to="contact" data-hover="Get in Touch"><span>Get in Touch</span></Link>
              </div>
            </div>
          </div>
        </div>
        
        <div class="col-lg-6 col-md-6">
          <div class="row">
            <div class="single-top-feature opening-hours">
              <span class="fa fa-clock-o"></span>
              <h3>Opening Hours</h3>
              <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh.</p>
              <ul class="opening-table">
                <li>
                  <span>Monday - Friday</span>
                  <div class="value">8.00 - 16.00</div>
                </li>
                <li>
                  <span>Saturday</span>
                  <div class="value">9.30 - 15.30</div>
                </li>
                <li>
                  <span>Sunday</span>
                  <div class="value">9.30 - 17.00</div>
                </li>
              </ul>              
            </div>
          </div>
        </div>
      </div>
    </section>
    <!--=========== END Top Feature SECTION ================-->
    <Services />
    <Choose />
    <Counter />
    <Testimonial />
</main>