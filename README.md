<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
</head>	
	<style>
	
		html, body {
		  height: 100%;
		  padding: 0;
		  margin: 0;
		  background: #000;
		}
		img{
			display: block;
			margin: 0 auto;
		}
		label{
			
			display: block;
			margin: 0 auto;
			color: pink;
			font-size: 20px;
			padding-right: 5px;/*往左偏移10px*/
			animation:mymove 2.5s infinite;/* //关联动画名称、动画时长、循环 */
				/*Safari 和 Chrome:*/
				-webkit-animation:mymove 2.5s infinite;/* //同上（兼容） */
		}
		@keyframes mymove
			{
			50% {font-size: 40px;}/* //名字放大大小 */
		}
		
		/*Safari 和 Chrome:*/
		@-webkit-keyframes mymove
		{
			50% {font-size: 40px;}/* //名字放大大小 */
		}
		.middle{
			width: 100%;
			height: 100vh;
			display: flex;
			align-items: center;
		}
		.middle2{
			position: absolute;
			z-index: 2;
			width: 100%;
			height: 100%;
            margin: auto;
			
			display: flex;align-items: center;
		}
	</style>
<link rel="stylesheet" href="./style.css">
<body>
    <div class="container">
        <span>浪</span>
        <span>漫</span>
        <span>的</span>
        <span>爱</span>
        <span>心</span>
 
    </div>
		<div class="middle">
			<div class="middle2">	
			</div>
			
			<img src="http://m.qpic.cn/psc?/V51XGviq2qTo840d7Oau3BVaMk2VbjSq/bqQfVz5yrrGYSXMvKr.cqZo0bn0S6oehxpHDf4OJi8vi1lFrEFRMV2jQ76Pmc7cDQinpkzWtZInLfrQfLC.Uz1zJVQNfcmY5xSaKs92d49M!/b&bo=LAGmAAAAAAACB6g!&rf=viewer_4"width="854" height="480"/>
		</div>
		
  </body>
    <audio 
    autoplay="autoplay" 
    loop="loop" 
    preload="auto"
    src="http://ws.stream.qqmusic.qq.com/C4000009nowb1Lxsk5.m4a?guid=291747946&vkey=927E1CB036619BB457EC5C1E98E58C4646FD00050805BB0984A5BFCA3496DCEB4584A8A036F397667725E74D8AC498ED6108144422F6FC6F&uin=&fromtag=120032">
    </audio>
<script type="text/javascript" src="//js.users.51.la/21504121.js"></script>		
	</body>
</html>
