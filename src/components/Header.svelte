<script>
import { Link } from "svelte-navigator";

</script>
<Link class="scrollToTop" to="#"><i class="fa fa-heartbeat"></i></Link>
<header id="header">
    <div class="menu_area">
    <nav class="navbar navbar-default navbar-fixed-top" role="navigation">  
        <div class="container">
        <div class="navbar-header">
            <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            </button>
            <!-- <Link class="navbar-brand" to="/"><i class="fa fa-heartbeat"></i>WpF <span>Medinova</span></Link>               -->

            <a class="navbar-brand" href="/"><img src="/esperanza/img/logo.png" alt="logo" style="width: 14rem;"></a>                      
        </div>
        <div id="navbar" class="navbar-collapse collapse">
            <ul id="top-menu" class="nav navbar-nav navbar-right main-nav">
            <li><Link to="/">Home</Link></li>
            <li><Link to="features">Features</Link></li>
            <li><Link to="gallery">Gallery</Link></li>
            <li><Link to="contact">Contact</Link></li>
            </ul>
        </div>
        </div>     
    </nav>  
    </div>
</header>