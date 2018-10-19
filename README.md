# element-theme-chalk
> element component chalk theme.


## Installation
```shell
npm i element-theme-chalk -S
```

## Usage

Use Sass import
```css
@import 'element-theme-chalk';
```

Or Use webpack
```javascript
import 'element-theme-chalk';
```

Or
```html
<link rel="stylesheet" href="path/to/node_modules/element-theme-chalk/lib/index.css">
```

##  Import on demand
```javascript
import 'element-theme-chalk/lib/input.css';
import 'element-theme-chalk/lib/select.css';

// ...
```
## 设计思路
  * 先设计出来一套静态主题
  * 使用scss抽离，可复用
  * 与js操作无关，完全独立
  * 抽象出自定义主题
