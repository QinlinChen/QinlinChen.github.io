| [Home](index.md) | [My Reading List](reading-list.md) | [Github](https://github.com/QinlinChen) | [Zhihu](https://www.zhihu.com/people/QinlinChen) |

# Qinlin Chen (陈钦霖)

- Ph.D. Student.
- [Pascal Research Group][pascal], [Institute of Computer Software][ics].
- [School of Computer Science][njucs], [Nanjing University][nju].

Contact:
- Office: 529, Building of Computer Science and Technology, Xianlin Campus of Nanjing University.
- Email: chenqinlin98 AT gmail DOT com.

## About

I am studying for a Ph.D. degree in the [Pascal Research Group][pascal] at Nanjing University. I am supervised by [Yue Li][yueli] (李樾). I have my interest in programming languages, software reliability methods, and infrastructure systems. Currently I am focusing on applying modern PL&SE techniques to hardware descrpition languages.

## Education

- Nanjing University (Sep 2022 - now), China
  - Studying for a Ph.D. Degree in Computer Science and Technology
  - Supervisor: [Yue Li][yueli] & [Tian Tan][tiantan]
- Nanjing University (Sep 2020 - Jul 2022), China
  - Studying for a M.Sc. Degree in Computer Science and Technology
  - Advisor: [Yanyan Jiang][yanyanjiang]
- Nanjing University (Sep 2016 - Jul 2020), China
  - Recevied a B.Sc. Degree in Computer Science and Technology

## Publications

Corresponding authors are marked with an asterisk (\*).

### Hardware Static Analysis

- (PLDI'26) [Exploiting Sophisticated Static Analysis for Verilog](https://dl.acm.org/doi/10.1145/3808300). [[PDF](papers/2026_PLDI_Qihe.pdf)] [[Homepage][qihe]]
  - **Qinlin Chen**, [Nairen Zhang][nairenzhang], [Jinpeng Wang][jinpengwang], [Jiacai Cui][jiacaicui], Tian Tan\*, Xiaoxing Ma, Chang Xu, Jian Lu, and Yue Li\*.
  - This is the conference version of [Qihe (ArXiv'26)](https://arxiv.org/abs/2601.11408).
- (ArXiv'26) [Qihe: A General-Purpose Static Analysis Framework for Verilog](https://arxiv.org/abs/2601.11408). [[PDF](papers/2026_ArXiv_Qihe.pdf)] [[Homepage][qihe]]
  - **Qinlin Chen**, [Nairen Zhang][nairenzhang], [Jinpeng Wang][jinpengwang], [Jiacai Cui][jiacaicui], Tian Tan\*, Xiaoxing Ma, Chang Xu, Jian Lu, and Yue Li\*.
- (POPL'26) [ChiSA: Static Analysis for Lightweight Chisel Verification](https://dl.acm.org/doi/10.1145/3776660). [[PDF](papers/2026_POPL_ChiSA.pdf)] [[Artifact](https://doi.org/10.5281/zenodo.17281239)]
  - [Jiacai Cui][jiacaicui], **Qinlin Chen**, Zhongsheng Zhan, Tian Tan\*, and Yue Li\*.   

### Hardware Programming Languages and Semantics

- (OOPSLA'23) [The Essence of Verilog: A Tractable and Tested Operational Semantics for Verilog](https://dl.acm.org/doi/10.1145/3622805). [[PDF](papers/2023_OOPSLA_LambdaV.pdf)] [[Artifact](https://zenodo.org/doi/10.5281/zenodo.8140941)]
  - **Qinlin Chen**, [Nairen Zhang][nairenzhang], [Jinpeng Wang][jinpengwang], Tian Tan\*, Chang Xu, Xiaoxing Ma, and Yue Li\*.
  - 🏆 _Distinguished Artifact Award_

### Hardware Acceleration

- (OOPSLA'26) [When FPGA Meets Dataflow Analysis: An Explorative Step](https://dl.acm.org/doi/10.1145/3839508). [[PDF](papers/2026_OOPSLA_FpgaFlow.pdf)] [[Artifact](https://doi.org/10.5281/zenodo.19045151)]
  - Fang Wei, **Qinlin Chen** (co-first author), [Nairen Zhang][nairenzhang], [Jiacai Cui][jiacaicui], Tian Tan\*, Zhiqiang Zuo, and Yue Li\*.

## Projects

- [Qihe][qihe]: The First General-Purpose Static Analysis Framework for Verilog
  - Unlike traditional Verilog linters, which are limited to basic code-style or syntactic checks, Qihe enables deep semantic analysis of hardware designs at the RTL stage.
  - Qihe is primarily designed and maintained by me, with significant contributions from [Nairen Zhang][nairenzhang], [Jinpeng Wang][jinpengwang], and [Jiacai Cui][jiacaicui].
- [Vide][vide]: A Modern SystemVerilog Coding IDE
  - It brings hardware developers 10+ code analysis features often missing from traditional hardware IDEs, such as precise completion, code annotations, automatic refactoring, and semantic highlighting.
  - Vide was initially maintained by [Jiayan Wu][jiayanwu] and is now maintained by [Jiarong Hong][jiaronghong].

> **Qihe and Vide are complementary**. Vide is optimized for fast, immediate static-analysis feedback during hardware development. This makes it less suited to deeper, more resource-intensive analyses, such as hardware bug detection, which are the focus of Qihe.

## Services

- Peer Review
  - Reviewer for TOSEM, 2026
  - Artifact Evaluation Committee Member for OOPSLA, 2024
    - 🏆 _Distinguished Artifact Reviewer Award_

- Teaching Assistant:
  - [Static Program Analysis (Fall 2021)](https://pascal-group.bitbucket.io/teaching.html), Nanjing University.
  - [Structure and Interpretation of Computer Programs (Fall 2020)](https://nju-sicp.bitbucket.io/2020/), Nanjing University.

## Awards & Honors

- 2025年南京大学博士研究生创优项目
- OOPSLA 2024 Distinguished Artifact Reviewer Award
- OOPSLA 2023 Distinguished Artifact Award
- 2023年江苏银行奖学金 (Bank of Jiangsu Scholarship, 2023)
- 南京大学2020届优秀毕业生 (Outstanding Graduates Awards of Nanjing University, 2020)
- 2019年南京大学拔尖计划奖学金特等奖

## Posts

I wrote some posts (in Chinese) on Zhihu for fun. Click [here](https://www.zhihu.com/people/QinlinChen/posts) if you have any interests.

[pascal]: https://pascal-lab.net/
[nju]: https://www.nju.edu.cn/en/
[njucs]: https://cs.nju.edu.cn/
[ics]: https://cs.nju.edu.cn/ics/
[qihe]: https://qihe.pascal-lab.net/
[vide]: https://vide.pascal-lab.net/

[yueli]: https://cs.nju.edu.cn/yueli/
[tiantan]: https://silverbullettt.bitbucket.io/
[yanyanjiang]: https://ics.nju.edu.cn/~jyy/
[jiacaicui]: https://www.cuijiacai.com/
[nairenzhang]: https://naiiren.github.io/
[jinpengwang]: https://jjppp.github.io/
[jiayanwu]: https://github.com/roife
[jiaronghong]: https://github.com/hongjr03
