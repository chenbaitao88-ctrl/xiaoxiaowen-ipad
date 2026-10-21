# 数据和开源组件

- Hanzi Writer 3.7.3，MIT，https://github.com/chanind/hanzi-writer 。本地文件：assets/hanzi-writer.min.js；许可证：assets/HANZI-WRITER-LICENSE。
- cnchar / cnchar-order / cnchar-words 3.2.6，MIT，https://github.com/theajack/cnchar 。本地文件：assets/cnchar*.js；许可证：assets/CNCHAR-LICENSE。用于拼音、多音字、笔画数量、笔画名称、补充组词。
- Hanzi Writer Data 2.0.1 / Make Me a Hanzi，原始字形为文鼎字体（Arphic Technology）。字形和笔顺数据为 Arphic Public License；完整许可证：assets/ARPHICPL.TXT；来源说明：assets/STROKES-LICENSE。https://github.com/chanind/hanzi-writer-data 。已打包部分常用汉字数据，其他字通过 jsDelivr 按需加载并缓存；不修改原始笔顺数据。
- 内置 data/english.json 与 data/words.json 为本应用编写的常用词和低年级例句。
- 超出内置英语词库的查询使用 https://mymemory.translated.net/doc/spec.php ，有免费调用额度限制；并非人工审校的儿童词典。不将接口结果作为权威教材内容。

应用代码不需要 API key，不含任何用户密钥。

## v1.2.0 小学常用库

- 常用汉字范围：3,500 字，依据《义务教育语文课程标准（2022年版）》附录常用字表的公开转录。来源：https://github.com/zispace/hanzi-chars ，文件 `data-charlist/《义务教育语文课程》（2022年版）常用字表.txt`。字表为范围参考，不代表二年级必会字，也不是对每个字的教材印次核对。
- 3,500 字的全部笔顺数据来自 Hanzi Writer Data 2.0.1，按原数据收录，许可见原有 Arphic 文件。全量字的笔画名称数量已与笔顺路径数核对一致。
- 汉字拼音参考 pinyin-data 的 `kTGHZ2013.txt`；词语拼音参考 phrase-pinyin-data 与 pypinyin。来源：https://github.com/mozillazg/pinyin-data 、https://github.com/mozillazg/phrase-pinyin-data 、https://github.com/mozillazg/python-pinyin ，MIT，许可证在 assets/PINYIN-DATA-LICENSE、PHRASE-PINYIN-LICENSE、PYPINYIN-LICENSE。词语读音仍需结合实际语境，特别是多音字。
- 中文词语选择：保留原词库、已核对教材词语，并参考 complete-hsk-vocabulary 新标准1—3级的词条范围（仅作常用性参考，不作为小学教学大纲）。来源：https://github.com/drkameleon/complete-hsk-vocabulary ，MIT，许可证 assets/HSK-LICENSE。
- 已有中文词语释义参考 chinese-xinhua（MIT）并补充儿童易读释义。来源：https://github.com/pwxcoo/chinese-xinhua ，许可证 assets/XINHUA-LICENSE。1,899词中1,216词有释义；其余683词明确标为待补充，不冒充完整词典。
- 英语：本应用编写小学日常词语释义和简单例句，保留原128词，合计1,180个不同单词/短语。不是任何指定版本教材的完整词表，也不是按词元去重的1180个基础单词。部分包含复数形式、英美拼写变体及常用短语。
- 新增英语音标参考 ECDICT（MIT）：https://github.com/skywind3000/ECDICT ，许可证 assets/ECDICT-LICENSE；部分复数音标人工补充。短语按单词组合的音标标明“短语分词参考音标”，不代表连读音标。来源混合英美音，不统一标成美式音标，系统朗读优先使用 en-US 声音。
- 英语选词阶段参考的列表：mahavivo/english-wordlists 中小学词汇列表和 Kaiyiwing/qwerty-learner 中小学词表，仅用于筛选范围；本版本没有发布其教材例句或词典文件。已下载的原始参考资料保留在工作目录，不随用户包分发。
- 引用范围仅作学习参考，未宣称为出版社授权教材数据。暂无外研新思维、北京版或人教版全套教材完整覆盖。
