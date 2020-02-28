<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>project Demand Template</title>
	<link rel="stylesheet" href="css/style.css">
	<link rel="stylesheet" href="css/font-awesome.css">
	 <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>

    <style>
       
        .title {
            font-family: candara;
            font-size: 50px;
            font-weight: 700;
            color: #00AEFE;
            text-align: center;
        }

        p {
            line-height: 1.5em;
        }

        h1+p,
        p+p {
            margin-top: 10px;
        }

        .container1 {
            padding: 0px 80px;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        .card-wrap {
            margin: 10px;
            -webkit-transform: perspective(800px);
            transform: perspective(800px);
            -webkit-transform-style: preserve-3d;
            transform-style: preserve-3d;
            cursor: pointer;
        }

        .card-wrap:hover .card-info {
            -webkit-transform: translateY(0);
            transform: translateY(0);
        }

        .card-wrap:hover .card-info p {
            opacity: 1;
        }

        .card-wrap:hover .card-info,
        .card-wrap:hover .card-info p {
            transition: 0.6s cubic-bezier(0.23, 1, 0.32, 1);
        }

        .card-wrap:hover .card-info:after {
            transition: 5s cubic-bezier(0.23, 1, 0.32, 1);
            opacity: 1;
            -webkit-transform: translateY(0);
            transform: translateY(0);
        }

        .card-wrap:hover .card-bg {
            transition: 0.6s cubic-bezier(0.23, 1, 0.32, 1), opacity 5s cubic-bezier(0.23, 1, 0.32, 1);
            opacity: 0.8;
        }

        .card-wrap:hover .card {
            transition: 0.6s cubic-bezier(0.23, 1, 0.32, 1), box-shadow 2s cubic-bezier(0.23, 1, 0.32, 1);
            box-shadow: rgba(255, 255, 255, 0.2) 0 0 40px 5px, white 0 0 0 1px, rgba(0, 0, 0, 0.66) 0 30px 60px 0, inset #333 0 0 0 5px, inset white 0 0 0 6px;
        }

        .card {
            position: relative;
            flex: 0 0 240px;
            width: 240px;
            height: 320px;
            background-color: #333;
            overflow: hidden;
            border-radius: 10px;
            box-shadow: rgba(0, 0, 0, 0.66) 0 30px 60px 0, inset #333 0 0 0 5px, inset rgba(255, 255, 255, 0.5) 0 0 0 6px;
            transition: 1s cubic-bezier(0.445, 0.05, 0.55, 0.95);
        }

        .card-bg {
            opacity: 0.5;
            position: absolute;
            top: -20px;
            left: -20px;
            width: 100%;
            height: 100%;
            padding: 20px;
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            transition: 1s cubic-bezier(0.445, 0.05, 0.55, 0.95), opacity 5s 1s cubic-bezier(0.445, 0.05, 0.55, 0.95);
            pointer-events: none;
        }

        .card-info {
            padding: 20px;
            position: absolute;
            bottom: 0;
            color: #fff;
            -webkit-transform: translateY(40%);
            transform: translateY(40%);
            transition: 0.6s 1.6s cubic-bezier(0.215, 0.61, 0.355, 1);
        }

        .card-info p {
            opacity: 0;
            text-shadow: black 0 2px 3px;
            transition: 0.6s 1.6s cubic-bezier(0.215, 0.61, 0.355, 1);
            font-family: candara;
        }

        .card-info * {
            position: relative;
            z-index: 1;
        }

        .card-info:after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            z-index: 0;
            width: 100%;
            height: 100%;
            background-image: linear-gradient(to bottom, transparent 0%, rgba(0, 0, 0, 0.6) 100%);
            background-blend-mode: overlay;
            opacity: 0;
            -webkit-transform: translateY(100%);
            transform: translateY(100%);
            transition: 5s 1s cubic-bezier(0.445, 0.05, 0.55, 0.95);
        }

        .card-info h1 {
            font-family: candara;
            font-size: 36px;
            font-weight: 700;
            text-shadow: rgba(0, 0, 0, 0.5) 0 10px 10px;
        }
    </style>
