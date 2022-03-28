# maka 前端小题

亲爱的候选人，你可以[点击这里](./intro.md)了解 Maka 更多信息。

## 做题要求

1. 使用在线 IDE [codesandbox](https://codesandbox.io/) 做题
2. 使用 React + TS 编写（如果不会，可以马上打开 React 和 TS 的文档开始学习呢）
3. 一天内完成
4. 二选一

## 一、红绿灯

查看[红绿灯demo](https://makapicture.oss-cn-beijing.aliyuncs.com/cdn/mk-widgets/fe-testing-res/traffic-light.html)，在 codesandbox 实现一个类似的应用。

要点：

- 功能逻辑
  - 暂停/播放
  - 时间间隔
  - 方向
- UI 自由发挥（发挥自身审美）

## 二、空格替换

已知一段 html 格式的字符串，实现 `replaceWhitespace` 函数将其内容的空格替换成 `&nbsp;`

注意：html tag 标签中的空格不要替换

```ts
const content = `<body><div style="padding: 1px">12           3</div></body>`

const replaceWhitespace = (htmlStr: string) => string

replaceWhitespace(content)
// 输出结果 <body><div style="padding: 1px">12&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</div></body>
```
