# 数据驱动的可重复性研究考察细则

- 使用课程中教授的技能，创建一个数据分析、软件开发、研究复现、网站建设等类型的项目（详见项目指南）
- 3 - 5 人一组共创一个项目，将项目代码移交到课程组织（[2025年春季学期 D2RS](https://github.com/D2RS-2025spring)）`D2RS-2025spring`（使用 transfer 的方法，详见 [转让仓库指南](transfer-guide.md)）


## 项目指南

- 项目可以以课程建设为立足点，为课程课件提出改进意见。不少同学在给 [课程的评价](https://d2rs-2025spring.github.io/comments/) 中指出了课件存在的一些问题，结合自己的思考对课件进行完善是非常欢迎的操作。
- **鼓励应用课堂讲授的技能解决自己课题中的具体问题**。
- 数据分析类项目要有数据、分析过程和分析结果，使**结果可复现**。
- 软件开发类项目要可安装、可运行，能够**解决某个具体的问题**。
- 研究复现类项目要选取**高水平论文**中的部分（或者全部）结果，能够复现论文中的数据分析结果或图片。
- 网站建设类项目要有**真实的需求**（如个人网站、课题组网站等），相较 Test3 的作业要有明显的提升。


## 评分依据

- 项目内容中**必须**能够体现课堂上教授过的知识和技能，这些技能概括来说主要包括以下几点：
    - 可重复性研究环境的配置（课堂只讲了 Conda，不过你仍然可以使用 Docker，Pip，renv 等其它方式）
    - 文学化编程（课程只讲了使用 Quarto 的内容，不过你仍然可以使用 Jupyter Notebook，R Markdown 等其它方式）
    - R、Python 等语言编程（课题只讲了 R、Python 及 Shell，不过你仍然可以使用其它任何你熟悉的编程语言）
    - 人工智能技术（专有神经网络模型，以及通用人工智能大模型的应用。大模型现在发展很快，建议使用最新的模型进行创作）
    - 其它数据科学知识
- 需要保证每个人在项目中**都有贡献**（通过 Git 追踪）。
    - 项目的主持人为小组组长，创建项目的主仓库。
    - 除小组组长以外的其他同学使用 Pull Request 向组长的仓库中提交代码（基于 Test4 时使用的流程）。
- 能够**活学活用**，应用课堂讲授的技能解决自己课题中具体问题的项目，给予一定加分
    - 虽然资环研究生的专业跨度很大，但是数据科学的原理和方法是一样的。
    - 项目涉及的研究课题的专业不影响评分。
- 请将问题**描述清楚**，并把解决问题的思路解释清楚，最后通过数据科学的方法解决它。
    - 尽管项目涉及的研究课题的专业不影响评分，如果你不能解释清楚项目的问题、解决思路和解决方法，那么仍然会对得分造成不利影响。
- 建议在项目中列出自己的得分点（如使用了课堂教授的哪项技能等）


## 重要时间节点

- 分组组队阶段（即日 - 2025年4月13日 24:00），在**雨课堂**中分组。
- 项目注册阶段（即日 - 2025年4月20日 24:00），请在 [D2RS-2025spring/exam](https://github.com/D2RS-2025spring/exam/issues) 中提交 Issue，注册自己的项目（参见下面的示例，请注意：每个项目一个 ISSUE，**不要重复提交**）。

  ```
  项目名称：XXXX
  项目成员：张三（组长，学号：2024303111001），李四（学号：xxxx），王五（学号：xxxxx）
  仓库地址：https://github.com/zhangsan/awesome-project-name
  ```

- 项目研发阶段（即日 - 2025年5月25日 24:00，**里程碑式的进展**可以在前面注册的 ISSUE 里面更新（修改或者添加评论均可））
- 项目移交阶段（即日 - 2025年6月1日 24:00，注意：**最终是否完成作业以项目是否在截止时间前成功移交到 `D2RS-2025spring` 组织为准**）
