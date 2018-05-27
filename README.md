<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en">
<head>
	<meta http-equiv="Content-Type" content="text/html;charset=UTF-8">
	<title>博雅首页</title>
	<style type="text/css">
		*{
			margin: 0;
			padding: 0;
		}
		.cl{
			clear: both;
		}
		body{
			font-size: 14px;
			font-family: "Microsoft YaHei","SimSun";
			height: 1500px;
		}
		.inner_c{
			width: 1000px;
			margin: 0 auto;
		}
		.header{
			height: 58px;
			background-color: #191D3A;

		}
		.header .logo{
			float: left;
			height: 58px;
		}
		.header .nav{
			float: left;
		}
		.header .nav ul{
			list-style: none;
		}
		.header .nav ul li{
			float: left;
			width: 100px;
			line-height: 58px;
			text-align: center;
			border-left: 1px solid #252947; 
		}
		.header .nav ul li.last{
			border-right: 1px solid #252947;
		}
		.header .nav ul li a{
			display: block;
			text-decoration: none;
			color:#818496;
			height: 58px;
		}
		.header .nav ul li a.current{
			background-color: #252947;
			color:white;
		}
		.header .nav ul li a:hover{
			background: #252947;
			color:white;
		}
		.header .jrwm_box{
			float: left;
			padding-left: 48px;
			padding-top: 12px;
		}
		.banner{
			height: 465px;
			background: url(images/banner.jpg) no-repeat center top;  
		}
		.content{
			padding-top: 50px;  }
		.content .product{	
			height: 228px;
			border-bottom: 1px solid #DBE1E7;
		}
		.content .product ul{
			list-style: none;
		}
		.content .product ul li{
			float: left;
			width: 218px;
			margin-right: 43px;
		}
		.content .product ul li.last{
			margin-right: 0px;
			width: 217px;
		}
		.content .product ul li img{
			width: 218px;
			height: 130px;
		}
		.content .product ul li h3{
			text-align: center;
			line-height: 38px;
			font-size: 15px;
			font-weight: bold;
		}
		.content .product ul li .djbf{
			text-align: center;
			line-height: 16px;
		}
		.content .product ul li .djbf a{
			font-size: 12px;
			color: #38B774;
			text-decoration: none;
			background: url(images/sanjiaoxing.png) no-repeat right ;
			padding-right: 16px; 

		}
	</style>
</head>
<body>
	<div class="header">
		<div class="inner_c">
			<h1 class="logo">
				<img src="images/logo.png" alt="" />
			</h1>
			<div class="nav">
				<ul>
					<li><a href="#" class="current">首页</a></li>
					<li><a href="#">博雅游戏</a></li>
					<li><a href="#">博雅新闻</a></li>
					<li><a href="#">关于我们</a></li>
					<li><a href="#">客服中心</a></li>
					<li class="last"><a href="#">投资者关系</a></li>
				</ul>
			</div>
			<div class="jrwm_box">
				<a href="#" class="jrwm">
					<img src="images/jrwm.png" alt="" />
				</a>
			</div>
		</div>
	</div>
	<div class="cl"></div>

	<div class="banner"></div>

	 <!-- 内容区域 -->
	<div class="content inner_c">
		<div class="product">
			<ul>
				<li>
					<p><img src="images/pro1.jpg" alt="" /></p>
					<h3>BPT宣传片</h3>
					<p class="djbf">
						<a href="#">点击播放</a>
					</p>
				</li>
				<li>
					<p><img src="images/pro2.jpg" alt="" /></p>
					<h3>BPT宣传片</h3>
					<p class="djbf">
						<a href="#">点击播放</a>
					</p>
				</li>
				<li>
					<p><img src="images/pro3.jpg" alt="" /></p>
					<h3>BPT宣传片</h3>
					<p class="djbf">
						<a href="#">点击播放</a>
					</p>
				</li>
				<li class="last">
					<p><img src="images/pro4.jpg" alt="" /></p>
					<h3>BPT宣传片</h3>
					<p class="djbf">
						<a href="#">点击播放</a>
					</p>
				</li>
			</ul>
		</div>
	</div>		
</body>
</html>
