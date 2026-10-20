# 数据和开源组件

- Hanzi Writer 3.7.3，MIT，https://github.com/chanind/hanzi-writer 。本地文件：assets/hanzi-writer.min.js；许可证：assets/HANZI-WRITER-LICENSE。
- cnchar / cnchar-order / cnchar-words 3.2.6，MIT，https://github.com/theajack/cnchar 。本地文件：assets/cnchar*.js；许可证：assets/CNCHAR-LICENSE。用于拼音、多音字、笔画数量、笔画名称、补充组词。
- Hanzi Writer Data 2.0.1 / Make Me a Hanzi，原始字形为文鼎字体（Arphic Technology）。字形和笔顺数据为 Arphic Public License；完整许可证：assets/ARPHICPL.TXT；来源说明：assets/STROKES-LICENSE。https://github.com/chanind/hanzi-writer-data 。已打包部分常用汉字数据，其他字通过 jsDelivr 按需加载并缓存；不修改原始笔顺数据。
- 内置 data/english.json 与 data/words.json 为本应用编写的常用词和低年级例句。
- 超出内置英语词库的查询使用 https://mymemory.translated.net/doc/spec.php ，有免费调用额度限制；并非人工审校的儿童词典。不将接口结果作为权威教材内容。

应用代码不需要 API key，不含任何用户密钥。
