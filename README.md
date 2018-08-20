# -
这是第一周做网站适配手机的代码改动说明
--------------------------------------------------
body {
	font-family: Arial， Helvetica， sans-serif;
	font-size: 12px;
	/*  cai_l */
	width:100%;
	min-width: 1250px;
}

.logo {
	 width: 400px;
	 float: left;
	 /* cai_l 
   缩小了padding左右边距，微调布局
	 */
	 padding-left: 50px;  
	 padding-right: 50px;    
	 /* cai_l */
	 padding-bottom: 10px;
}

.header {
	width:80%; 
	position: relative;
	margin: 0 auto;
	padding: 0px;
	height: 60px;
	/* cai_l 
  缩小了margin上的边距，微调布局
  */
	margin-top: 15px;
}
/*
  此外，删除掉了每个模块<head>里面的代码，如下
  
  <meta name="viewport" content="width=device-width,height=device-height,inital-scale=1.0,maximum-scale=1.0,user-               scalable=no;" />
  
  修改headers中的宽度为2000px固定宽度
*/
