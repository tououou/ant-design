---
order: 0
title:
  zh-CN: 基本用法
  en-US: Basic
---

## zh-CN

简单的步骤条。

## en-US

The most basic step bar.

```jsx
import { Steps } from 'antd';

const { Step } = Steps;

ReactDOM.render(
  <Steps current={1}>
    <Step title="完成申请" description="This is a description." />
    <Step title="研究计划书写作" subTitle="Left 00:00:08" description="This is a description." />
    <Step title="先行研究阅读" description="This is a description." />
  </Steps>,
  mountNode,
);
```
