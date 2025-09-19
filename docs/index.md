
#
<html>
	<head>
		<meta charset="UTF-8">
		<title>css add shadow</title>
		<style>
			.demo{
				width: 400px;
				margin: 50px auto;
				text-align: center; /* 添加这行来让内容居中 */
			}
			.demo img{
				-webkit-filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5)); /*考虑浏览器兼容性：兼容 Chrome, Safari, Opera */
                filter: drop-shadow(10px 10px 10px rgba(0,0,0,.5));
				display: block; /* 添加这行让图片独占一行 */
				margin: 0 auto; /* 确保图片也居中 */
			}
			.demo p {
				margin-top: 20px; /* 在图片和文字之间添加一些间距 */
				font-size: 16px; /* 设置文字大小 */
			}
		</style>
	</head>
	<body>
		<div class="demo">
			<img src="https://plus.unsplash.com/premium_photo-1712685912275-943ff90aac7c?q=80&w=3020&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" width = "400" alt="Mountain" />
			<br>
            <p>Qihang On Vocals Here.</p>
		</div>
	</body>
</html>

