# czrsortable
多区域拖放图片（支持前端压缩）

# 使用办法
●在需要使用的czrsortable的页面引入js及所需的依赖js文件，css文件未引入时将自动加载

● 调用办法：<br>
$.dragimg('idName');

● 获取数据办法：<br>
$.getdragimg('idName');//获取指定区域的数据<br>
$.getdragimg('idName','src');//获取指定区域指定数据且只返回src一维数组

# 可选参数
●	density: 'lrz',//使用lrz压缩服务，默认无压缩[设置不存在的压缩服务时默认无压缩]<br>
●	url: true,//开启url服务[默认关闭false]<br>
●	urlTitle： ‘请输入跳转链接’,//url输入框标题[默认无标题false]<br>
●	css: '',//自定义css路径<br>
●	width: 900,//设置图片宽度,默认原大小[无压缩不支持设置宽度][只需宽度数字，无需加px等字眼]<br>
●	height: 900,//设置图片高度,默认原大小[无压缩不支持设置高度][只需高度数字，无需加px等字眼]<br>
●	maxcount: 8,//限制图片数量,默认无限制<br>
●	maxerror: '最多只能添加{count}张图片哦',//当图片超出时提示（自定义）<br>
●	sorcreate: {},//支持配置Sortable自带参数，参数请阅读Sortable
