# vue-dialog

> vue弹出窗口组件

## Build Setup

``` bash
# 依赖velocity.js
# 直接用 <script> 标签引入
<script src="drag.js"></script>

# 模块化引入
import drag from 'drag.js'

Vue.use(drag)

<div v-drag></div>

# 支持指定区域拖拽：可拖拽元素定义data-drag
<div v-drag>
  <h data-drag='drag'>title</h>
  <p>content</p>
</div>
```

## 预览

<a href="https://zhazhjie.github.io/vue-components-demo/">Demo</a>
