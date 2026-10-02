# 第三方组件与内容说明

- swift-fsrs：MIT，固定 4fbaf20184d62f82a9f44f343337c61a2c5483e9。
- SwiftCSV：MIT，固定 324d583f2e6eb587c62bcd8574693d5c4f9b6eff。
- JWTKit 4.13.5：MIT，固定 13e7513b3ba0afa13967daf77af2fb4ad087306c；附带 BoringSSL 许可文本。
- Apple Swift Crypto 与 Swift ASN.1：Apache 2.0，许可证随资源提供。最近一次 CI 分别解析为 3.15.1、1.7.3。
- ECDICT：MIT，仅提取 ky 标记的 4801 个词条；保留原许可证及来源摘要。
- Noto Serif SC：SIL OFL 1.1，保留字体内版权记录及独立许可文件。
- App 图标与原创功能示例来自本项目开发内容；未包含用户头像照片。
- PDFKit、Vision、AVFoundation、AuthenticationServices 为 Apple 系统框架。

各许可证完整文本位于 StudyDesk/Resources。社区真题数据不随公开候选分发。公开仓库与授予原创代码开源许可证是两件事，原创代码许可待维护者决定。

## 内置政治基础练习

包含 C-Eval 政治相关四科选择题 887 道：马原 203、毛概 248、史纲 240、思修 196。它们是基础练习，不代表完整历年考研真题，也不代表覆盖 2027 大纲和最新时政。答案沿用原数据，尚未逐题独立复核；867 道未提供原解析。

数据作者为 Huang et al. (2023)，来源 https://github.com/hkust-nlp/ceval 与 https://huggingface.co/datasets/ceval/ceval-exam 。本题包遵循 CC BY-NC-SA 4.0，仅限非商业使用，署名并以相同许可分享题包改编。此数据许可与 App 原创代码许可分别适用。完整许可及转换说明随 App 提供。

新安装会加载这 887 道基础题及原有 14 道原创示例题。升级按题号追加缺少的题目，保留已有题库、答题记录和进度。当前为已完成静态检查的源码候选，尚未完成 Xcode/真机验证。
