# naukrisahihai.com
<!DOCTYPE html>
<html>
<head>
<div id="banner3">
    <link rel="stylesheet" type="text/css" href="styles3.css">
	<button id="shareBtn">Use Tools free and Share with Friends</button>
</div>
    <link rel="stylesheet" type="text/css" href="styles.css">
	<title>NaukriSahiHai.Com</title>
</head>
<body>
<header>
	<h1>NaukriSahiHai.Com</h1>
</header>
<div>
	<h2>Welcome to NaukriSahiHai.Com - Your one-stop destination for job and placement services.</h2>
	<br>
	<br>
	<button class="btn"> <a href="imagetopdf.html">Image to PDF</a></button>
	<button class="btn"> <a href="20KB.html">Compress Less Than 20 KB</a></button>
	<button class="btn"> <a href="50KB.html">Compress Less Than 50 KB</a></button>
	<button class="btn"> <a href="100KB.html">Compress Less Than 100 KB</a></button>
	<br>
	<br>
	<p>We offer a wide range of job and placement services to help you find the right job for you. Our services include image to pdf conversion, image compression, and much more. With our user-friendly interface and powerful tools, you can easily search and apply for jobs, create and manage your resume, and stay informed about the latest job openings and trends in your field. Whether you're a fresh graduate or an experienced professional, we're here to help you take the next step in your career.

</p>
</div>
<head>
<div id="banner3">
    <link rel="stylesheet" type="text/css" href="styles3.css"> 	
    <button id="shareBtn">Use Tools free and Share with Friends</button>
</div>
</head>
<footer>
	Copyright @ NaukriSahiHai.Com
</footer>
<script>
	var shareBtn = document.getElementById("shareBtn");
	shareBtn.addEventListener("click", function() {
	    if (navigator.share) {
	        navigator.share({
	            title: 'NaukriSahiHai.Com',
	            text: 'Use Tools free and Share with Friends',
	            url:'https://naukrisahiha.com',
})
.then(() => console.log('Successful share'))
.catch((error) => console.log('Error sharing:', error));
} else {
console.log("Your browser doesn't support sharing feature.")
}
});
</script>

</body>
</html>

