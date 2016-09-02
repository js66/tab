# tab
网页组件常用切换tab效果

#step1
~~~
    <script src="js/jquery-1.4.2.min.js"></script>
		<script src="js/jquery.tab.1.0.js"></script>
~~~
# step2
~~~
<div class="tab">
								<div class="tab_title">title1</div>
								<div class="tab_title">title2</div>
								<div class="tab_title">title3</div>
								<div class="tab_con">tabcontent1</div>
								<div class="tab_con">tabcontent2</div>
								<div class="tab_con">tabcontent3</div>
						
</div>
~~~

# step3

~~~
$(".tab").tab();
~~~

# Advance  更多

###参数说明
~~~
{
					"effect":"toggle" ,  		//effect 效果    toggle  | fade |  slide
					"default":0,				//默认显示第几个
					"titleName":".tab_title", 	// 控制器名称  .tab_title
					"contentName":".tab_con",	 // 内容名称  .tab_con
					"speed":"normal"			// 动画的速度   "normal" | "fast" |"slow" | 毫秒
	}
~~~

### 例子

~~~
$(".tab").tab({
"effect":"slide",
"default":2,
"titleName":".tab_title",
"contentName":".tab_con",
"speed":"fast"
});
~~~



