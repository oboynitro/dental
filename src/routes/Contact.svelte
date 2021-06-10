<script>
	import { Link } from 'svelte-navigator';
    let pageName = "Contact Page"
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
		<script src="/esperanza/js/custom.js"></script>s
</svelte:head>
<main>
<section id="blogArchive">
      <div class="row">
        <div class="col-lg-12 col-md-12">
          <div class="blog-breadcrumbs-area">
            <div class="container">
              <div class="blog-breadcrumbs-left">
                <h2>Contact</h2>
              </div>
              <div class="blog-breadcrumbs-right">
                <ol class="breadcrumb">
                  <li>You are here</li>
                  <li><Link to="/">Home</Link></li>
                  <li class="active">Contact</li>
                </ol>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!--=========== BEGIN Google Map SECTION ================-->
    <section id="googleMap">
      <iframe title="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3281.297314036103!2d-86.74954699999999!3d34.672444999999996!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x88626565a94cdb25%3A0x74c206053b6a97c9!2s305+Intergraph+Way%2C+Madison%2C+AL+35758%2C+USA!5e0!3m2!1sen!2sbd!4v1431591462160" width="100%" height="500" frameborder="0" style="border:0"></iframe>
    </section>
    <!--=========== END Google Map SECTION ================-->
    <section id="contact">
      <div class="container">
        <div class="row">
          <div class="col-lg-offset-3 col-md-offset-3 col-lg-6 col-md-6 col-sm-12">
            <div class="contact-address">
              <div class="section-heading">
                <h2>Contact Information</h2>
                <div class="line"></div>
              </div>
               <p>The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters.</p>
              <address class="contact-info">
                <p><span class="fa fa-home"></span>305 Intergraph Way
                Madison, AL 35758, USA</p>
                <p><span class="fa fa-phone"></span>1.256.730.2000</p>
                <p><span class="fa fa-envelope"></span>info@wpfmedinova.com</p>
              </address>
              <h3>Social Media</h3>
              <div class="social-share">
               <ul>
                 <li><a href="#"><span class="fa fa-facebook"></span></a></li>
                 <li><a href="#"><span class="fa fa-twitter"></span></a></li>
                 <li><a href="#"><span class="fa fa-pinterest"></span></a></li>
                 <li><a href="#"><span class="fa fa-google-plus"></span></a></li>
                 <li><a href="#"><span class="fa fa-linkedin"></span></a></li>
               </ul>
             </div>
            </div>
          </div>
        </div>
      </div>
    </section>
</main>