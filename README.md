# zero to nlp

## 特点

1. 注重中文的nlp建设
2. 基于transformers库
3. 每一个项目，都具有数据、模型训练、部署等模块
4. 提供公开的数据
5. 开箱即用，保证代码都是可跑通，替换数据即可训练出自己的模型
6. transformers库的源码级介绍
7. 基于pytorch，不用tensorflow
8. 模型方面，只介绍大模型，不再介绍传统文本模型
9. 每一个项目，都会给出相关的坑和注意事项

## 目录

| 中文名称   | 文件夹名称                                                                                           | 数据  | 数据清洗 | 大模型 | 模型部署 | 图解  |
|--------|-------------------------------------------------------------------------------------------------|-----|------|-----|------|-----|
| 中文文本分类 | [chinese_classifier](https://github.com/yuanzhoulvpi2017/zero_nlp/tree/main/chinese_classifier) | ✅   | ✅    | ✅   | ☑️   | ✅   |
| 中文gpt2 | [chinese_gpt2](https://github.com/yuanzhoulvpi2017/zero_nlp/tree/main/chinese_gpt2)             | ✅   | ✅    | ✅   | ✅    | ☑️  |

## 数据流程图解

我一直觉得，数据流程通过图解的形式表达出来，其实是最清楚的，因此我都会尽可能的把每一个任务的都图解出来。

### 文本分类数据图解

<img src="https://github.com/yuanzhoulvpi2017/zero_nlp/raw/main/images/%E6%96%87%E6%9C%AC%E5%88%86%E7%B1%BB.003.png"/>

### 中文gpt2
<img src="https://github.com/yuanzhoulvpi2017/zero_nlp/raw/main/images/chinesegpt2_bot.png"/>

