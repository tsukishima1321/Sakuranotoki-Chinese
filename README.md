# Sakuranotoki-Chinese
樱之刻简中汉化，仅作学习交流使用。

6.1更新：翻译了所有人物的名字。修复了对话重复的问题。儿童节快乐~

**目前翻译完成100%**。开香槟咯！全长48684句话，日语字符共1288806，汉字字符共993538。感谢大家的支持~

## 更新日志
以下是已修改的问题：

- 若干1、2章翻译问题
- 23/06/05 修复心铃线`03_mis07_3`对话错位
- 23/06/06 修复鸟谷线`03_mak04_1`对话错乱
- 23/06/07 修复第5章`03_02_1`对话错位
- 23/06/10 修复`05_06_4`、`05_08_1`、`05_09_1`和`05_10`对话错位、重复问题；修复了大部分宫崎心铃的错误翻译。GPT4竟然为`宫崎misuzu`翻译了21个不同的名字！

## 下载方法

点击右上方绿色“`code`”按钮，之后会出现“`download zip`”，点击即可下载压缩包。

也可以直接下载release中的`script.zip`。

## 使用方法

把`script`文件夹后放置在游戏文件夹下（**推荐**）。然后开始游戏即可。

也可以下载release中的`script.zip`解压到游戏文件夹下，然后运行游戏。

由于翻译问题可能需要频繁的修改，因此code中的`script`文件夹永远是最新的，而release可能不是。所以建议还是下载code比较好。

## 翻译方法

使用GPT4网页版，在同一个session内发送15句一段的翻译请求，能有效保持上下文连贯性。翻译脚本已经开源到[VN-ChatGPT-Translator](https://github.com/kono-dada/VN-ChatGPT-Translator)

## 致谢

感谢一位b站上认识的网友[蝉时月夜](https://space.bilibili.com/13732795)提供了3个GPT plus账号，使翻译速度提升**3倍**。

## **如果你想对此翻译贡献自己的修改**：

如果在游玩的过程中遇到了不通顺或者可能错误的地方，你可以提交修改。

有两个文件夹需要关注：
- `translated`文件夹以json格式储存了GPT4翻译后对话
- `untranslated`文件夹以json格式储存了原文

你可以通过运行`find_a_sentence.py`来查找某句话在哪个文件的哪一行。**修改过后，请确保原文和译文有相同的行数。**修改完成后，运行`.\to_ast.bat`即可生成新的ast脚本。然后直接pull request即可。

最后。希望全樱之刻玩家共同维护和完善这份汉化。

