<script>
	import { Link } from 'svelte-navigator';
import Choose from "../components/Choose.svelte";
import Counter from "../components/Counter.svelte";
import Services from "../components/Services.svelte";

    let pageName = "Feature Page"
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
                <h2>Features</h2>
              </div>
              <div class="blog-breadcrumbs-right">
                <ol class="breadcrumb">
                  <li>You are here</li>
                  <li><Link to="/">Home</Link></li>                  
                  <li class="active">Features</li>
                </ol>
              </div>
            </div>
          </div>
        </div>        
      </div>      
    </section>
    <Services />
    <Choose />>
    <Counter />
    <!--=========== End Counter SECTION ================-->
    <section id="extraFeatures">
      <div class="container">
        <div class="row">
         <div class="col-lg-6 col-md-6 col-sm-12">
            <div class="departments-area">
              <div class="section-heading">
                <h2>Our Departments</h2>
                <div class="line"></div>
              </div>
              <!-- Start Departments Accordion -->
              <div class="panel-group custom-panel" id="accordion">
                <div class="panel panel-default">
                  <div class="panel-heading">
                    <h4 class="panel-title">
                      <a data-toggle="collapse" data-parent="#accordion" href="#collapseOne">
                        Pediatric Clinic <span class="fa fa-minus"></span>
                      </a>
                    </h4>
                  </div>
                  <div id="collapseOne" class="panel-collapse collapse in">
                    <div class="panel-body">
                     <p> Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident.</p>
                    </div>
                  </div>
                </div>
                <div class="panel panel-default">
                  <div class="panel-heading">
                    <h4 class="panel-title">
                      <a data-toggle="collapse" data-parent="#accordion" href="#collapseTwo">
                        Dental Implants<span class="fa fa-plus"></span>
                      </a>
                    </h4>
                  </div>
                  <div id="collapseTwo" class="panel-collapse collapse">
                    <div class="panel-body">
                    <img class="img-center" src="/esperanza/images/choose-us-img3.jpg" alt="img">
                     <p> Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod.
                     </p>
                    </div>
                  </div>
                </div>
                <div class="panel panel-default">
                  <div class="panel-heading">
                    <h4 class="panel-title">
                      <a data-toggle="collapse" data-parent="#accordion" href="#collapseThree">
                        Laryngological Clinic  <span class="fa fa-plus"></span>
                      </a>
                    </h4>
                  </div>
                  <div id="collapseThree" class="panel-collapse collapse">
                    <div class="panel-body">
                      <p>Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.</p>
                    </div>
                  </div>
                </div>
                <div class="panel panel-default">
                  <div class="panel-heading">
                    <h4 class="panel-title">
                      <a data-toggle="collapse" data-parent="#accordion" href="#collapseFour">
                        Laryngological Clinic<span class="fa fa-plus"></span>
                      </a>
                    </h4>
                  </div>
                  <div id="collapseFour" class="panel-collapse collapse">
                    <div class="panel-body">
                    <img class="img-center" src="/esperanza/images/choose-us-img3.jpg" alt="img">
                     <p> Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod.
                     </p>
                    </div>
                  </div>
                </div>
                <div class="panel panel-default">
                  <div class="panel-heading">
                    <h4 class="panel-title">
                      <a data-toggle="collapse" data-parent="#accordion" href="#collapseFive">
                        Rehabilitation Therapy Clinic <span class="fa fa-plus"></span>
                      </a>
                    </h4>
                  </div>
                  <div id="collapseFive" class="panel-collapse collapse">
                    <div class="panel-body">
                      <p>Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
         </div>
         <div class="col-lg-6 col-md-6 col-sm-12">
           <div class="how-works-area">
             <div class="section-heading">
                <h2>How we work</h2>
                <div class="line"></div>
              </div>
              <div class="how-works">
                <ul class="nav nav-tabs" id="myTab">
                  <li class="active"><a href="#experiment" data-toggle="tab">Experiment</a></li>
                  <li><a href="#monitor" data-toggle="tab">Monitor</a></li>
                  <li><a href="#clean" data-toggle="tab">Clean</a></li>
                  <li><a href="#fast" data-toggle="tab">Fast</a></li>
                  <li><a href="#support" data-toggle="tab">Support</a></li>
                </ul>
                <!-- Tab panes -->
                <div class="tab-content">
                  <div class="tab-pane fade in active" id="experiment">
                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
                  </div>
                  <div class="tab-pane fade " id="monitor">
                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
                    <img class="img-center" src="/esperanza/images/choose-us-img2.jpg" alt="img">
                  </div>
                  <div class="tab-pane fade " id="clean">
                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
                  </div>
                  <div class="tab-pane fade " id="fast">
                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
                     <img class="img-center" src="/esperanza/images/choose-us-img1.jpg" alt="img">
                  </div>
                  <div class="tab-pane fade " id="support">
                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>                     
                  </div>
                </div>
              </div>
           </div>
         </div>
       </div>         
      </div>
    </section>
</main>