AutoTest --- 基于MFC的批量TCP接口测试应用
======================================
### 安装
直接[下载](Release/AutoTest.exe)目录Release/AutoTest.exe，双击执行即可。

### 使用介绍
1. ip和port按照实际的情况填写；
2. 点击“加载配置”，会弹出选择文件框（txt和dat后缀的文件），文件ansi编码；
	2.1. 加载的文件格式：#开头的表示注释，不会作为测试数据发送，其他的一条数据一行
3. 双击列表中的某一条会把其中的内容发送到指定端口并弹出返回值；
4. 点击“开始”会把加载的内容全部发送到指定端口并接受返回值；

### 编译
推荐使用visual studio community 2015版，这个是微软的免费版，不需要购买。<br />
直接F7编译即可。
