# starks
<script type="text/javascript">
function doZoom(size)
{document.getElementById('zoom').style.fontSize=size+'px';}
</script>
<span id="zoom">需要指定大小的文字</span>
<a href="javascript:doZoom(16)">大</a> <a href="javascript:doZoom(14)">中</a> <a
href="javascript:doZoom(12)">小</a>
<select name="select" onchange="window.open(this.options[this.selectedIndex].value)">
<option value="http://www.microsoft.com/ie"> Internet Explorer</option>
<option value="http://www.microsoft.com"> Microsoft Home</option>
<option value="http://msdn.microsoft.com"> Developer Network</option>
</select>


<a href=# onclick="this.style.behavior='url(#default#homepage)';this.setHomePage

('xxx.com');">设为首页</a>

<a href="javascript:window.external.AddFavorite('xxxx.com','好度云

盟')">收藏本站</a>
<Script Language="JavaScript"> 

　　 var timedate= new Date("October 1,2002"); 

　　 var times= "国庆节"; 

　　 var now = new Date(); 

　　 var date = timedate.getTime() - now.getTime(); 

　　 var time = Math.floor(date / (1000 * 60 * 60 * 24)); 

　　 if (time >= 0) 

　　 document.write( "现在离"+times+"还有: "+time +"天")

</Script>

