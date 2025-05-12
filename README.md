<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>个人资料</title>
    <style>
        body {
            font-family: 'Microsoft YaHei', sans-serif;
            line-height: 1.6;
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
            color: #e0e0e0;
            background: linear-gradient(135deg, #1a1a1a 0%, #333333 100%);
            min-height: 100vh;
        }
        
        h1, h2 {
            color: #FAEBD7;
            text-shadow: 0 2px 4px rgba(0,0,0,0.3);
        }
        
        .python-outline h3 {
            color: #4fc3f7;
            border-bottom: 2px solid #4fc3f7;
            padding-bottom: 5px;
        }
        
        .card {
            background: rgba(40, 40, 40, 0.7);
            border-radius: 10px;
            padding: 25px;
            margin-bottom: 25px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
            backdrop-filter: blur(5px);
            border: 1px solid #444;
        }
        
        a {
            color: #4fc3f7;
            text-decoration: none;
        }
        
        a:hover {
            color: #81d4fa;
            text-decoration: underline;
        }
        
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #FAEBD7;
            box-shadow: 0 4px 10px rgba(255,51,51,0.3);
        }
    </style>
</head>
<body>
    <div class="card">
        <header>
            <a href="1.jpg" target="_blank">
                <img src="1.jpg" alt="照片" class="profile-img">
            </a>
            <h1>艾天宇</h1>
            <p>建筑工程学院 建筑学专业</p>
        </header>
    </div>

    <div class="card">
        <h2>自我介绍</h2>
        <p>我是大一智建2408艾天宇，这是我的python作业4</p>
    </div>

    <div class="card">
        <h2>联系方式</h2>
        <ul>
            <li>邮箱：2381228399@qq.com</li>
            <li>电话：13116819268</li>
        </ul>
    </div>

    <div class="card">
        <h2>爱好</h2>
        <ul>
            <li>睡觉</li>
		<li>看小说</li>
		<li>玩游戏</li>
		<li>旅游</li>
        </ul>
    </div>

    <div class="card">
        <h2>Python知识脑库（大纲版）</h2>
        <div class="python-outline" style="background-color: rgba(30,30,30,0.8); padding: 15px; border-radius: 5px;">
            <h3>1. Python基础</h3>
            <p>1.1 变量与数据类型<br>数值类型：int（整数）、float（浮点数）、complex（复数）。<br>字符串类型：用单引号（'）、双引号（"）或三引号（''' 或"""）表示，支持索引、切片等操作。</p>
            <p>1.2运算符<br>算术运算符,比较运算符,逻辑运算符,赋值运算符</p>
            <p>1.3控制流语句<br>条件语句：if、elif、else<br>循环语句:for,while,break,continue<p>
            <h3>2. 数据结构</h3>
            <p>2.1 列表（List）<br>增删改查、切片、列表推导式</p>
            <p>2.2 字典（Dict）<br>键值对操作、字典推导式</p>
            <p>2.3元组(Tuple)<br>适合存储一些不希望被修改的数据。
	    <p>2.4集合(Set)<br>无序、不重复的数据集合，用花括号 {} 或 set () 函数创建。
           <h3>三、函数</h3>
   	 <p>函数定义：def 函数名(参数):<br>参数传递：位置参数/默认参数/*args（可变位置参数）/**kwargs（可变关键字参数）<br>返回值：return 语句返回结果</p>

 	   <h3>四、模块与包</h3>
  	  <p>模块：包含Python代码的文件，用import导入（import/from...import）<br>包：包含多个模块的目录（需__init__.py文件）</p>

 	   <h3>五、面向对象编程（OOP）</h3>
  	  <p>类与对象：class定义类，obj=类名()创建对象<br>属性与方法：实例属性/类属性；实例方法/@classmethod/@staticmethod<br>继承：class 子类(父类):<br>多态：不同对象对同一方法的不同实现</p>

   	 <h3>六、异常处理</h3>
  	  <p>try-except：捕获处理异常（try:代码块 except 异常类型:处理）<br>finally：无论是否异常都会执行<br>raise：手动抛出异常</p>

 	   <h3>七、文件操作</h3>
   	 <p>打开文件：open('文件名', '模式')（r只读/w写入/a追加）<br>读写方法：read()/readline()/readlines()（读）；write()（写）<br>关闭文件：file.close() 或 with open(...) as file:（自动关闭）</p>
</div>

<div class="card">
		<h2>学习python的网站</h2>
		<p>https://www.runoob.com/python3/python3-tutorial.html<br>https://www.coursera.org/search?query=python<br>https://www.imooc.com/course/list?c=python等<p>
		<h2>建议</h2>
		<p>先掌握变量、数据类型、条件循环、函数等核心语法，再逐步深入。<br>通过实际项目（如计算器、文件操作）巩固知识，利用 LeetCode 等平台练习。<br>选择 VS Code 或 PyCharm，学会调试和使用 pip 安装库。<br>掌握类与对象的概念，为框架学习打基础。<br>通过错误信息定位问题，利用 Stack Overflow 解决疑难。<br>根据兴趣选择库（如 Pandas、Flask）深入学习。<br>从简单开源贡献或个人小项目（如博客、自动化脚本）入手。<br>加入社区（如 Python 中文社区），关注优质教程。<br>不死记语法，先实现功能再优化，不跳过基础直接学框架。<br>选择 Web 开发、数据分析、AI 等方向，针对性学习。<p>
</body>
</html># python-
