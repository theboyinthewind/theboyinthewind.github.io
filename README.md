# 王境泽Gif生成器JavaScript版  
页面地址: [purecucumber.top/wjz/](http://purecucumber.top/wjz/index.html)  
本项目Coding仓库: [coding.net/u/hhhhhg/p/wjzGif-JavaScript/git](https://coding.net/u/hhhhhg/p/wjzGif-JavaScript/git)  
  
本项目可以生成王境泽真香的gif  
更改文字内容后,请等上方图片至少播放一轮后,再点击生成图片按钮,以保证内容正确  
由于作者比较菜,js也不是啥好语言,所以有时会有生成的图片第一帧是全黑的情况(不知为啥)  
由于作者比较穷,所以页面加载会比较慢,不过缓存一次后啥都好说(  

用到了Vue.js,PIXI.js,gif.js.  
PIXI.js和gif.js都要求在服务器环境下运行,克隆或下载下来的话应该放到本地服务器上运行  
  
思路是在Canvas上绘制出动画后,将Canvas生成的图片逐帧添加到gif图片里.
