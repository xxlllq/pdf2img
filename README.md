# :diamond_shape_with_a_dot_inside:pdf2img
使用JS将PDF文档转换为图片，并支持下载图片（.zip格式全部下载）

* 在线[Demo](https://xxlllq.github.io/pdf2img)
<kbd>
  <div style="border: 1px solid gainsboro;border-radius: 5px;" align="center">
    <img width="80%" height="auto" src="https://raw.githubusercontent.com/xxlllq/pdf2img/master/img/pdf2img.gif" alt="PDF To Image" title="PDF To Image"/>
  </div>
</kbd>

* 页面样式模板[来源](https://codepen.io/roydigerhund/pen/OMreoV)

* 操作步骤(选择文件-->文档上传完成-->导出图片)

* 文档大小建议不超过10M，因为文件越大处理过程越慢。可通过修改index.html中的【if(mb > 10)】改变文件大小限制。

* 项目中使用了[pdf.js](http://mozilla.github.io/pdf.js/)、[FileSaver.js](https://github.com/eligrey/FileSaver.js/)

* 浏览器（建议Chrome）

|Chrome  |  Firefox |  Safari |  IE|
|:------:|:------:|:------:|:------:|
![](https://raw.githubusercontent.com/xxlllq/pdf2img/master/img/chrome.png)  |  ![](https://raw.githubusercontent.com/xxlllq/pdf2img/master/img/firefox.png)|  ![](https://raw.githubusercontent.com/xxlllq/pdf2img/master/img/safari.png)|  ![](https://raw.githubusercontent.com/xxlllq/pdf2img/master/img/ie.png)
|latest|latest|latest|10+|　　
 
* PDF JS版本2.8.335浏览器支持

由于pdfjs版本2.8.335中js引入了可选链操作符【?.，??】等，请访问参考下图查看自己的浏览器是否支持。
<kbd>
  <div style="border: 1px solid gainsboro;border-radius: 5px;" align="center">
    <img width="80%" height="auto" src="https://raw.githubusercontent.com/xxlllq/pdf2img/master/img/version-2.8.335-support.png" alt="PDF To Image" title="PDF To Image"/>
  </div>
</kbd>