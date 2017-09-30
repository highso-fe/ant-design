<p align="center">
  <a href="http://ant.design">
    <img width="320" src="https://t.alipayobjects.com/images/rmsweb/T1B9hfXcdvXXXXXXXX.svg">
  </a>
</p>

hx-ant-design
===

Forked from [ant-design](https://github.com/ant-design/ant-design)

## Changes

* 删除了全局样式对 `normalize.css v7.0.0` 的引用
* 删除了 Ant 的部分自定制 CSS 重置操作
    * [Set a font specifically for all numbers on the page](http://stackoverflow.com/a/13611748/3040605)
    * HTML & Body reset
    * unify the setting of elements's margin and padding for browsers
    * Reset fonts for relevant elements
    * Remove the clear button of a text input control in IE10+
    * Headers
    * Links
    * Utility classes
* 删除了 `package.json` -> `scripts` -> `prepublish`

## Install

```bash
npm install hx-antd
```
