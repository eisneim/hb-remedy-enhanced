**Pellentesque habitant morbi tristique** senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. __Aenean ultricies mi vitae est.__ Mauris placerat eleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, `commodo vitae`, ornare sit amet, wisi. Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. [Donec non enim](#) in turpis pulvinar facilisis. Ut felis.

## Header Level 2


1. 这是一些中文这是一些中文这是一些中文这是一些中文, consectetuer adipiscing elit.</li>
2. Aliquam tincidunt mauris eu risus.</li>

> 这是一些中文, consectetur adipiscing elit. Vivamus magna. Cras in mi at felis aliquet congue. Ut a est eget ligula molestie gravida. Curabitur massa. Donec eleifend, libero at sagittis mollis, tellus est malesuada tellus, at luctus turpis elit sit amet quam. Vivamus pretium ornare est.

更多内容请查看百度百科对Unicode的介绍。
介绍完方案，再谈下使用。之前在看玉伯写的一篇文章《中文字体在 CSS 中的写法》 中提到：font-family中用到的宋体，“用 unicode 表示，不用 SimSun, 是因为 Firefox 的某些版本和 Opera 不支持 SimSun 的写法”。我在网上搜索了下相关内容，大多都是摘抄这篇文章，并没有提到具体哪个版本的Firefox和Opera会不支持英文的写法。

对比下，三种方法各有优缺点：中文形式的方便记忆，但在不支持中文的系统或者编码的页面则无法正常显示；英文形式的兼容了系统和编码的问题，但不方便记忆，又可能有潜在的风险；unicode码兼容行最好，但也存在记忆难的问题。

### 来点中文会怎么样？

* Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</li>
* Aliquam tincidunt mauris eu risus.</li>

```css
#header h1 a { 
  display: block; 
  width: 300px; 
  height: 80px; 
}
```

```javascript
function(this,data){
	var a = 'var';
	console.log('this is a function');
}
```

```markup
<h2>sdkjflds</h2>
<a href="#"></a>
```