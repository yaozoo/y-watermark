<!--
 * @Author: 鲁遥
 * @Date: 2021-03-30 17:22:31
 * @LastEditTime: 2023-05-17 14:17:31
 * @LastEditors: luyao
 * @Description:
 * @FilePath: /y-watermark/README.md
-->

### 说明

```
此包仅供公司内部使用
```

### install

```
npm install watermark-dfs
```

### 使用

```

@description:
@param {*} displaytext 展示的水印文字  默认:location.hostname
@param {*} cansWidth 单位画布宽  默认:300
@param {*} cansHeight 单位画布高  默认:180
@param {*} cansRotate 旋转角度  默认:-15
@param {*} cansFont 文字fonsSize  默认:20
@param {*} cansfillBG 填充背景颜色  默认:rgba(200, 200, 200, 0.20
@param {*} cansfillTextAlign 文字对齐方式  默认:left
@param {*} uniqueId 唯一标识符号


Watermark.set({
    displayText: "dmm.doublefs.com", // 水印文案
    cansWidth: 300,
    cansHeight: 200,
    cansRotate: -15,
    cansFont: 20,
    cansfillBG: "rgba(0, 0, 0, 0.1)",
    cansfillTextAlign: "left",
    uniqueId:'98765432.8765432.765432'
});

Watermark.set();

```
