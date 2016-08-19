#good-material-for-learning-CS
##This is a collection for code-learning. 
Just wanna share some `useful material` with you guys!! </br>
[![cat](https://github.com/EmilyKeer/good-material-for-learning-CS/raw/master/github_icon.jpg)] (http://pan.baidu.com/s/1eSPr6L0 "open")
[Have a look at here] (http://pan.baidu.com/s/1eSPr6L0 "open") 

Including material for: :blush:, </br>
> * MySQL</br>
>> * Windows OS</br>
* Javascript</br>
* Html+CSS</br>
* Java</br>
* More...

* Example(for models):
```javascript
<HTML>
<HEAD>
<TITLE>时间日期篇--显示时钟</TITLE>
</HEAD>

<BODY bgcolor="#fef4d2" onload=showclock() background="../images/background2.jpg">
<br/>


 <h2 style="color:#FF00FF;text-align:center" ><b>时间日期篇--显示时钟</b></h2>

  <hr width=300> <!--分割线-->
<br/>


<!-- [Step1]: 这里可以调整时钟的方位 -->
<span id=liveclock style="position:relative; left:300px;top:122px; width: 300px; height: 25px">
</span>   
<SCRIPT type="text/javascript">

function showclock() 
{if(!document.layers&&!document.all)
return //如果不是IE所有元素集合/Netscape所有元素集合，那就返回吧

var Digital=new Date() //Mon Aug 15 2016 11:57:47 GMT+0800 (中国标准时间)
var hours=Digital.getHours()   //得到字符串
var minutes=Digital.getMinutes()
var seconds=Digital.getSeconds()
var dn="AM"
if(hours>12)
{dn="PM"
hours=hours-12
}
if(hours==0) hours=12
if(minutes<=9) minutes="0"+minutes
if(seconds<=9) seconds="0"+seconds
<!-- [Step2]:这里可以改变时钟的大小 -->
myclock='<p style="font-size:50px; font-family:verdana; color:green; ">'+hours+":"+minutes+":" //内联样式表：‘ “ 要区分；注意格式
+seconds+"&nbsp"+dn+"</p>"
if(document.layers)
{document.layers.liveclock.document.write(myclock)
document.layers.liveclock.document.close()
}
else if(document.all)
liveclock.innerHTML=myclock

setTimeout("showclock()",1000)
}
</SCRIPT>



</BODY>

</HTML>
```
