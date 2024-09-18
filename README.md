# anki-template-choices

自用选择题 anki 模板

测试用 anki 卡组包已放在 release 和 [repo 里](for-testing.apkg)

## 功能

- 选项乱序
- 支持单选/多选
- 判断正确答案
- 在Anki for Windows/Ankiweb/AnkiDroid动作良好，其他未测试
- 夜间模式
- 单张卡片计时(beta)
- 正确率统计(beta)

## TO-DO：

- latex支持
- 样式优化
- 写使用方式

## 效果

### 日间

![图片](preview-sun.png)

### 夜间

![图片](preview-night.png)

## tips：

卡组字段分别是：

- 问题
- 选项
- 答案
- 解析

其中选项需要打开“默认使用HTML编辑器”，每个选项用``<br>```隔开

以下为选项例：

``作为观察当代世界变化的工具<br>指导中国发展的行动指南<br>引领人类社会进步的科学理论<br>提供革命、建设、改革的固定方案``

## 致谢
[参考了 cyliu-phy/simple-anki-template 的样式](https://github.com/cyliu-phy/simple-anki-template)
