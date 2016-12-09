## 省级联动插件使用说明
1、首先插件时基于jquery上扩展的插件，使用的时候要先引入jquery文件
2、省级联动的设计原理：
![](https://raw.githubusercontent.com/Believel/MarkdownPhotos/master/imgs/%E7%9C%81%E7%BA%A7%E8%81%94%E5%8A%A8%E5%8E%9F%E7%90%86.png)
3、引入jquery.region.js包
4、html代码
```bash
 <div class="hometown">
 		<select name="" id="province" data-id=""></select>
 		<select name="" id="city" data-id=""></select>
 		<select name="" id="xian" data-id=""></select>
 	</div>
```
5、js代码
```js
$('.hometown').region({
// 如果是从服务器获得数据，会有一个链接的地址，这里我是把后台的数据导入了出来放在文件的region.json里面，
// 方便大家测试使用
			url: './region.json'
		});
```
6、效果图展示如下：
![](https://raw.githubusercontent.com/Believel/MarkdownPhotos/master/imgs/region-result.png)
