# Seedance 社区参考说明

查阅日期：2026-11-20（北京时间 / Asia/Shanghai）。以下链接指向可变的main分支，不是不可变版本锁定；仅代表本次公开文档读取结果。

## 来源与许可

| 来源 | 实际读取入口 | 许可核验与限制 |
|---|---|---|
| dexhunter/seedance2-skill | [README](https://github.com/dexhunter/seedance2-skill/blob/main/README.md)、[英文SKILL](https://github.com/dexhunter/seedance2-skill/blob/main/SKILL.md)、[LICENSE](https://github.com/dexhunter/seedance2-skill/blob/main/LICENSE) | LICENSE为MIT，版权声明为Copyright (c) 2026 Dex (i@dex.moe)。README称其指南基于字节跳动文档；本次没有独立打开核验其所引官方文档。若后续复制其代码或大量文档，须随附原版权及MIT许可声明。 |
| LearnPrompt/awesome-seedance / goodcase.ai | [README](https://github.com/LearnPrompt/awesome-seedance/blob/main/README.md)、[LICENSE](https://github.com/LearnPrompt/awesome-seedance/blob/main/LICENSE) | LICENSE为MIT，Copyright (c) 2026 LearnPrompt；但README的Copyright & Takedown Notice明确代码才适用MIT，编选/组织/统计/模板提炼/原创摘要适用[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)，原始提示词与媒体仍属各自作者，不因仓库公开而取得再分发权。 |

本技能参考上述作者的社区方法，以中文重新组织、概念性改写；未搬运案例提示词、媒体、代码或整套模板。对awesome-seedance / goodcase.ai的编选方法借鉴在此署名、链接并声明改写，不将其原始案例混同为MIT素材。本说明不赋予第三方素材额外许可，也不决定本仓库其余内容的许可证。

## 提炼的方法及精确位置

- dexhunter `SKILL.md` 的 **Core Syntax: The @ Reference System / Assigning Roles to References**：参考素材应明确用途，而非把全部外观、动作、背景、音频一起继承。改写为“实际素材—限定继承—排除继承”表，并额外约束纯文生不编造素材。
- dexhunter `SKILL.md` 的 **Prompt Structure Blueprint** 与 **Interaction Instructions**：主体、场景、动作、摄影、时间、转场、声音与风格分层；按需给简单/复杂方案。沿用通用层次而不复制模板或其参数表。
- awesome-seedance README 的 **Prompt Templates by Category → Structural foundations**：连续时间窗、单个主要动作与对应声音；身份参考应限定继承范围。该原则强化本技能的每段结果状态与参考输入边界。
- 同README的 **Realism and UGC / Commercial and product / Narrative and performance**：不同视频类型采用不同可见线索；产品和人物分别保持一致；对白要包含行动引发的反应。改写为按题材选择的分支，不强制所有作品电影化。
- 同README开头明确：其稳定性标签描述原始案例提示词的复跑，不代表借助技能生成的新内容已被测试。本技能因此区分原帖、社区复测与新提示词，不转述成功率，也未复核其统计或视频结果。

## 按需附录：特定模型素材语法

以下只说明dexhunter所述即梦Seedance 2.0指南的写法，不是本技能的默认语法：其英文指南用 `@Image1`、`@Video1`、`@Audio1` 指代实际上传素材，并分别指定外形、场景、运镜、动作、节奏或音频用途。仅当当前入口确实支持该写法、用户实际提供且允许使用对应素材时，才采用入口认可的标识；不能用这些占位符捏造素材。图片/视频/音频各类角色也要按当前版本支持情况核实。

本技能核心纯文生不需要这些标识。其他模型采用自己的语法和参数；即使同属一个模型系列，也不从本附录继承能力或上限。

## 社区指南不等于官方能力规范

两仓库均为社区资料，不是目标生成入口的服务合同。dexhunter文档面向即梦Seedance 2.0，包含时长、参考文件数量/格式、分辨率、人脸上传限制等具体说法；本技能未将其作为当前普适规则。awesome-seedance覆盖多个版本并有大量案例，不表示案例时长或输入方式在每个入口均可用。

本次未独立核实官方当前能力、Seedance 2.5 Flash参数、API时长/分辨率/素材上限、费用、人脸政策或原生音频支持。纯文生、图片参考、视频参考、音频参考、编辑、延长与分镜图转视频必须按本次入口分别核实。保留模型/入口/版本和查证日期，不能跨版本直接套用社区参数。

本次没有下载媒体、执行安装脚本、安装第三方技能，也没有测试视频。原始案例及媒体许可未逐一核实，故未复制或打包。
