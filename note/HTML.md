# DOCTYPE
 * 是一种标准通用标记语言的文档类型声明，目的是告诉语言解析器要通过什么样的文档类型规范解析文档。
# WEB标准以及W3C标准
 * 结构、表现和行为分离、标签闭合、标签小写、不随意嵌套、使用外链css和js
# 严格模式和混杂模式
 * 严格模式的排版和JS运作模式是以该浏览器支持的最高标准运行
 * 混杂模式的页面以宽松的向后兼容的方式显示，模拟老式浏览器的行为以防止站点无法工作。
 * DOCTYPE不存在或格式不正确会导致混杂模式
# 标签语义化
 * 让页面的内容结构化，便于浏览器、搜索引擎解析
 * 在缺少css样式的情况下也可以以一种文档格式显示，并且容易阅读
 * 搜索引擎的爬虫依赖于标记来确定上下文和各个关键字的权重，利于SEO
 * 更容易将网站分块，便于维护理解
# 常用标签的默认样式
 * 块级元素
  + div,ol,ul,p,h1(系列),address,blockquote,form,dd,dl,dt,fieldset,frame,frameset,noframes,center,dir,hr,menu,pre {display:block};
 * 列表元素
  + li{display:list-item,list-style:disc}
  + ol{list-style-type:decimal}
  + ol ul,ul ol,ul ul,ol ol{margin-top:0;margin-bottom:0}
  + ol,ul{margin-left:40px}
 * 预格式文本
  + i,cite,em,var,address{font-style:italic}
  + big{font-size:1.17em}
  + small,sub,sup{font-size:.83em}
  + sub/sup{vertical-align:sub/super}
  + u,ins{text-decoration:underline}
 * 标题
  + h1{font-size:2em;margin:.67em 0}
  + h2{font-size:1.5em;margin:.75em 0}
  + h3{font-size:1.17em;margin:.83em 0}
  + h4,p,blockquote,ul,fieldset,form,ol,dl,dir,menu{margin:1.12em 0}
  + h5{font-size:.83em;margin:1.5em 0}
  + h6{font-size:.75em;margin:1.67em 0}
  + h1,h2,h3,h4,h5,h6,b,strong{font-weight:bolder}
 * 表格
  + table{display:table}
  + tr{display:table-row}
  + thead{display:table-header-group}
  + tbody{display:table-row-group}
  + tfoot{display:table-footer-group}
  + col{display:table-column}
 * 其他
  + head{display:none}
  + body{margin:8px;line-height:1.12em}
  + button,textarea,input,object,select{display:inline-block}
  + blockquote{margin-left:40px;margin-right:40px;}
  + pre,tt,code,kbd,samp{font-family:monospace}
  + pre{write-space:pre}
  + hr{border:1px inset}
  + center{text-align:center}
  + abbr,acronym{font-variant:small-caps;letter-spacing:0.1em}
# Meta标签作用及用法
    