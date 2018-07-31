<<<<<<< HEAD
=======
<<<<<<< HEAD
>>>>>>> 2018.07.31
# QQ-TIM
QQ-TIM，视差滚动
=======
#《QQ TIM》
##1. 语义化标签的兼容
+ 使用html5 shiv.js插件,解决IE8及以下的浏览器对h5c3兼容性问题，需要在头部引入 
  ```html
    <!--[if lte IE 8]>
    <script src="js/html5shiv.min.js"></script>
    <![endif]-->
  ```
##2. seo搜索的优化
<<<<<<< HEAD
  ```html
     <h1>想要被搜索到的内容</h1>
  ```
 设置样式 
 ```css
=======
  ```html
     <h1>想要被搜索到的内容</h1>
  ```
 设置样式 
  ```css
>>>>>>> 2018.07.31
    font-size: 0;
    background: url("../images/sound-text.png") no-repeat center/cover;
    height: 300px;
  ```
##3.视差滚动效果
+ 视差滚动效果是在滚动的时候，内容和多层次的背景呈现出不同的速度或者不同的方向，有时候加上一些透明度、大小的动画优化显示。利用backgroung-attachment属性来实现的

+ stellar插件的使用
 - 引用文件
    ``` html
        <script src="js/jquery.min.js"></script>
        <script src="js/jquery.stellar.js"></script>
    ```
 - 结构
<<<<<<< HEAD
    ```html  
       <div class="content" id="content3" data-stellar-background-ratio="0.5">
           <p>TEXT HERE</p>
       </div>
    ```
  - 基本样式
    ````css 
=======
    ```html
      <div class="content" id="content3" data-stellar-background-ratio="0.5">
          <p>TEXT HERE</p>
      </div>
    ```
  - 基本样式
    ```css 
>>>>>>> 2018.07.31
    .content {
    background-attachment: fixed;
    height: 400px;
    }
    #content1 {
    background-image: url("..");
    }
<<<<<<< HEAD
    ````
  - js初始化
    ```javascript
    $.stellar({
       horizontalScrolling: false,
       responsive: true
    });
=======
    ```
  - js初始化
    ```javascript
        $.stellar({
            horizontalScrolling: false,
            responsive: true
        });
>>>>>>> 2018.07.31
    ```
+ 参数解释
  -  horizontalScrolling 和 verticalScrolling 该配置项用来设置视差效果的方向
  -  horizontalScrolling设置水平方向，verticalScro设置垂直方向， 为布尔值，默认为true 
  - responsive 该配置项用来制定load或者resize时间触发时是否刷新页面，其值为布尔值，默认为false
  - hideDistantElements 该配置项用来设置移出视线的元素是否隐藏，其值为布尔值，若不想隐藏则设置为false
  - data-stellar-ratio="2"  定义了此元素针对页面滚动的速度比率，比如，0.5为页面滚动的50%，2为页面滚动的200%，所以数值越大，你可以看到页面元素滚动速度越快
  - data-stellar-background-ratio  该配置项用在单个元素中，其值为一个正数，用来改变被设置元素的影响速度。 例如 值为0.3时，则表示背景的滚动速度为正常滚动速度的0.3倍。如果值为小数时最好在样式表中设置

<<<<<<< HEAD
=======
>>>>>>> 7.31
>>>>>>> 2018.07.31