</head>
<body>
	<!-- -----------------------header qismi kodi--------------------- -->
	<main>
		<div class="layer"></div>
		<header>
			<img src="images/banner.jpg">
		</header>
	<div class="container">
		<aside>
			<div class="logo">
				<a href="#!">
					<i class="fa fa-line-chart"></i> <span>Demand</span>
				</a>
			</div>
		<div class="menu">
			<a href="#!" data-id="#menu1">Home</a>
			<a href="#!" data-id="#menu2">About Us</a>
			<a href="#!" data-id="#menu3">Services</a>
			<a href="#!" data-id="#menu4">Blog</a>
			<a href="#!" data-id="#menu5">Contact</a>
			<a href="#!" data-id="#menu6"><span>Get Started</span></a>
		</div>
		</aside>
	</div>
	
	<div class="container">
		<div class="text">
			<div class="h1">
				<h1>Corporate <span>Business</span></h1>
				<h2>Best Technology Demand</h2>
			</div>
			<div class="p">
				Lorem ipsum dolor sit amet, consectetur adipisicing elit. Asperiores vitae, ipsam ea similique molestias placeat nostrum ab, atque doloremque doloribus 
			</div>
			<div class="button">
				<button class="first">Read more</button>
				<button class="second">Get started</button>
			</div>
		</div>
	</aside>
	</main>

	<button class="up"><i class="fa fa-long-arrow-up"></i></button>

	<!-- -------------------------info qismining kodi------------------ -->

	 <h1 class="title">Our continents</h1>

    <div id="app" class="container1">
        <card
            data-image="https://images.unsplash.com/photo-1479660656269-197ebb83b540?dpr=2&auto=compress,format&fit=crop&w=1199&h=798&q=80&cs=tinysrgb&crop=">  
            <h1 slot="header">Canyons</h1>
            <p slot="content">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
        </card>
        <card
            data-image="https://images.unsplash.com/photo-1479659929431-4342107adfc1?dpr=2&auto=compress,format&fit=crop&w=1199&h=799&q=80&cs=tinysrgb&crop=">
            <h1 slot="header">Beaches</h1>
            <p slot="content">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
        </card>
        <card
            data-image="https://images.unsplash.com/photo-1479644025832-60dabb8be2a1?dpr=2&auto=compress,format&fit=crop&w=1199&h=799&q=80&cs=tinysrgb&crop=">
            <h1 slot="header">Trees</h1>
            <p slot="content">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
        </card>
        <card
            data-image="https://images.unsplash.com/photo-1479621051492-5a6f9bd9e51a?dpr=2&auto=compress,format&fit=crop&w=1199&h=811&q=80&cs=tinysrgb&crop=">
            <h1 slot="header">Lakes</h1>
            <p slot="content">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
        </card>
    </div>


	<div class="container" id="menu1">
		<div class="info">
			<div class="box">
				<div class="icon1">
					<i class="fa fa-fort-awesome"></i>
				</div>
				<div class="statistics">
					<h3>Statistics</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate labore unde, expedita deserunt? Et laborum</p>
				</div>
			</div>
			<div class="box">
				<div class="icon2">
					<i class="fa fa-key"></i>
				</div>
				<div class="statistics">
					<h3>Security</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate labore unde, expedita deserunt? Et laborum</p>
				</div>
			</div>
			<div class="box">
				<div class="icon3">
					<i class="fa fa-tasks"></i>
				</div>
				<div class="statistics">
					<h3>Presentation</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate labore unde, expedita deserunt? Et laborum</p>
				</div>
			</div>
		</div>
	</div>

	<!-- -------------------------picture------------------------------ -->

	<div class="container" id="menu2">
		<main class="picture">
			<div class="picture">
				<img src="images/about.jpg">
			</div>
			<div class="fonttext">
				<h3>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatem cum aliquam Voluptatem aliquam</h3>

				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam dicta maxime molestias sunt dolore. Corrupti consectetur iusto quae, placeat repellendus recusandae eveniet! Quae vero, eaque voluptatum non aperiam corporis adipisci! Lorem ipsum dolor sit amet, consectetur adipisicing elit. Laborum voluptatem autem iste voluptas voluptatum nulla, dignissimos</p>
			</div>
		</main>
	</div>

	<!-- --------------------------main qismi----------------------------- -->

	<div class="container">
		<div class="information">
			<div class="box">
				<div class="icon1">
					<i class="fa fa-print"></i>
				</div>
				<div class="statistics">
					<h3>Statistics</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate</p>
				</div>
			</div>
			<div class="box">
				<div class="icon2">
					<i class="fa fa-newspaper-o"></i>
				</div>
				<div class="statistics">
					<h3>Security</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate</p>
				</div>
			</div>
			<div class="box">
				<div class="icon3">
					<i class="fa fa-unlock"></i>
				</div>
				<div class="statistics">
					<h3>Presentation</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate</p>
				</div>
			</div>

			<div class="box">
				<div class="icon4">
					<i class="fa fa-product-hunt"></i>
				</div>
				<div class="statistics">
					<h3>Security</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate</p>
				</div>
			</div>
		</div>
	</div>
	<!-- -----------------------black statistic information---------------- -->

	<div class="blackfon" id="menu3">
		<div class="container">
			<h1>Latest <span>Statistical Information</span></h1>
			<div class="boxes">
				<div class="box">
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam natus ipsa libero nisi labore ad pariatur consequatur quasi sint modi porro saepe, cupiditate sed asperiores ullam laudantium sit dolorem. Animi. cupiditate sed asperiores ullam laudantium sit dolorem. Animi.</p>
				<button>Read More</button>
			</div>
			<div class="box">
				<img src="images/stats1.jpg">
			</div>
			<div class="box">
				<span class="text">ONLINE MARKETING</span>
				<div class="stats">
					<div class="background1"></div>
				</div>
				
				<span class="text">FINANCIAL CONSULTING</span>
				<div class="stats">
					<div class="background2"></div>
				</div>
				
				<span class="text">CREATIVE PROJECTS</span>
				<div class="stats">
					<div class="background3"></div>
				</div>
				
				<span class="text">FUTURE ENHANCEMENT</span>
				<div class="stats">
					<div class="background4"></div>
				</div>
				
				<span class="text">24/7 SUPPORT</span>
				<div class="stats">
					<div class="background5"></div>
				</div>
				
			</div>
			</div>
		</div>
	</div>

	<!-- -----------------------marketing qismi--------------------------- -->

	<main class="marketing" id="menu4">
		<div class="container">
			<p class="marketproduct">Our Marketing <span>Products</span></p>
			<div class="boxes">
				<div class="box1">
					<div class="hover">
						<i class="fa fa-print"></i>
						<h2>Consulting</h2>
					</div>
				</div>
				<div class="box2">
					<div class="hover">
						<i class="fa fa-newspaper-o"></i>
						<h2>Marketing</h2>
					</div>
				</div>
				<div class="box3">
					<div class="hover">
						<i class="fa fa-unlock"></i>
						<h2>IT Software</h2>
					</div>
				</div>
				<div class="box4">
					<div class="hover">
						<i class="fa fa-product-hunt"></i>
						<h2>Cloud Technology</h2>
					</div>
				</div>
			</div>
		</div>
	</main>

