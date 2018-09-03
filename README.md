BackstopJS
1.安装
安装node.js，全局执行 npm install -g backstopjs
合适的文件夹下，执行 backstop init
2.测试
打开backstop.json，viewports是浏览器分辨率，scenarios下的url是测试的网址，referenceUrl是参考的网址，填写正确后执行 backstop  test
bitmaps_reference 文件夹下应保存设计图，命名需与backstop  test生成的名称一致，包括扩展名
bitmaps_reference 存入设计图后，设置分辨率、url，执行 backstop  test

