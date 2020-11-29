
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>"
	<style type="text/css">
		p{
			color:red;
			margin:5px;
			cursor:pointer;
		}
		p:hover{
			background:yellow;
		}
		.zenbo{
			position: fixed;
			top: 0;
			left: 0;
			width: 100%;
			height: 100%
			z-index: 10;
			background: rgba(150,036,0,0.5);
			display: flex;
			justify-content: center;
			align-items: center;
		}
	</style>
</head>
<body>
	<p>貓咪介紹</p>
	<h1>萌軟奶貓</h1>
	<div class="cat">
		 <img src="https://cdn0.techbang.com/system/excerpt_images/60224/original/bf32199b457a11764b1a72b18259ff61.jpg?1533265554">
	</div>
                  <div class="fause">
                  <img src="https://img.tukuppt.com/png_preview/00/05/87/Vw6Lm2JX7Z.jpg!/fw/780" width="50" height="50" >
                  </div>

<script type="text/javascript"> 
$('p').click(function(){
$('.cat').slideToggle();
                                                         $('.fause').slideToggle();
                                                     
});
$('.fause').click(function(){
$('.fause').slideToggle();
                                                         $('.cat').slideToggle();
});
	</script>
	
</body>
</html>
