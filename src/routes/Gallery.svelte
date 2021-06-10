<script>
	import { Link } from 'svelte-navigator';
    import galleryData from "../data/gallery.js"
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
                <h2>Gallery</h2>
              </div>
              <div class="blog-breadcrumbs-right">
                <ol class="breadcrumb">
                  <li>You are here</li>
                  <li><Link to="/">Home</Link></li>
                  <li class="active">Gallery</li>
                </ol>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!--=========== BEGIN GALLERY SECTION ================-->
    <section id="gallery">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 col-md-12 col-sm-12">
            <div class="gallery-area">
              <!-- Start First Image Album  -->
              <div class="my-simple-gallery">
                <div class="section-heading">
                  <h2>Gallery</h2>
                  <div class="line"></div>
                </div>
                <div class="row">
                    {#each galleryData as gallery (gallery.id)}
                        <figure itemprop="associatedMedia" class="col-lg-4 col-md-4 col-sm-6 col-xs-12">
                            <a class="gallery-iteam" href={gallery.src} itemprop="contentUrl" data-size="1080x800">
                            <img src="{gallery.src}" itemprop="thumbnail" alt={gallery.title} />
                            <span class="image-effect"></span>
                            </a>
                        </figure>
                    {/each}
                </div>
              </div>
              <div class="pswp" tabindex="-1" role="dialog" aria-hidden="true">
                <div class="pswp__bg"></div>
                <div class="pswp__scroll-wrap">
                  <div class="pswp__container">
                      <div class="pswp__item"></div>
                      <div class="pswp__item"></div>
                      <div class="pswp__item"></div>
                  </div>
                  <div class="pswp__ui pswp__ui--hidden">
                    <div class="pswp__top-bar">
                        <div class="pswp__counter"></div>
                        <button class="pswp__button pswp__button--close" title="Close (Esc)"></button>
                        <button class="pswp__button pswp__button--share" title="Share"></button>
                        <button class="pswp__button pswp__button--fs" title="Toggle fullscreen"></button>
                        <button class="pswp__button pswp__button--zoom" title="Zoom in/out"></button>
                        <div class="pswp__preloader">
                            <div class="pswp__preloader__icn">
                              <div class="pswp__preloader__cut">
                                <div class="pswp__preloader__donut"></div>
                              </div>
                            </div>
                        </div>
                    </div>
                    <div class="pswp__share-modal pswp__share-modal--hidden pswp__single-tap">
                        <div class="pswp__share-tooltip"></div>
                    </div>
                    <button class="pswp__button pswp__button--arrow--left" title="Previous (arrow left)">
                    </button>
                    <button class="pswp__button pswp__button--arrow--right" title="Next (arrow right)">
                    </button>
                    <div class="pswp__caption">
                        <div class="pswp__caption__center"></div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
</main>