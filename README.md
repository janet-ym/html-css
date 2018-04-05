# html-css
Review notes about html/css

<h1>As html:</h1>
  <h2>2. html template</h2>
  <img src="img/html-template.jpg" alt="">

  <h2>3. Document type</h2>
	<h3><!DOCTYPE>声明帮助浏览器正确地显示网页。</h3>
	<!DOCTYPE>不是html标签，它为浏览器提供一项信息声明，即html是用什么版本编写的。

	HTML5:
		<!DOCTYPE html>


	HTML 4.01 Strict(该DTD包含所有html元素和属性,但 不包括展示性的和弃用的元素,不允许框架集):
		<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">


	HTML 4.01 Transitional(该DTD包含所有html元素和属性,包括展示性的和弃用的元素,不允许框架集):
		<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">


	HTML 4.01 Frameset(该DTD等同于HTML 4.01 Transitional,但允许框架集内容):
		<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">


	XHTML 1.0 Strict(该DTD包含所有HTML元素和属性,但不包括展示性和弃用的元素,不允许框架集,必须以格式正确的XML来编写标记):
		<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd"> 
    
    
  <h2>4. Metadata analysis</h2>
    <p>1. charset="UTF-8"  表示字符编码的meta一定要放在第一个</p>
	  <p>2. name="renderder" content="webkit"  指定双核浏览器默认以何种方式渲染页面  </p>
	  <p>3. name="viewport" content="width=device-width, initial-scale=1.0"  </p>
	  <p>      浏览器窗口内容区大小         浏览器窗口内容区大小     初始缩放比例    </p>
    <p>4. http-equiv="X-UA-Compatible" content="ie=edge,chrome=1"   表示在IE8优先使用最新版的IE和Chrome  </p>
    <p>5. name="format-detection" content="telephone=no"   取消移动电话标识   </p>
    <h3> SEO优化 </h3>
    <p> name="keywords" content="关键字   关键字" </p>
    <p> name="description" content="描述   描述" </p>
    <p> name="author" content="作者信息" </p>
  


  <h2>5. Metadata analysis</h2>
