# HoK
 Honor of Kings -- Shanghaitech

https://jack0chan.github.io/HoK/



# 网页内嵌入视频的方法

推荐第一个方法

```html
<div style="position:relative; padding-bottom:56.25%; padding-top:30px; height:0; overflow:hidden;">
	<iframe  width="425" height="344" src="http://player.bilibili.com/player.html?aid=243831171&bvid=BV1Qv411i7js&cid=209328155&page=1" frameborder="0" allowfullscreen 
			style="position:absolute; top:0; left:0; width:100%; height:100%;">
	</iframe>
</div>



<iframe   src="http://player.bilibili.com/player.html?aid=243831171&bvid=BV1Qv411i7js&cid=209328155&page=1" width="425" height="344"   frameborder="1"  name="iframe名称"     scrolling="auto">   
</iframe>



<object width="425" height="344" data="http://player.bilibili.com/player.html?aid=243831171&bvid=BV1Qv411i7js&cid=209328155&page=1"></object>



<embed src="http://player.bilibili.com/player.html?aid=243831171&bvid=BV1Qv411i7js&cid=209328155&page=1" allowfullscreen="true" width="425" height="344">



<iframe  width="425" height="344" src="http://player.bilibili.com/player.html?aid=243831171&bvid=BV1Qv411i7js&cid=209328155&page=1" frameborder="0" allowfullscreen></iframe>
```

