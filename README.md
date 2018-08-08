<h1 align="center">Emojis for Plus(ThinkSNS+)</h1>

## 简介

这个包主要目的是为 Plus 非 iOS 平台提供 Emoji 常用表情列表

## 安装

```bash
# NPM
npm i @slimkit/plus-emojis
# Yarn
yarn add @slimkit/plus-emojis
```

## 使用

```js
let emojis = require('@slimkit/plus-emojis');

console.log(emojis);
/*

[
    {
        text: "😂",
        unicode: "U+1F602"
        bytes: "\xF0\x9F\x98\x82"
    }
]
*/
```

## 国际化

针对每个表情，提供了一些辅助性描述文件，存放在 `i18n` 目录中。以中文为例：

```js
let lang = require('@slimkit/plus-emojis/i18n/zh-CN');
console.log(lang);
/*
{
    "😂": "笑哭"
}
*/
```

## License

这个包所有内容遵循 MIT 许可证发布，请参阅完整的[许可证文本](https://github.com/slimkit/plus-emojis/blob/master/LICENSE)
