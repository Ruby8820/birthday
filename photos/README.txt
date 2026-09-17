把生日照片放到这个文件夹里，例如：

  public/photos/01.jpg
  public/photos/02.jpg
  ...

然后在 src/content.js 里把对应照片的 img 改成 "./photos/01.jpg" 即可。
（注意：路径必须以 ./ 开头，这样双击 dist/index.html 时照片才能正常显示。）

本文件夹内的图片会被原样复制到打包产物 dist/photos/ 下，
发送给朋友时请把整个 dist 文件夹一起打包。
