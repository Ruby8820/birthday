把背景音乐文件放到这个文件夹里，例如：

  public/music/birthday.mp3

然后在 src/content.js 的 music.src 里改成 "./music/birthday.mp3"。

说明：
- 支持 mp3 / m4a / ogg 等常见格式。
- 音乐会在用户第一次点击页面时自动响起（浏览器禁止无交互自动播放）。
- 右上角有悬浮按钮，可随时暂停 / 继续。
- 本文件夹内的音乐文件会被复制到打包产物 dist/music/ 下，
  发送给朋友时请把整个 dist 文件夹一起打包。
