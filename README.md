## Installation

```
npm install airing-translator -g
```

## Help


```
  Usage: airing [options]

  🍻  欢迎使用 Airing 翻译小助手 🍻


  Options:

    -V, --version  output the version number
    -e, --en       Add English word
    -z, --zh       Add Chinese word
    -h, --help     output usage information
```

## Example

### en -> zh

```
airing -e apple
```

Output:

```
=== 🍻  欢迎使用 Airing 翻译小助手 🍻  ===
apple 的翻译结果为：
苹果
=== 🍻  翻译成功 🍻  ===
```

### zh -> en


```
airing -z 苹果
```

Output:

```
=== 🍻  欢迎使用 Airing 翻译小助手 🍻  ===
苹果 的翻译结果为：
Apple
=== 🍻  翻译成功 🍻  ===
```