<!-- ---------------------growth qismi----------------------- -->

<div class="growth">
	<img src="images/stats-bg.jpg">
	<div class="theme"></div>
		<div class="container">
				<div class="texts">
					<h1>Our <span>Statistical Growth</span></h1>
				</div>
			<div class="box11">
				<div class="statistica">
					<p><i class="fa fa-credit-card"></i></p>
					<h1>1568</h1>
					<p class="cooparate">Partners</p>
				</div>
				<div class="statistica">
					<p><i class="fa fa-users"></i></p>
					<h1>1900</h1>
					<p class="cooparate">Customers</p>
				</div>
				<div class="statistica">
					<p><i class="fa fa-dollar"></i></p>
					<h1>1422</h1>
					<p class="cooparate">Projects</p>
				</div>
				<div class="statistica">
					<p><i class="fa fa-globe"></i></p>
					<h1>400</h1>
					<p class="cooparate">Employees</p>
				</div>
				<div class="infobox">
					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Modi animi sunt, eveniet.</p>
				</div>
			</div>
		</div>
</div>

<!-- -------------------------mobile apps----------------------------- -->
<section class="body1">
 <div class="container2">
    <div class="box111">
      <div class="content111">
        <h2>01</h2>
        <h3>Service One</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsa veritatis excepturi distinctio tempore incidunt quas non quaerat harum alias eum</p>
        <a href="#!">Read More</a>
      </div>
    </div>

    <div class="box111">
      <div class="content111">
        <h2>02</h2>
        <h3>Service Two</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsa veritatis excepturi distinctio tempore incidunt quas non quaerat harum alias eum</p>
        <a href="#!">Read More</a>
      </div>
    </div>

    <div class="box111">
      <div class="content111">
        <h2>03</h2>
        <h3>Service Three</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsa veritatis excepturi distinctio tempore incidunt quas non quaerat harum alias eum</p>
        <a href="#!">Read More</a>
      </div>
    </div>

    <div class="box111">
      <div class="content111">
        <h2>04</h2>
        <h3>Service Four</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsa veritatis excepturi distinctio tempore incidunt quas non quaerat harum alias eum</p>
        <a href="#!">Read More</a>
      </div>
    </div>
  </div>
</section>

<div class="mobile" id="menu5">
	<div class="container">
		<div class="pages">
			<div class="apps">
				<p class="iconfooter"><i class="fa fa-mobile"></i>
					<span>Mobile Apps</span></p>
				<p class="textfooter">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
			</div>
			<div class="apps">
				<p class="iconfooter"><i class="fa fa-shield"></i>
					<span>Security Tips</span></p>
				<p class="textfooter">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
			</div>
			<div class="apps">
				<p class="iconfooter"><i class="fa fa-globe"></i>
					<span>Various Branches</span></p>
				<p class="textfooter">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
			</div>
			<div class="apps">
				<p class="iconfooter"><i class="fa fa-phone"></i>
					<span>24 / 7 Support</span></p>
				<p class="textfooter">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
			</div>
		</div>
	</div>
