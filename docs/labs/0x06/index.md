# 实验六：硬盘驱动与文件系统

!!! tip ""

    <p align="right" style="font-weight: bold">by</p>

## 实验目的

1. 了解文件系统的概念、作用。
2. 实现块设备、磁盘、分区、文件系统的抽象。
3. 了解 ATA 硬盘的工作原理、实现基本的读写驱动。
4. 实现 FAT16 文件系统的读取和只读文件访问。

## 实验基础知识

!!! note "善用 LLM 进行学习"

    对于现代计算机专业的学生，建议并要求大家学习借助 LLM（Large Language Model）进行学习，这是一种非常有效的学习方法，可以帮助你更快的学习到知识。

    对于不理解的知识点和概念，建议优先参考文档、借助 LLM 进行实践，在仍然无法解决的情况下再向他人提问。

    确保你阅读了 [寻求帮助](../../general/help.md) 一节，这将帮助你更快的解决问题。

鼓励使用 Typst 来进行实验文档的编写，使用可以参考 [使用 Typst 编写报告](../../general/typst.md)。

对于本次实验内容，你需要参考学习如下实验资料：


## 实验任务与要求

1. 请各位同学独立完成作业，任何抄袭行为都将使本次作业判为 0 分。

2. 请参考 [代码规范](../../general/coding_convention.md) 进行实验代码编写。

3. 依据 [实验任务](./tasks.md) 完成实验。

    - 代码编写任务：观察提供的代码，完善所有标记为 `FIXME:` 的部分，并验证结果是否符合预期。**请在报告中介绍实现思路，截图展示关键结果。**
    - 思考任务：完成 “思考题” 和 “实验任务” 部分的内容，**在报告中简要进行回答**。*注：思考题可能也是理解代码、实现功能的重要提示。*
    - Bonus 加分项：学有余力的同学可以任选 Bonus 部分完成，尝试完成更多的功能，并在报告中进行展示。这部分内容不是必须的要求。

4. 请在实验报告中涵盖相关任务的实现截图、实验任务对应问题的解答、实验过程中遇到的问题与解决方案等内容。