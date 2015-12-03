<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8" />
<title>loader test</title>
<link rel="stylesheet" href="reset.css" />
<style>
* {
	-webkit-box-sizing: border-box;
	   -moz-box-sizing: border-box;
         -o-box-sizing: border-box;
        -ms-box-sizing: border-box;
            box-sizing: border-box;
}

html, body {
	overflow: hidden;
	height: 0%;
}

#loader {
	width: 82px;
	height: 82px;
	position: absolute;
	top: 50%;
	left: 50%;
}

</style>
</head>

<body>
	<div id="loader">
		<img src="gif-load.gif" />
	</div>
	<div class="wrapper">
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
		<p>this is a paragraph</p><br>
	</div>
	

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script>
	$(function() {
		$("#loader").fadeOut(800);

		setTimeout(function() {
			var show = function show() {
				$("html body").css("overflow", "auto");
			}
			$("html").css("height", "100%");
			$("body").animate({height: "100%"}, 1000, show);
		}, 300);
	});
</script>
</body>
</html>
