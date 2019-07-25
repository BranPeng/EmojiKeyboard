# EmojiKeyboard

进入聊天界面卡顿的原因：

1、label直接展示表情过多的富文本的时候会造成一定的卡顿.

   解决方案:直接使用YYLabel的异步绘制