</div>

<!-- ------------------------------footer------------------------------- -->

<footer>
	<div class="container" id="menu6">
		<div class="footer">
			<div class="linking">
				<h2>Contact Info</h2>
				<p><i class="fa fa-map-marker"></i>
				<span>2130 Fulton Street, San Diego,
				CA 94117-1080 USA</span>
				</p>
				<p><i class="fa fa-phone"></i><span>1-600-1234-567</span></p>
				<p><i class="fa fa-phone"></i><span>1-600-1234-567</span></p>
				<p><i class="fa fa-envelope"></i><span><a href="#!">info@example.com</a></span></p>
			</div>
			<div class="linking">
				<h2>Our Platforms</h2>
				<p><a href="#!">Digital Trade Marketing</a></p>
				<p><a href="#!">Software Development</a></p>
				<p><a href="#!">Cloud Marketing</a></p>
				<p><a href="#!">Business Intelligence</a></p>
				<p><a href="#!">Modern Technology</a></p>
			</div>
			<div class="linking">
				<h2>Media Center</h2>
				<p><a href="#!">Press Release</a></p>
				<p><a href="#!">Vision & Values</a></p>
				<p><a href="#!">Winning Awards</a></p>
				<p><a href="#!">Networking</a></p>
			</div>
			<div class="linking">
				<h2>Resources</h2>
				<p><a href="#!">24 / 7 Help Line</a></p>
				<p><a href="#!">Nearest Branch</a></p>
				<p><a href="#!">Guidance</a></p>
				<p><a href="#!">Download</a></p>
				<p><a href="#!">Mobile App</a></p>
			</div>
			<div class="linking">
				<h2>Other Links</h2>
				<p><a href="#!">Our Services</a></p>
				<p><a href="#!">About Us</a></p>
				<p><a href="#!">Company Blog</a></p>
				<p><a href="#!">Contact Us</a></p>
			</div>
		</div>
	</div>
	<div class="liner">
		<div class="container">
			<div class="leftright">
				<div class="left">
					<span>&copy; 2019 Demand. All rights reserved | Design by 
					<a href="#!">W3Layouts.</a></span>
				</div>
				<div class="right">
					<a href="#!">Privacy Policy</a>
					<a href="#!">Terms & Conditions</a>
					<a href="#!">Disclaimer.</a>
				</div>
			</div>
		</div>
	</div>
</footer>

	<script src="jQuery/jQuery.js"></script>
	<script src="jQuery/owl.carousel.min.js"></script>
	<script src="jQuery/main.js"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/vue/2.0.1/vue.min.js"></script>

    <script>
        Vue.config.devtools = true;

        Vue.component("card", {
            template: `
    <div class="card-wrap"
      @mousemove="handleMouseMove"
      @mouseenter="handleMouseEnter"
      @mouseleave="handleMouseLeave"
      ref="card">
      <div class="card"
        :style="cardStyle">
        <div class="card-bg" :style="[cardBgTransform, cardBgImage]"></div>
        <div class="card-info">
          <slot name="header"></slot>
          <slot name="content"></slot>
        </div>
      </div>
    </div>`,
            mounted() {
                this.width = this.$refs.card.offsetWidth;
                this.height = this.$refs.card.offsetHeight;
            },
            props: ["dataImage"],
            data: () => ({
                width: 0,
                height: 0,
                mouseX: 0,
                mouseY: 0,
                mouseLeaveDelay: null
            }),

            computed: {
                mousePX() {
                    return this.mouseX / this.width;
                },
                mousePY() {
                    return this.mouseY / this.height;
                },
                cardStyle() {
                    const rX = this.mousePX * 30;
                    const rY = this.mousePY * -30;
                    return {
                        transform: `rotateY(${rX}deg) rotateX(${rY}deg)`
                    };

                },
                cardBgTransform() {
                    const tX = this.mousePX * -40;
                    const tY = this.mousePY * -40;
                    return {
                        transform: `translateX(${tX}px) translateY(${tY}px)`
                    };

                },
                cardBgImage() {
                    return {
                        backgroundImage: `url(${this.dataImage})`
                    };

                }
            },

            methods: {
                handleMouseMove(e) {
                    this.mouseX = e.pageX - this.$refs.card.offsetLeft - this.width / 2;
                    this.mouseY = e.pageY - this.$refs.card.offsetTop - this.height / 2;
                },
                handleMouseEnter() {
                    clearTimeout(this.mouseLeaveDelay);
                },
                handleMouseLeave() {
                    this.mouseLeaveDelay = setTimeout(() => {
                        this.mouseX = 0;
                        this.mouseY = 0;
                    }, 1000);
                }
            }
        });

        var app = new Vue({
            el: "#app"
        });
    </script>

</body>
</html>
