# EnoughIsEnough
<!DOCTYPE html>
<html lang="en">
	<head>
		<title>Enough Is Enough!</title>
		<meta name="description" content="">
		<meta name="keywors" content="this is where SEO keywords go for search engine optimization">
		<meta name ="author" content="">
		 <meta charset="utf-8">
    		<meta http-equiv="X-UA-Compatible" content="IE=edge">
    		<meta name="viewport" content="width=device-width, initial-scale=1">
		<link href = "index.css" rel ="stylesheet" type ="text/css" />
		
		<style>
		/*resets all margins and things*/
		*{
			box-sizing: border-box;
		}
		
		body{
			margin:0;
			font-family: 'Segoe UI', Tahoma, Geneva, Verdana,
			sans-serif;
			font-size:1rem;
			line-height: 1.5;
			color: #333;
			overflow-x: hidden;  /*hides horizontal scroll bar*/
		}
		
		.v-header{
			height: 100vh;
			display: flex;
			align-items: center;
			color: #fff;
		}
		
		.container{
			max-width: 960px;
			padding-left: 1rem;
			padding-right: 1rem;
			margin: auto;
			text-align: center;
		}
		
		.fullscreen-video-wrap{
			position:absolute;
			top: 0;
			left: 0;
			width: 100%;
			height: 100vh;
			overflow: hidden;
		}
		
		.fullscreen-video-wrap video{
			min-width: 100%;
			min-height: 100%;
		}
		
		.header-overlay{
			height: 100vh;
			width: 100vw;
			position: absolute;
			top: 0;
			left: 0;
			background: #ff6700;
			z-index: 1;  /*makes sure blue cover is always over the video*/
			opacity: 0.85;
		}
		
		
		.header-content{
			z-index: 2;  /*brings the words closer to the surface so you can see them better*/
			margin: auto;
		}
		
		.header-content h1{
			fpnt-size: 50px;
			margin-bottom: 0;
		}
		
		.header-content p{
			font-size: 1.5rem;
			display: block;
			padding-bottom: 2rem;
		}
		
		.btn{
			background: #34b3a0;
			color: #fff;
			font-size: 1.2rem;
			padding: 1rem 2rem;
			text-decoration: none;
		}
		
		.section{
			padding: 20px 0;
		}
		
		.section-b{
			background: #ff6700 ;
			color: #fff;
		}
		
		@media(max-width: 960px){
		.container
			padding-right: 3rem;
			padding-left: 3rem;
		}
	}
		</style>
	</head>
	<body>
		<header class = "v-header container">
		<div class = "fullscreen-video-wrap">
			<a href="http://www.freeimagehosting.net/commercial-photography/"><img src="https://i.imgur.com/1xgwVCF.jpg" alt="Commercial Photography"></a>">
		</div>
		<div class="header-overlay"></div>
		<div class="header-content">
		<h1>Enough Is Enough!</h1>
		<h2>Public Safety Envelopes</h2>
		<p>Craig Johnson seen here in orange is a 30 plus year veteran reserve police officer and the creater of the public safety envelope</p>
		<a href="#section section-a" class="btn">Read More</a>
		</div>
		</header>
		
		<section id="section section-a"> </section>
		
		<section class="section section-a">
			<div class="container"
			<h1>SECTION A UNDER CONSTRUCTION! VIDEO BACKGROUND AND CONTENT COMING SOON!</h1>
			<p>
			"There is no one who loves pain itself, who seeks after it and wants to have it, simply because it is pain..."

			What is Lorem Ipsum?
			Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
			</p>
			</div>
		</section>
		
		<section class="section section-b">
			<div class="container"
			<h1>Section B</h1>
			<p>
			"There is no one who loves pain itself, who seeks after it and wants to have it, simply because it is pain..."

			What is Lorem Ipsum?
			Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
			</p>
			</div>
		</section>

	</body>	
</html>
