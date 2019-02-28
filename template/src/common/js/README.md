# js
不要将任何文件单独放在该路径下， 如有需要， 应该添加一个文件夹用于存放公共文件

## api: 接口请求

> 为什么 api 不放在 pages 页面下? 为了秉承 DRY 原则， 有可能页面间请求同一个接口， 所以放在该路径下， 统一管理

## components 公共组件

所有页面都能复用的组件

## directives 公共指令

## filters 公共过滤器

## i18n
可复用的国际化

## lib 库文件

## mixins

mixin

## pages

每个页面所引用的 js 文件， 都放在 pages 下

## utils 工具函数

将函数分散在多个文件， 在使用到的地方单独引用。 用到哪个引用哪个。

> 不要将不相关的函数放到一个文件中！
> 不要将第三方 lib 放到这个文件夹。放到 `src/js/lib` 目录下工具函数