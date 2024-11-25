# navigation-bar

修正小程序 Demo 中导航栏组件的 Bug：

1. 样式错误；
2. 补全了一个 HomeButton 图标；

示例：

![./screenshots/navigator-bar.png](screenshots/navigator-bar.png)

## 使用

安装：

```shell
npm install git@github.com:miniapp-develop/navigation-bar.git
```

在 `.json` 中引入组件：

```json
{
  "usingComponents": {
    "navigation-bar": "@mini-dev/navigation-bar/index"
  }
}
```

在 `.wxml` 中使用

```xml
<navigation-bar title="Title" back="{{false}}" color="black" background="#FFF"></navigation-bar>
```

## ChangeLog

### 0.0.1

- 修正原始 bug
