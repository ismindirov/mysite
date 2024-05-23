# mysite
My personal website ismindirov.com4
This is my website written in java and CSS
To make changes open index.html file with vscode and see # areas and read comments

Site is hosted in AWS S3+ cloudfront+ route53 


<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
	<meta name="description" content="Welcome to My Personal Website!">
	<meta name="author" content="Ismindirov Vlad">
	<title>Ismindirov Vlad - DevOps Engineer</title>
	<link rel="stylesheet" href="assets/vendors/themify-icons/css/themify-icons.css">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
	<link rel="stylesheet" href="assets/css/style.css">
	<link href="https://fonts.googleapis.com/css?family=Lato:400,700|Poppins:400,700&display=swap" rel="stylesheet">
	<!-- Р¤Р°РІС–РєРѕРЅ -->
	<link rel="icon" type="image/png" href="assets/imgs/logo.png">
</head>

<body data-spy="scroll" data-target=".navbar" data-offset="40" id="home">
	<div class="preloader">
		<svg class="preloader__image" role="img" viewBox="0 0 512 512">
			<path fill="#22652f"
				d="M304 48c0 26.51-21.49 48-48 48s-48-21.49-48-48 21.49-48 48-48 48 21.49 48 48zm-48 368c-26.51 0-48 21.49-48 48s21.49 48 48 48 48-21.49 48-48-21.49-48-48-48zm208-208c-26.51 0-48 21.49-48 48s21.49 48 48 48 48-21.49 48-48-21.49-48-48-48zM96 256c0-26.51-21.49-48-48-48S0 229.49 0 256s21.49 48 48 48 48-21.49 48-48zm12.922 99.078c-26.51 0-48 21.49-48 48s21.49 48 48 48 48-21.49 48-48c0-26.509-21.491-48-48-48zm294.156 0c-26.51 0-48 21.49-48 48s21.49 48 48 48 48-21.49 48-48c0-26.509-21.49-48-48-48zM108.922 60.922c-26.51 0-48 21.49-48 48s21.49 48 48 48 48-21.49 48-48-21.491-48-48-48z">
			</path>
		</svg>
	</div>


	<div class="wrapper">

		<!-- navigation -->
		<header class="nav">
			<div class="nav__container">
				<a href='#' class='nav__logo'>
					<!-- Р·РѕР±СЂР°Р¶РµРЅРЅСЏ Р»РѕРіРѕС‚РёРїСѓ -->
					<img class="logotype" src="assets/imgs/logo.png" alt="logo">
				</a>
				<div class='nav__menu menu'>
					<button type='button' class='menu__icon icon-menu'> <span></span></button>
					<nav class='menu__body'>
						<ul class='menu__list'>
							<li class='menu__item'><a href='#' class='menu__link' data-goto="#home"
									data-goto-top="100">Home</a>
							</li>
							<li class='menu__item'><a href='#' class='menu__link' data-goto="#about"
									data-goto-top="100">About</a>
							</li>
							<li class='menu__item'><a href='#' class='menu__link' data-goto="#skills"
									data-goto-top="100">Skills</a></li>
							<li class='menu__item'><a href='#' class='menu__link' data-goto="#projects" data-goto-top="100">My
									projects</a></li>
							<li class='menu__item'><a href='#' class='menu__link' data-goto="#certifications"
									data-goto-top="100">Certifications</a>
							</li>
							<li class='menu__item'><a href='#' class='menu__link' data-goto="#contact"
									data-goto-top="100">Contact</a></li>
						</ul>
					</nav>
				</div>
			</div>
		</header>
		<!-- End of navigation -->

		<!-- hero -->
		<section class="header">
			<div class="container about-section">
				<div class="infos">
					<h6 class="subtitle" id="home" data-watch="navigator" data-watch-threshold="0.2">Hello, I'm</h6>
					<h6 class="title">Ismindirov Vlad</h6>
					<p>DevOps Engineer</p>
					<div class="buttons pt-3">
						<a href="assets/Ismindirov_CV2.pdf" download="assets/Ismindirov_CV2.pdf"
							class="btn btn-primary rounded">DOWNLOAD CV</a>
					</div>
					<div class="socials mt-4">
						<a class="social-item" href="mailto:ismindirov@gmail.com" target="_blank" rel="noopener noreferrer"><i
								class="fas fa-envelope"></i></a>
						<a class="social-item" href="https://www.linkedin.com/in/ismindirov/" target="_blank"
							rel="noopener noreferrer"><i class="fab fa-linkedin-in"></i></a>
						<a class="social-item" href="https://t.me/DevOpsIsmindirov" target="_blank"
							rel="noopener noreferrer"><i class="fab fa-telegram-plane"></i></a>
						<a class="social-item" href="https://github.com/ismindirov" target="_blank"
							rel="noopener noreferrer"><i class="fab fa-github"></i></a>
					</div>
				</div>
				<!-- Р—РѕР±СЂР°Р¶РµРЅРЅСЏ РІ РіРѕР»РѕРІРЅРѕРјСѓ Р±Р»РѕС†С– -->
				<!-- <div class="img-holder">
					<picture>
						<source class="" srcset="assets/imgs/Ismsndirov.webp" type="image/webp">
						<img class="" src="assets/imgs/Ismsndirov.png" alt="Ismsndirov">
					</picture>
				</div> -->
			</div>
			<div class="widget">
				<a class="widget-item" href="#" data-goto="#skills" data-goto-top="100">
					<h2>1+</h2>
					<p>Years of Experience</p>
				</a>
				<a class="widget-item" href="#" data-goto="#projects" data-goto-top="100">
					<h2>5+</h2>
					<p>personal projects</p>
				</a>
				<a class="widget-item" href="#" data-goto="#certifications" data-goto-top="100">
					<h2>3</h2>
					<p>Major Certifications</p>
				</a>
			</div>
		</section>
		<!-- End of hero -->

		<!-- about -->
		<section class="section mt-3">
			<div class="container mt-5">
				<div class="row text-center text-md-left">
					<div id="about" class="col-md-3" data-watch="navigator" data-watch-threshold="0.2">
						<picture>
							<source class="img-thumbnail mb-4" srcset="assets/imgs/Ismsndirov.webp" type="image/webp">
							<img class="img-thumbnail mb-4" src="assets/imgs/Ismsndirov.png" alt="Ismsndirov">
						</picture>
					</div>
					<div class="pl-md-4 col-md-9">
						<h6 class="title">Ismindirov Vlad</h6>
						<p class="subtitle">DevOps Engineer</p>
						<!-- С‚РµРіРѕРј <strong> ...С‚СѓС‚ СЏРєРёР№СЃСЊ С‚РµРєСЃС‚...</strong> РІРёРґС–Р»РµРЅРѕ Р·РµР»РµРЅРёРј-->
						<p>A forward-thinking <strong>DevOps Engineer</strong> with a robust background in optimizing
							operation systems within agile frameworks. Specializing in the strategic deployment of technologies
							like
							<strong>Terraform</strong>, <strong>AWS</strong>, <strong>Kubernetes</strong>, and
							<strong>GitOps</strong> principles, I ensure scalable, efficient, and innovative IT
							infrastructures. My expertise extends to automating workflows, crafting <strong>CI/CD
								pipelines</strong>, and
							integrating GitOps for enhanced operational clarity and consistency.
						</p>
						<p>With a proven track record in <strong>team leadership</strong> and <strong>operational
								excellence</strong>, I am passionate about leveraging technology to surpass business objectives.
							Explore my site to see how my blend of creativity and technical acumen can elevate your project to
							new heights.</p>
						<a href="assets/Ismindirov_CV2.pdf" download="assets/Ismindirov_CV2.pdf"
							class="btn btn-primary rounded">DOWNLOAD
							CV</a>
					</div>
				</div>
			</div>
		</section>
		<!-- End of about -->

		<!-- skills -->
		<section class="section skills-section">
			<div class="container text-center">
				<h6 id="skills" class="subtitle" data-watch="navigator" data-watch-threshold="0.5">Skills</h6>
				<h6 class="section-title mb-4">Why Choose Me</h6>
				<p class="mb-5 pb-4">Here's why I'm a strong candidate for your projects and how I can contribute to your
					team and company.</p>
				<div class="row row-skills">
					<div class="col-lg-4 col-md-4 col-sm-4 wow fadeInUp skill-card" data-wow-delay="0.6s">
						<i class="fa fa-flag" aria-hidden="true"></i>
						<h3 class="skill-title">Transformational Leadership & DevOps Expertise</h3>
						<p class="skill-description">Expertise in <strong>leading DevOps</strong> transformations, with a
							proven track record in <strong>building and mentoring teams</strong>, providing training sessions,
							and
							enhancing operational efficiencies through best practices in agile environments.</p>
					</div>
					<div class="col-lg-4 col-md-4 col-sm-4 wow fadeInUp skill-card" data-wow-delay="0.9s">
						<i class="fa  fa-cloud" aria-hidden="true"></i>
						<h3 class="skill-title">Cloud Solution Architecture & Deployment</h3>
						<p class="skill-description">Architected and deployed <strong>scalable cloud solutions</strong> using
							<strong>AWS</strong>, <strong>Kubernetes</strong>, and <strong>Terraform</strong>, focusing on
							<strong>automating the platform lifecycle</strong>, from infrastructure deployment to routine
							maintenance, ensuring <strong>high availability</strong> and complex hybrid architecture
							integration.
						</p>
					</div>
					<div class="col-lg-4 col-md-4 col-sm-4 wow fadeInUp skill-card" data-wow-delay="1s">
						<i class="fa fa-rocket" aria-hidden="true"></i>
						<h3 class="skill-title">Advanced CI/CD Pipeline Development</h3>
						<p class="skill-description">Developed sophisticated CI/CD pipelines utilizing <strong>GitLab
								CI</strong>, <strong>Jenkins</strong>, and <strong>FluxCD</strong>, incorporating
							<strong>GitOps</strong> best practices and custom logic to cater to diverse deployment scenarios,
							significantly improving deployment reliability and efficiency.
						</p>
					</div>
					<div class="col-lg-4 col-md-4 col-sm-4 wow fadeInUp skill-card" data-wow-delay="1s">
						<i class="fa fa-search" aria-hidden="true"></i>
						<h3 class="skill-title">Monitoring & Logging Framework Implementation</h3>
						<p class="skill-description">Implemented comprehensive monitoring and logging frameworks using
							<strong>ELK</strong>, <strong>Datadog</strong>, <strong>Grafana</strong>, and
							<strong>Prometheus</strong>, automating system maintenance tasks, which led to improved system
							performance and reliability.
						</p>
					</div>
					<div class="col-lg-4 col-md-4 col-sm-4 wow fadeInUp skill-card" data-wow-delay="1s">
						<i class="fa fa-code" aria-hidden="true"></i>
						<h3 class="skill-title">Scripting & Automation with Data Services</h3>
						<p class="skill-description">Demonstrated proficiency in <strong>Python</strong> and
							<strong>Bash</strong> scripting for automation, contributing to significant improvements in system
							operations, including automation of infrastructure management and process testing. Proficient in
							integrating data services like <strong>Redis</strong>, <strong>MongoDB</strong>, and <strong>Apache
								Kafka</strong> for enhanced application performance and scalability.
						</p>
					</div>
					<div class="col-lg-4 col-md-4 col-sm-4 wow fadeInUp skill-card" data-wow-delay="1s">
						<i class="fa fa-certificate" aria-hidden="true"></i>
						<h3 class="skill-title">Certified Cloud Services & Infrastructure Expert</h3>
						<p class="skill-description">Hold <strong>AWS Certified Solutions Architect</strong>,
							<strong>Certified Kubernetes Administrator</strong>, and HashiCorp Certified: <strong>Terraform
								Associate</strong>
							certifications, evidencing advanced knowledge and skills in cloud services, container
							orchestration, and infrastructure as code.
						</p>
					</div>
				</div>
			</div>
		</section>
		<!-- End of skills -->

		<!-- My projects -->
		<section class="page__projects projects">
			<div class="projects__container">
				<h6 id="projects" class="section-title mb-4" data-watch="navigator" data-watch-threshold="0.5">My projects
				</h6>
				<p class="mb-5 pb-4">Here's why I'm a strong candidate for your projects and how I can contribute to your
					team and company.</p>
				<div data-spollers class="spollers">
					<div class="spollers__item spollers__item-padding">
						<!-- Comming soon.... -->
						<p class="mb-5 pb-4">Comming soon.... </p>
						<!-- Р РѕР·РґС–Р» Р· С„РѕС‚Рѕ РїСЂРѕРµРєС‚С–РІ -->
						<button type="button" data-spoller class="spollers__title btn btn-primary rounded">
							Show projects</button>
						<div class="spollers__body">
							<div class="projects__items">
								<article class="projects__item">
									<!-- РџРѕСЃРёР»Р°РЅРЅСЏ РЅР° РїСЂРѕРµРєС‚ -->
									<a href="https://github.com/ismindirov">
										<picture>
											<!-- РџРѕСЃРёР»Р°РЅРЅСЏ РЅР° Р·РѕР±СЂР°Р¶РµРЅРЅСЏ РІ РґРІРѕС… С„РѕСЂРјР°С‚Р°С…  .webp С‚Р° .png-->
											<source class="" srcset="assets/imgs/logo.webp" type="image/webp">
											<img class="" src="assets/imgs/logo.png" alt="logo">
										</picture>
									</a>
									<!-- РћРїРёСЃ РїСЂРѕРµРєС‚Сѓ РїСЂРё РЅР°РІРµРґРµРЅРЅС– -->
									<span>ProProjectProjectject</span>
								</article>
								<article class="projects__item">
									<a href="https://github.com/ismindirov">
										<picture>
											<source class="" srcset="assets/imgs/logo.webp" type="image/webp">
											<img class="" src="assets/imgs/logo.png" alt="logo">
										</picture>
									</a>
									<span>ProjectProject ProjectProjProjectect</span>
								</article>
								<article class="projects__item">
									<a href="https://github.com/ismindirov">
										<picture>
											<source class="" srcset="assets/imgs/logo.webp" type="image/webp">
											<img class="" src="assets/imgs/logo.png" alt="logo">
										</picture>
									</a>
									<span>Project</span>
								</article>
								<article class="projects__item">
									<a href="https://github.com/ismindirov">
										<picture>
											<source class="" srcset="assets/imgs/logo.webp" type="image/webp">
											<img class="" src="assets/imgs/logo.png" alt="logo">
										</picture>
									</a>
									<span>Project</span>
								</article>
								<article class="projects__item">
									<a href="https://github.com/ismindirov">
										<picture>
											<source class="" srcset="assets/imgs/logo.webp" type="image/webp">
											<img class="" src="assets/imgs/logo.png" alt="logo">
										</picture>
									</a>
									<span>Project</span>
								</article>
								<article class="projects__item">
									<a href="https://github.com/ismindirov">
										<picture>
											<source class="" srcset="assets/imgs/logo.webp" type="image/webp">
											<img class="" src="assets/imgs/logo.png" alt="logo">
										</picture>
									</a>
									<span>Project</span>
								</article>
								<article class="projects__item">
									<a href="https://github.com/ismindirov">
										<picture>
											<source class="" srcset="assets/imgs/logo.webp" type="image/webp">
											<img class="" src="assets/imgs/logo.png" alt="logo">
										</picture>
									</a>
									<span>Project</span>
								</article>
								<article class="projects__item">
									<a href="https://github.com/ismindirov">
										<picture>
											<source class="" srcset="assets/imgs/logo.webp" type="image/webp">
											<img class="" src="assets/imgs/logo.png" alt="logo">
										</picture>
									</a>
									<span>Project</span>
								</article>
							</div>
						</div>
					</div>
				</div>
			</div>
		</section>
		<!--End of My projects -->

		<!-- certifications -->
		<section class="section certifications">
			<div class="certifications__container">
				<div data-spollers class="spollers">
					<div class="spollers__item">
						<div class="spollers__body">
							<div class=" text-center">
								<h6 id="certifications" class="subtitle" data-watch="navigator" data-watch-threshold="0.3">
									Certifications
								</h6>
								<h6 class="section-title mb-4">My Professional Certifications</h6>
								<p class="mb-5 pb-4">Browse through my industry-recognized certifications that validate my
									expertise and skills in various technological domains.</p>
								<!-- Comming soon.... -->
								<p class="mb-5 pb-4">Comming soon.... </p>
								<button type="button" data-spoller class="spollers__title btn btn-primary rounded">
									Show certificates</button>
								<!-- Р РѕР·РґС–Р» Р· С„РѕС‚Рѕ СЃРµСЂС‚РёС„С–РєР°С‚С–РІ -->
								<div class="certification__items">
									<div class="certification__item">
										<picture>
											<source class="" srcset="assets/imgs/certificate-02.webp" type="image/webp">
											<img class="" src="assets/imgs/certificate-02.png" alt="certificate">
										</picture>
									</div>
									<div class="certification__item">
										<picture>
											<source class="" srcset="assets/imgs/certificate-02.webp" type="image/webp">
											<img class="" src="assets/imgs/certificate-02.png" alt="certificate">
										</picture>
									</div>
									<div class="certification__item">
										<picture>
											<source class="" srcset="assets/imgs/certificate-02.webp" type="image/webp">
											<img class="" src="assets/imgs/certificate-02.png" alt="certificate">
										</picture>
									</div>
									<div class="certification__item">
										<picture>
											<source class="" srcset="assets/imgs/certificate-02.webp" type="image/webp">
											<img class="" src="assets/imgs/certificate-02.png" alt="certificate">
										</picture>
									</div>
									<div class="certification__item">
										<picture>
											<source class="" srcset="assets/imgs/certificate-02.webp" type="image/webp">
											<img class="" src="assets/imgs/certificate-02.png" alt="certificate">
										</picture>
									</div>
									<div class="certification__item">
										<picture>
											<source class="" srcset="assets/imgs/certificate-02.webp" type="image/webp">
											<img class="" src="assets/imgs/certificate-02.png" alt="certificate">
										</picture>
									</div>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</section>
		<!-- End of certifications -->

		<!-- contact -->
		<section class="position-relative section">
			<div class="container text-center">
				<h2 id="contact" class="subtitle" data-watch="navigator" data-watch-threshold="0.2">Let's Collaborate</h2>
				<h2 class="section-title mb-4">Reach Out To Me</h2>
				<p class="contact-text">Looking to dive into DevOps? Need help with cloud setups? Or maybe you're close to a
					big idea?<br>I'm all ears and ready to help. Whether it's partnering up, asking questions, or just a good
					tech talk - I'm here for it.</p>
				<div class="contact-methods d-flex justify-content-center flex-wrap mb-4">
					<a href="mailto:ismindirov@gmail.com" class="btn btn-outline-dark btn-contact">
						<i class="fas fa-envelope mr-2"></i>ismindirov@gmail.com
					</a>
					<a href="https://www.linkedin.com/in/ismindirov/" target="_blank"
						class="btn btn-outline-dark btn-contact" rel="noopener noreferrer">
						<i class="fab fa-linkedin-in mr-2"></i>linkedin.com/in/ismindirov
					</a>
					<a href="https://github.com/ismindirov" target="_blank" class="btn btn-outline-dark btn-contact"
						rel="noopener noreferrer">
						<i class="fab fa-github mr-2"></i>github.com/ismindirov
					</a>
					<a href="https://t.me/DevOpsIsmindirov" target="_blank" class="btn btn-outline-dark btn-contact"
						rel="noopener noreferrer">
						<i class="fab fa-telegram-plane mr-2"></i>t.me/DevOpsIsmindirov
					</a>
				</div>
			</div>
		</section>
		<!-- End of contact -->

		<!-- Footer -->
		<footer class="page-footer" id="footer">
			<div class="container">
				<div class="row align-items-center justify-content-between">
					<div class="col-md-4">
						<p>Copyright
							<script>document.write(new Date().getFullYear())</script> &copy; <a
								href="https://www.linkedin.com/in/ismindirov/" target="_blank"
								rel="noopener noreferrer">Ismindirov Vlad</a>
						</p>
					</div>
					<div class="col-md-4 text-center">
						<div class="socials">
							<a class="social-item" href="mailto:ismindirov@gmail.com" target="_blank"
								rel="noopener noreferrer"><i class="fas fa-envelope"></i></a>
							<a class="social-item" href="https://www.linkedin.com/in/ismindirov/" target="_blank"
								rel="noopener noreferrer"><i class="fab fa-linkedin-in"></i></a>
							<a class="social-item" href="https://t.me/DevOpsIsmindirov" target="_blank"
								rel="noopener noreferrer"><i class="fab fa-telegram-plane"></i></a>
							<a class="social-item" href="https://github.com/ismindirov" target="_blank"
								rel="noopener noreferrer"><i class="fab fa-github"></i></a>
						</div>
					</div>
				</div>
			</div>
		</footer>
	</div>
	<!-- End of footer -->
	<script src="assets/vendors/jquery/jquery-3.4.1.js"></script>
	<script src="assets/vendors/bootstrap/bootstrap.bundle.js"></script>
	<script src="assets/js/app.js"></script>

</body>

</html>
