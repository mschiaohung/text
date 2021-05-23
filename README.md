# text

<!DOCTYPE html>
<html>
<head>
	<title>at this park</title>
		<link	href="css/bootstrap.min.css"	rel="stylesheet">


	<style>
		.c1{
			color: blue;
		}

		.c2{
			color: pink;
		}
		a{
			color: #80ff00;
			font-size: 180%;
			font-weight: bold;
			text-decoration: none;
		}

		h2{
			margin: 10px 0px 0px;
		}

		.place{
			background: lightblue;
		}

		.lucy{
			background: pink;
		}

		div{
			width: 200px;
			border: 1px red solid;
			margin: 10px;
			border: none;
		}

	</style>

	<script language="javascript">
		function changeh1(){
			document.getElementById("myh1").className="c2";
		}

		score=prompt("請輸入成績");
		
		if(score<60){
			alert("不及格");
		} else{
			alert("及格");
		}

		function showDate(){
			document.getElementById('js2').innerHTML=Date();
		}
		window.onload=function(){
			var btn1 =document.getElementById("btn1");
			btn1.onclick=function(){
				document.getElementById('js3').innerHTML=Date();
			}
		}


	</script>
</head>
<body>

	<h1 id="myh1" class="c1" onclick="changeh1()">click me to change color</h1>
	<a href="https://www.104.com.tw/jobs/main/student" >104</a>



	<ul>
		
		<li>Because is you.</li>
	</ul>

	<section class="place">
		<h2 style="color: gray">寶島水果</h2>
		<p>這會兒你看，春天來了，春天的桃李舞著春風；夏天前的鮮黃鳳梨酸溜酸溜帶著濃郁的香氣，可以打果汁也可以切塊吃；接下來是閃著黃金光芒，澄黃的芒果就鮮艷欲滴的登場了。艷紅的西瓜，<strong>那種嬌艷欲滴的色彩把夏天變溫柔了</strong>，冰冰涼涼的、沙沙的，比冰淇淋還香、比冰沙還爽口。熱得要死的時候，正是甜得要命的荔枝龍眼上場，又香又甜，像是賞味用的珍珠，簡直讓人甜上了天。台灣的水果──不由得讓人大叫： 我愛你。</p>

		<img src="img/purple.jpg"height="200px">
	</section>

	<section class="lucy">
		<h2>果醬</h2>
		<strong>留住水果的美味  封存停格的絢麗</strong>，這些又「水」又好吃的水果，除了新鮮現吃，有一個讓時間停格、讓美麗凝結的方法──做果醬。
		<img src="img/str.jpg"height="200px">
	</section>

	<textarea name="textarea" rows="10" cols="50">請在此輸入訊息</textarea>

	<form>
		<input type="text" placeholder="帳號" name="user"><br>

		<input type="password" placeholder="密碼" name="password"><br>

		<input type="button" value="login">
	</form>

	<div>
		<button type="button" onclick="alert('Hello')">Hello</button>
	</div>

	
	<div>
		<p id="js2">按下按鈕在此顯示時間</p>
		<button type="button" onclick="showDate()">點選顯示時間</button>
	</div>
</body>
</html>
