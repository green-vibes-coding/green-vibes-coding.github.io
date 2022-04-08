<!DOCTYPE html>

<!--
	Author:		    Víctor Giró
	URL:		    -
    Designed By:    Víctor Giro
	Version:	    1.0	
-->

<html lang = "en">

    <head>
        <meta charset = "UTF-8">
        <meta http-equiv = "X-UA-Compatible" content = "IE=edge">
        <meta name = "viewport" content = "width=device-width, initial-scale=1.0">
        <meta name = "description" content = "Victor - Responsive One Page HTML5">
        <meta name = "keywords" content = "HTML5, Bootsrtrap, One Page, Responsive, Template, Portfolio" />
		    <meta name = "author" content = "Victor Giro">
        <title>Victor Giro</title>
		    <link rel = "icon" type = "image" href = "img/favicon.png">

        <!-- Mobile Metas -->
		    <meta name = "viewport" content = "width=device-width, initial-scale=1">

        <!-- Google Fonts  -->
		    <link href = 'http://fonts.googleapis.com/css?family=Roboto:400,700,500' rel = 'stylesheet' type = 'text/css'> <!-- Body font -->
		    <link href = 'http://fonts.googleapis.com/css?family=Lato:300,400' rel = 'stylesheet' type = 'text/css'> <!-- Navbar font -->
        
        <!-- Libs and Plugins CSS -->
		    <link rel = "stylesheet" href="inc/bootstrap/css/bootstrap.min.css">
		    <link rel = "stylesheet" href="inc/animations/css/animate.min.css">
	    	<link rel = "stylesheet" href="inc/font-awesome/css/font-awesome.min.css"> <!-- Font Icons -->
		    <link rel = "stylesheet" href="inc/owl-carousel/css/owl.carousel.css">
	    	<link rel = "stylesheet" href="inc/owl-carousel/css/owl.theme.css">
        
        <!-- Theme CSS -->
        <link rel = "stylesheet" href = "css/reset.css">
	    	<link rel = "stylesheet" href = "css/style.css">
	    	<link rel = "stylesheet" href = "css/mobile.css">
        
        <!-- Skin CSS -->
    		<link rel = "stylesheet" href = "css/skin/cool-gray.css">

        

    </head>

    <body data-spy = "scroll" data-target = "#main-navbar">
        <div class = "page-loader"></div>  <!-- Display loading image while page loads -->
    	  <div class = "body">
        
            <!--========== BEGIN HEADER ==========-->
            <header id = "header" class = "header-main">

                <!-- Begin Navbar -->
                <nav id = "main-navbar" class = "navbar navbar-default navbar-fixed-top" role = "navigation"> <!-- Classes: navbar-default, navbar-inverse, navbar-fixed-top, navbar-fixed-bottom, navbar-transparent. Note: If you use non-transparent navbar, set "height: 98px;" to #header -->
                    
                    <div class = "container">

                    <!-- Brand and toggle get grouped for better mobile display -->
                    <div class = "navbar-header">
                        <button type = "button" class = "navbar-toggle collapsed" data-toggle = "collapse" data-target = "#bs-example-navbar-collapse-1">
                            <span class = "sr-only">Toggle navigation</span>
                            <span class = "icon-bar"></span>
                            <span class = "icon-bar"></span>
                            <span class = "icon-bar"></span>
                        </button>

                        <a class = "navbar-brand page-scroll" href = "index.html">Victor</a>
                    </div>

                    <!-- Collect the nav links, forms, and other content for toggling -->
                    <div class = "collapse navbar-collapse" id = "bs-example-navbar-collapse-1">
                        <ul class = "nav navbar-nav navbar-right">
                            <li><a class = "page-scroll" href = "body">Home</a></li>
                            <li><a class = "page-scroll" href = "#about-section">About</a></li>
                            <li><a class = "page-scroll" href = "#services-section">Services</a></li>
                            <li><a class = "page-scroll" href = "#portfolio-section">Works</a></li>
                            <li><a class = "page-scroll" href = "#contact-section">Contact</a></li>
                        </ul>
                    </div><!-- /.navbar-collapse -->
                  </div><!-- /.container -->
                </nav>
                <!-- End Navbar -->

            </header>
            <!-- ========= END HEADER =========-->
            
            
            
            
        	<!-- Begin text carousel intro section -->
			<section id = "text-carousel-intro-section" class = "parallax" data-stellar-background-ratio = "0.5" style = "background-image: url(img/slider-bg2.jpg);">
				
				<div class = "container">
					<div class = "caption text-center text-white" data-stellar-ratio = "0.7">

						<div id = "owl-intro-text" class = "owl-carousel">
							
                            <div class = "item">
								<h1>I'm Victor Giro</h1>
								<p>A student web developer and a programmer</p>
                                <div class = "extra-space-l"></div>
								<a class = "btn btn-blank" href = "" target = "_blank" role = "button">View More!</a>
							</div>
							
                            <div class = "item">
								<h1>Join me</h1>
								<p>To the greatest Journey</p>
								<div class = "extra-space-l"></div>
								<a class = "btn btn-blank" href = "" target = "_blank" role = "button">View More!</a>
							</div>

							<div class = "item">
								<h1>I have Awesome things</h1>
								<p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
								<div class = "extra-space-l"></div>
								<a class = "btn btn-blank" href = "" target = "_blank" role = "button">View More!</a>
							</div>
						
                        </div>

					</div> <!-- /.caption -->
				</div> <!-- /.container -->

			</section>
			<!-- End text carousel intro section -->
                
                
                
                
            <!-- Begin about section -->
			<section id="about-section" class="page bg-style1">
                <!-- Begin page header-->
                <div class="page-header-wrapper">
                    <div class="container">
                        <div class="page-header text-center wow fadeInUp" data-wow-delay="0.3s">
                            <h2>About Me</h2>
                            <div class="devider"></div>
                            <p class="subtitle">little information</p>
                        </div>
                    </div>
                </div>
                <!-- End page header-->

                <!-- Begin rotate box-1 -->
                <div class = "rotate-box-1-wrapper">
                    <div class = "container">
                        <div class = "row">
                            <div class = "col-md-3 col-sm-6">
                                <a href = "#" class="rotate-box-1 square-icon wow zoomIn" data-wow-delay="0">
                                    <span class = "rotate-box-icon"><i class="fa fa-user"></i></span>
                                    <div class = "rotate-box-info">
                                        <h4>Who I Am?</h4>
                                        <p>I am a student currently studying Cross-Platform Application Development</p>
                                    </div>
                                </a>
                            </div>

                            <div class="col-md-3 col-sm-6">
                                <a href="#" class="rotate-box-1 square-icon wow zoomIn" data-wow-delay="0.2s">
                                    <span class="rotate-box-icon"><i class="fa fa-diamond"></i></span>
                                    <div class="rotate-box-info">
                                        <h4>What Do I Do?</h4>
                                        <p>Lorem ipsum dolor sit amet set, consectetur utes anet adipisicing elit, sed do eiusmod tempor incidist.</p>
                                    </div>
                                </a>
                            </div>

                            <div class="col-md-3 col-sm-6">
                                <a href="#" class="rotate-box-1 square-icon wow zoomIn" data-wow-delay="0.4s">
                                    <span class="rotate-box-icon"><i class="fa fa-heart"></i></span>
                                    <div class="rotate-box-info">
                                        <h4>Why I Do It?</h4>
                                        <p>Lorem ipsum dolor sit amet set, consectetur utes anet adipisicing elit, sed do eiusmod tempor incidist.</p>
                                    </div>
                                </a>
                            </div>
                            
                            <div class="col-md-3 col-sm-6">
                                <a href="#" class="rotate-box-1 square-icon wow zoomIn" data-wow-delay="0.6s">
                                    <span class="rotate-box-icon"><i class="fa fa-clock-o"></i></span>
                                    <div class="rotate-box-info">
                                        <h4>Since When?</h4>
                                        <p>Lorem ipsum dolor sit amet set, consectetur utes anet adipisicing elit, sed do eiusmod tempor incidist.</p>
                                    </div>
                                </a>
                            </div>
                            
                        </div> <!-- /.row -->
                    </div> <!-- /.container -->
                </div>
                <!-- End rotate box-1 -->
                
                <div class="extra-space-l"></div>
                
                <!-- Begin page header--> 
                <div class="page-header-wrapper">
                    <div class="container">
                        <div class="page-header text-center wow fadeInUp" data-wow-delay="0.3s">
                            <h4>My Skills</h4>
                        </div>
                    </div>
                </div>
                <!-- End page header-->
                
                <!-- Begin Our Skills -->
                <div class = "our-skills">
                	<div class = "container">
                    	<div class = "row">
                        
                        	<div class = "col-sm-6">
                                <div class = "skill-bar wow slideInLeft" data-wow-delay = "0.2s">
                                    <div class = "progress-lebel">
                                        <h6>Photoshop & Illustrator</h6>
                                    </div>
                                    <div class = "progress">
                                      <div class = "progress-bar" role = "progressbar" aria-valuenow = "75" aria-valuemin = "0" aria-valuemax = "100" style = "width: 75%;">
                                      </div>
                                    </div>
                                </div>
                            </div>
                            
                            <div class = "col-sm-6">
                                <div class = "skill-bar wow slideInRight" data-wow-delay = "0.2s">
                                    <div class = "progress-lebel">
                                        <h6>Java</h6>
                                    </div>
                                    <div class = "progress">
                                      <div class = "progress-bar" role = "progressbar" aria-valuenow = "85" aria-valuemin = "0" aria-valuemax = "100" style = "width: 85%;">
                                      </div>
                                    </div>
                                </div>
                            </div>
                            
                            <div class = "col-sm-6">
                                <div class = "skill-bar wow slideInLeft" data-wow-delay = "0.4s">
                                    <div class = "progress-lebel">
                                        <h6>Html & Css</h6>
                                    </div>
                                    <div class = "progress">
                                      <div class = "progress-bar" role = "progressbar" aria-valuenow = "95" aria-valuemin = "0" aria-valuemax = "100" style = "width: 95%;">
                                      </div>
                                    </div>
                                </div>
                            </div>
                            
                            <div class = "col-sm-6">
                                <div class = "skill-bar wow slideInRight" data-wow-delay = "0.4s">
                                    <div class = "progress-lebel">
                                        <h6>JavaScript & Php</h6>
                                    </div>
                                    <div class = "progress">
                                      <div class = "progress-bar" role = "progressbar" aria-valuenow = "70" aria-valuemin = "0" aria-valuemax = "100" style = "width: 70%;">
                                      </div>
                                    </div>
                                </div>
                            </div>
                            
                        </div> <!-- /.row -->
                    </div> <!-- /.container -->
                </div>
                <!-- End Our Skill -->
          </section>
          <!-- End about section -->

              
              
              
          <!-- Begin cta -->
          <section id="cta-section">
          	<div class="cta">
            	<div class="container">
                	<div class="row">
                    
                    	<div class="col-md-9">
                        	<h1>Download My Pdf</h1>
                            <p>Inspired by nature, follow technology, appreciate the classics. You can build modern & professional websites with Unika. The possibilities are just endless.</p>
                        </div>
                        
                        <div class = "col-md-3">
                        	<div class = "cta-btn wow bounceInRight" data-wow-delay = "0.4s">
                                <a class = "btn btn-default btn-lg" href = "file:///C:/Users/vigir/Desktop/My%20web/img/My%20Pdf.pdf" target = "_blank" role = "button">Download</a>
                        	</div>
                        </div>
                        
                    </div> <!-- /.row -->
                </div> <!-- /.container -->
            </div>
          </section>
          <!-- End cta -->

              
              
              
            <!-- Begin Services -->
            <section id="services-section" class="page text-center">
                <!-- Begin page header-->
                <div class="page-header-wrapper">
                    <div class="container">
                        <div class="page-header text-center wow fadeInDown" data-wow-delay="0.4s">
                            <h2>Services</h2>
                            <div class="devider"></div>
                            <p class="subtitle">what we really know how</p>
                        </div>
                    </div>
                </div>
                <!-- End page header-->
            
                <!-- Begin roatet box-2 -->
                <div class="rotate-box-2-wrapper">
                    <div class="container">
                        <div class="row">
                            <div class="col-md-3 col-sm-6">
                                <a href="#" class="rotate-box-2 square-icon text-center wow zoomIn" data-wow-delay="0">
                                    <span class="rotate-box-icon"><i class="fa fa-mobile"></i></span>
                                    <div class="rotate-box-info">
                                        <h4>App Development</h4>
                                        <p>Lorem ipsum dolor sit amet set, consectetur utes anet adipisicing elit, sed do eiusmod tempor incidist.</p>
                                    </div>
                                </a>
                            </div>
            
                            <div class="col-md-3 col-sm-6">
                                <a href="#" class="rotate-box-2 square-icon text-center wow zoomIn" data-wow-delay="0.2s">
                                    <span class="rotate-box-icon"><i class="fa fa-pie-chart"></i></span>
                                    <div class="rotate-box-info">
                                        <h4>Ui Design</h4>
                                        <p>Lorem ipsum dolor sit amet set, consectetur utes anet adipisicing elit, sed do eiusmod tempor incidist.</p>
                                    </div>
                                </a>
                            </div>
            
                            <div class="col-md-3 col-sm-6">
                                <a href="#" class="rotate-box-2 square-icon text-center wow zoomIn" data-wow-delay="0.4s">
                                    <span class="rotate-box-icon"><i class="fa fa-cloud"></i></span>
                                    <div class="rotate-box-info">
                                        <h4>Cloud Hosting</h4>
                                        <p>Lorem ipsum dolor sit amet set, consectetur utes anet adipisicing elit, sed do eiusmod tempor incidist.</p>
                                    </div>
                                </a>
                            </div>
                            
                            <div class="col-md-3 col-sm-6">
                                <a href="#" class="rotate-box-2 square-icon text-center wow zoomIn" data-wow-delay="0.6s">
                                    <span class="rotate-box-icon"><i class="fa fa-pencil"></i></span>
                                    <div class="rotate-box-info">
                                        <h4>Coding Pen</h4>
                                        <p>Lorem ipsum dolor sit amet set, consectetur utes anet adipisicing elit, sed do eiusmod tempor incidist.</p>
                                    </div>
                                </a>
                            </div>
                            
                        </div> <!-- /.row -->
                    </div> <!-- /.container -->
                    
                    <div class="container">
                        <!-- Cta Button -->
                        <div class="extra-space-l"></div>
                        <div class="text-center">
                    		<a class="btn btn-default btn-lg-xl" href="file:///C:/Users/vigir/Desktop/My%20web/img/My%20Pdf.pdf" target="_blank" role="button">Large Button</a>
                        </div>
                    </div> <!-- /.container -->                       
                </div>
                <!-- End rotate-box-2 -->
            </section>
            <!-- End Services -->
              
              
              
              
            <!-- Begin testimonials -->
            <section id="testimonial-section">
                <div id="testimonial-trigger" class="testimonial text-white parallax" data-stellar-background-ratio="0.5" style="background-image: url(img/testimonial-bg.jpg);">
                    <div class="cover"></div>
                    <!-- Begin page header-->
                    <div class="page-header-wrapper">
                        <div class="container">
                            <div class="page-header text-center wow fadeInDown" data-wow-delay="0.4s">
                                <h2>Reviews</h2>
                                <div class="devider"></div>
                                <p class="subtitle">What people say about me</p>
                            </div>
                        </div>
                    </div>
                    <!-- End page header-->
                    <div class="container">
                        <div class="testimonial-inner center-block text-center">
                            <div id="owl-testimonial" class="owl-carousel">
                                <div class="item">
                                    <blockquote>
                                        <p>"This was my first experience with him and outperformed my expectation! They know there stuff and I highly recommend them! A+++".</p>
                                        <footer><cite title="Source Title">Daniel Garcia</cite></footer>
                                    </blockquote>
                                </div>
                                <div class="item">
                                    <blockquote>
                                        <p>"Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                                        tempor incididunt ut labore et dolore magna aliqua."</p>
                                        <footer><cite title="Source Title">Carles Bonet</cite></footer>
                                    </blockquote>
                                </div>
                                <div class="item">
                                    <blockquote>
                                        <p>"Quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
                                        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
                                        cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
                                        proident, sunt in culpa qui officia deserunt mollit".</p>
                                        <footer><cite title="Source Title">Rafael Fernandez</cite></footer>
                                    </blockquote>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- End testimonials -->
                

                
                
            <!-- Begin Portfolio -->
            <section id="portfolio-section" class="page bg-style1">
            	<div class="container">
                    <div class="row">
                        <div class="col-md-12">
                            <div class="portfolio">
                                <!-- Begin page header-->
                                <div class="page-header-wrapper">
                                    <div class="container">
                                        <div class="page-header text-center wow fadeInDown" data-wow-delay="0.4s">
                                            <h2>My Works</h2>
                                            <div class="devider"></div>
                                            <p class="subtitle">What I'm proud of</p>
                                        </div>
                                    </div>
                                </div>
                                <!-- End page header-->
                                <div class="portfoloi_content_area" >
                                    <div class="portfolio_menu" id="filters">
                                        <ul>
                                            <li class="active_prot_menu"><a href="#porfolio_menu" data-filter="*">all</a></li>
                                            <li><a href="#porfolio_menu" data-filter=".websites">websites</a></li>
                                            <li><a href="#porfolio_menu" data-filter=".webDesign" >web design</a></li>
                                            <li><a href="#porfolio_menu" data-filter=".appsDevelopment">apps development</a></li>
                                            <li><a href="#porfolio_menu" data-filter=".GraphicDesign">graphic design</a></li>
                                            <li><a href="#porfolio_menu" data-filter=".responsive">responsive</a></li>
                                        </ul>
                                    </div>
                                    <div class="portfolio_content">
                                        <div class="row"  id="portfolio">
                                            <div class="col-xs-12 col-sm-4 appsDevelopment">
                                                <div class="portfolio_single_content">
                                                    <img src="img/portfolio/p1.jpg" alt="title"/>
                                                    <div>
                                                        <a href="#">Skull Awesome</a>
                                                        <span>Subtitle</span>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="col-xs-12 col-sm-4 GraphicDesign">
                                                <div class="portfolio_single_content">
                                                    <img src="img/portfolio/p2.jpg" alt="title"/>
                                                    <div>
                                                        <a href="#">Photo Frame</a>
                                                        <span>Subtitle</span>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="col-xs-12 col-sm-4 responsive">
                                                <div class="portfolio_single_content">
                                                    <img src="img/portfolio/p3.jpg" alt="title"/>
                                                    <div>
                                                        <a href="#">Hand Shots</a>
                                                        <span>Subtitle</span>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="col-xs-12 col-sm-4 webDesign websites">
                                                <div class="portfolio_single_content">
                                                    <img src="img/portfolio/p4.jpg" alt="title"/>
                                                    <div>
                                                        <a href="#">Night Abstract</a>
                                                        <span>Subtitle</span>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="col-xs-12 col-sm-4 appsDevelopment websites">
                                                <div class="portfolio_single_content">
                                                    <img src="img//portfolio/p5.jpg" alt="title"/>
                                                    <div>
                                                        <a href="#">Joy of Independence</a>
                                                        <span>Subtitle</span>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="col-xs-12 col-sm-4 GraphicDesign">
                                                <div class="portfolio_single_content">
                                                    <img src="img/portfolio/p6.jpg" alt="title"/>
                                                    <div>
                                                        <a href="#">Night Crawlers</a>
                                                        <span>Subtitle</span>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="col-xs-12 col-sm-4 responsive">
                                                <div class="portfolio_single_content">
                                                    <img src="img/portfolio/p7.jpg" alt="title"/>
                                                    <div>
                                                        <a href="#">Last Motel</a>
                                                        <span>Subtitle</span>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="col-xs-12 col-sm-4 GraphicDesign">
                                                <div class="portfolio_single_content">
                                                    <img src="img/portfolio/p8.jpg" alt="title"/>
                                                    <div>
                                                        <a href="#">Dirk Road</a>
                                                        <span>Subtitle</span>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="col-xs-12 col-sm-4 websites">
                                                <div class="portfolio_single_content">
                                                    <img src="img/portfolio/p9.jpg" alt="title"/>
                                                    <div>
                                                        <a href="#">Old is Gold</a>
                                                        <span>Subtitle</span>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- End portfolio -->
            
                
                
                
            <!-- Begin counter up -->
            <section id="counter-section">                					
				<div id="counter-up-trigger" class="counter-up text-white parallax" data-stellar-background-ratio="0.5" style="background-image: url(img/counter-bg.jpg);">
					<div class="cover"></div>
                    <!-- Begin page header-->
                    <div class="page-header-wrapper">
                        <div class="container">
                            <div class="page-header text-center wow fadeInDown" data-wow-delay="0.4s">
                                <h2>Some Fun Facts</h2>
                                <div class="devider"></div>
                                <p class="subtitle">Before anyone is not told</p>
                            </div>
                        </div>
                    </div>
                    <!-- End page header-->
					<div class="container">

						<div class="row">

							<div class="fact text-center col-md-3 col-sm-6">
								<div class="fact-inner">
									<i class="fa fa-users fa-3x"></i>
                                    <div class="extra-space-l"></div>
									<span class="counter">6666</span>
									<p class="lead">Clients Worked With</p>
								</div>
							</div>

							<div class="fact text-center col-md-3 col-sm-6">
								<div class="fact-inner">
									<i class="fa fa-leaf fa-3x"></i>
                                    <div class="extra-space-l"></div>
									<span class="counter">5</span>
									<p class="lead">Completed Projects</p>
								</div>
							</div>

							<div class="fact text-center col-md-3 col-sm-6">
								<div class="fact-inner">
									<i class="fa fa-trophy fa-3x"></i>
                                    <div class="extra-space-l"></div>
									<span class="counter">55</span>
									<p class="lead">Winning Awards</p>
								</div>
							</div>

							<div class="fact last text-center col-md-3 col-sm-6">
								<div class="fact-inner">
									<i class="fa fa-coffee fa-3x"></i>
                                    <div class="extra-space-l"></div>
									<span class="counter">1100</span>
									<p class="lead">Cups of tea drinking</p>
								</div>
							</div>

						</div> <!-- /.row -->
					</div> <!-- /.container -->
				</div>
            </section>
			<!-- End counter up -->
                
                
                
            <!-- Begin social section -->
			<section id="social-section">
            
                 <!-- Begin page header-->
                <div class="page-header-wrapper">
                    <div class="container">
                        <div class="page-header text-center wow fadeInDown" data-wow-delay="0.4s">
                            <h2>Join Me</h2>
                            <div class="devider"></div>
                            <p class="subtitle">Follow me on social networks</p>
                        </div>
                    </div>
                </div>
                <!-- End page header-->
                
                <div class = "container">
                	<ul class = "social-list">
                		<li> <a href = "https://github.com/green-vibes-coding" class = "rotate-box-1 square-icon text-center wow zoomIn" data-wow-delay = "0.3s"><span class = "rotate-box-icon"><i class = "fa fa-github"></i></span></a></li>
                		<li> <a href = "https://www.facebook.com/profile.php?id=100080370813756" class = "rotate-box-1 square-icon text-center wow zoomIn" data-wow-delay = "0.4s"><span class = "rotate-box-icon"><i class = "fa fa-facebook"></i></span></a></li>
                		<li> <a href = "#" class = "rotate-box-1 square-icon text-center wow zoomIn" data-wow-delay = "0.5s"><span class = "rotate-box-icon"><i class = "fa fa-linkedin"></i></span></a></li>
                		<li> <a href = "https://twitter.com/green_vibes_O" class = "rotate-box-1 square-icon text-center wow zoomIn" data-wow-delay = "0.6s"><span class = "rotate-box-icon"><i class = "fa fa-twitter"></i></span></a></li>
                		<li> <a href = "https://www.pinterest.es/Green_Vibes_/_saved/" class = "rotate-box-1 square-icon text-center wow zoomIn" data-wow-delay = "0.7s"><span class = "rotate-box-icon"><i class = "fa fa-pinterest-p"></i></span></a></li>
                		<li> <a href = "https://www.instagram.com/_victorgiro_/" class = "rotate-box-1 square-icon text-center wow zoomIn" data-wow-delay = "0.8s"><span class = "rotate-box-icon"><i class = "fa fa-instagram"></i></span></a></li>                      
                    </ul>
                </div>
                
            </section>
            <!-- End social section -->
                
                
                
                
            <!-- Begin contact section -->
			<section id="contact-section" class="page text-white parallax" data-stellar-background-ratio="0.5" style="background-image: url(img/map-bg.jpg);">
            <div class="cover"></div>
            
                 <!-- Begin page header-->
                <div class="page-header-wrapper">
                    <div class="container">
                        <div class="page-header text-center wow fadeInDown" data-wow-delay="0.4s">
                            <h2>Contacts</h2>
                            <div class="devider"></div>
                            <p class="subtitle">All to contact me</p>
                        </div>
                    </div>
                </div>
                <!-- End page header-->
                
                <div class = "contact wow bounceInRight" data-wow-delay = "0.4s">
                    <div class = "container">
                    	<div class = "row">
                        
                            <div class = "col-sm-6">
                                <div class = "contact-info">
                                    <h4>My Address</h4>
                                    <ul class = "contact-address">
			                            <li><i class = "fa fa-map-marker fa-lg"></i>&nbsp; Barcelona, Plaça de Catalunya, 08002 ,<br><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Barcelona, Spain</li>
			                            <li><i class = "fa fa-phone"></i>&nbsp; +34   658 -78 -05 -94</li>
			                            <li><i class = "fa fa-envelope"></i> uninterestedness@gmail.com</li>
			                            <li><i class = "fa fa-user"></i> Victor Giro</li>
			                        </ul>
                                </div>
                            </div>
                        
                        	<div class = "col-sm-6">
                               
                                <div class = "contact-form">
                                	
                                    <h4>Write me</h4>
                                   
                                    <form role = "form">

                                        <div class = "form-group">
                                            <input type = "text" class = "form-control input-lg" placeholder = "Your Name" required>
                                        </div>
                                       
                                        <div class = "form-group">
                                            <input type = "email" class = "form-control input-lg" placeholder = "E-mail" required>
                                        </div>
                                        
                                        <div class = "form-group">
                                            <input type = "text" class = "form-control input-lg" placeholder = "Subject" required>
                                        </div>
                                        
                                        <div class = "form-group">
                                            <textarea class = "form-control input-lg" rows = "5" placeholder = "Message" required></textarea>
                                        </div>
                                        
                                        <button type = "submit" class = "btn wow bounceInRight" data-wow-delay = "0.8s">Send</button>
                                    
                                    </form>
                               
                                </div>	
                            
                            </div>
                                                                                
                        </div> <!-- /.row -->
                    </div> <!-- /.container -->
                </div>
            </section>
            <!-- End contact section -->
                
                

                
            <!-- Begin footer -->
            <footer class="text-off-white">
            
                <div class="footer-top">
                	<div class="container">
                    	<div class="row wow bounceInLeft" data-wow-delay="0.4s">

                            <div class = "col-sm-6 col-md-4">
                            	<h4>Useful Links</h4>
                                <ul class = "imp-links">
                                	<li><a href = "">About</a></li>
                                	<li><a href = "">Services</a></li>
                                	<li><a href = "">Press</a></li>
                                	<li><a href = "">Copyright</a></li>
                                	<li><a href = "">Advertise</a></li>
                                	<li><a href = "">Legal</a></li>
                                </ul>
                            </div>
                        
                        	<div class = "col-sm-6 col-md-4">
                                <h4>Subscribe</h4>
                            	<div id = "footer_signup">
                                    <div id = "email">
                                        <form id="subscribe" method="POST">
                                            <input type = "text" placeholder = "Enter email address" name = "email" id = "address" data-validate = "validate(required, email)"/>
                                            <button type = "submit">Submit</button>
                                            <span id = "result" class = "section-description"></span>
                                        </form> 
                                    </div>
                                </div> 
                                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p> 
                            </div>

                            <div class = "col-sm-12 col-md-4">
                                <h4>Recent Uploads</h4>
                                <div class = "single-tweet">
                                    <div class = "tweet-content"><span>@green-vibes-coding</span> Excepteur sint occaecat cupidatat non proident</div>
                                    <div class = "tweet-date">1 Hour ago</div>
                                </div>
                                <div class = "single-tweet">
                                    <div class = "tweet-content"><span>@green-vibes-coding</span> Excepteur sint occaecat cupidatat non proident uku shumaru</div>
                                    <div class = "tweet-date">1 Hour ago</div>
                                </div>
                            </div>
                            
                        </div> <!-- /.row -->
                    </div> <!-- /.container -->
                </div>

            </footer>
            <!-- End footer -->

            <a href="#" class="scrolltotop"><i class="fa fa-arrow-up"></i></a> <!-- Scroll to top button -->
                                              
        </div><!-- body ends -->
        
        
        
        
        <!-- Plugins JS -->
		<script src="inc/jquery/jquery-1.11.1.min.js"></script>
		<script src="inc/bootstrap/js/bootstrap.min.js"></script>
		<script src="inc/owl-carousel/js/owl.carousel.min.js"></script>
		<script src="inc/stellar/js/jquery.stellar.min.js"></script>
		<script src="inc/animations/js/wow.min.js"></script>
    <script src="inc/waypoints.min.js"></script>
		<script src="inc/isotope.pkgd.min.js"></script>
		<script src="inc/classie.js"></script>
		<script src="inc/jquery.easing.min.js"></script>
		<script src="inc/jquery.counterup.min.js"></script>
		<script src="inc/smoothscroll.js"></script>

		<!-- Theme JS -->
		<script src="js/theme.js"></script>

    </body> 

</html>
