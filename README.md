# vue-memo

> DEMO在[这里](https://youknowznm.github.io/demos/vue_memo/)。

完全原创的基于 Vue.js 的记事本应用，实现了以下功能：
  - 通过`localStorage`实现数据的本地持久化
  - 增删、编辑笔记
  - 暂存未确认保存的笔记
  - 标记笔记的完成状态
  - 按`类别`、`标题`、`内容`或`时间戳`进行过滤
  - 按`创建时间`或`标题`排序
  - 对不同尺寸的桌面端和移动端响应适配
  - 支持`文本`和`涂鸦`两种记录方式
    * 文本编辑器支持`Markdown`格式
    * 涂鸦编辑器（来自我的[另一个项目](https://github.com/youknowznm/paint)）支持`选取颜色`、`撤销`、`重做`、`清除画布`    
```  
TODO：
  - 编辑笔记时的输入内容验证
  - 用Firebase代替本地存储
```

---

10月21日更新：
  - 改善了移动端编辑器的体验：在移动端限制主容器的高度并使溢出内容隐藏，避免编辑器里的`touch`事件造成视口滚动

---

![桌面端](https://github.com/youknowznm/youknowznm.github.io/blob/master/hehehe/desktop.png)

![移动端](https://github.com/youknowznm/youknowznm.github.io/blob/master/hehehe/mobile.png)


## 怎么用？

``` bash
npm install

npm run dev

在 8080 端口查看
```
