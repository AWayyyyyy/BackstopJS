BackstopJS

1.安装

安装node.js，全局执行 npm install -g backstopjs
合适的文件夹下，执行 backstop init

2.测试

打开backstop.json，viewports是浏览器分辨率，scenarios下的url是测试的网址，referenceUrl是参考的网址，填写正确后执行 backstop  test
bitmaps_reference 文件夹下应保存设计图，命名需与backstop  test生成的名称一致，包括扩展名
bitmaps_reference 存入设计图后，设置分辨率、url，执行 backstop  test

注意：

1.设计图必须是png，需转换只改扩展名无效
2.设置的网页高宽需与设计图尺寸一致
3.需要登录的页面需要导入cookie
4.工具默认是用chromium截图，测试其他浏览器样式，可以将其他浏览器页面截图作为参考图片，与chromium的截图对比

其他具体用法：https://github.com/jiamingjn/BackstopJS

