# vue-dialog

> vue弹出窗口组件

## Build Setup

``` bash
# submit监听确定事件，width,height窗口初始大小，showWin显示隐藏窗口

import dialogEl from 'dialog'

<dialog-el :showWin.sync='show' @submit='submit' width='500' height='300'>
  <div slot='title'>标题</div>
  <div slot='content'>按住头部可拖拽、右下角放大缩小、可最大化</div>
</dialog-el>
```
## 预览

[DEMO](https://zhazhjie.github.io/vue-dialog/?id=dialog)

组件移至fly-ui项目，<a href="https://zhazhjie.github.io/fly-ui">戳这里</a>
