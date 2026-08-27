---
name: explain
description: Explain a piece of code, a file, an error message, or a concept in clear, plain terms.
argument-hint: <説明してほしいコード・ファイル・エラー・概念>
---

## 説明対象

$ARGUMENTS

## Steps

1. $ARGUMENTS に登場する概念を平たい言葉で列挙. この時簡単な役割を「登場人物」に記述.
2. 登場人物間の関係を中学生でも分かるように「登場人物の関係」に記述.
3. コードがある場合は登場人物、関係がそれぞれ実際にどこに該当するかを「具体」に説明.

## Output Format

```
1. 登場人物

...登場人物を列挙

2. 登場人物の関係

...関係を記述

3. 具体

...該当箇所、具体的なコードを記述
```
