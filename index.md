---
layout: page
title: wildchild's site
tagline: 十年磨一贱~
---
{% include JB/setup %}

<script type="text/javascript">
	window.onload = function(){ 
		var canvas = document.getElementById("myCanvas");
        var context = canvas.getContext("2d");
        var destX = 0;
        var destY = 0;
        var imageObj = new Image();	

		context.font  = 'Bold 30px Sans-Serif';
    	context.strokeText('Loading ...', 400, 150);
        
        imageObj.onload = function(){
        	context.clearRect ( 400 , 150 , 200 , 40 );
            context.drawImage(imageObj, destX, destY);            
    		context.font         = 'Italic 15px Sans-Serif';
    		var x = 20;
    		var y = 30;
            context.fillText("我是一位资历尚浅的程序员，在西安待过几年，现在在北京，未来在哪还不知道。", x, y);
            y += 20;
            context.fillText("使用Mac，且不能自拔，可以归为果粉，工作主要写iOS程序，有时会被迫写Flex。", x, y);
            y += 20;
            context.fillText("感兴趣的技术挺多（Cocoa，Python，Ruby，Rails，MacRuby），精通的少。", x, y);
            y += 20;
            context.fillText("感兴趣的运动挺多，都能玩玩，某人说我爱“动手动脚”... 足球应该是最爱。", x, y);
            y += 20;
            context.fillText("我会在这里分享一些我觉得有用的，有意思的东西。", x, y);
            context.fillStyle = "#FFFFFF";
            context.font         = 'Italic 9px Sans-Serif';
			context.fillText("From flickr.com/wbsloan", 830, 340);            
        };
        imageObj.src = "/img/index_bg.jpg";
	}
</script>

<canvas id="myCanvas" width="940" height="350">
</canvas>

[Douban](http://www.douban.com/people/wildchild_eric/)  [新浪微博](http://weibo.com/wildchild1001)  [Twitter](https://twitter.com/#!/wildchildEric)  [Github](https://github.com/wildchildEric)



