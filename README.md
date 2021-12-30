# 山东大数据竞赛—网格事件智能分类 baseline

## 简介

比赛名称：山东大数据竞赛—网格事件智能分类

测评任务：基于网格事件数据，对网格中的事件内容进行提取分析，对事件的类别进行划分，具体为根据提供的事件描述，对事件所属政务类型进行划分

任务类型：文本分类

测评链接：http://data.sd.gov.cn/cmpt/cmptDetail.html?id=67

## 环境

```
pip install ark-nlp
pip install pandas
```

## 使用说明

下载数据并解压到`data/source_datasets`中，运行`code`文件夹中的`text_classify.ipynb`，最终提交文件会生成在`data/output_datasets`

## 效果

- 线下验证集：0.69
- 线上测试：0.701982