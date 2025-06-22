## 语言 | Language
**[中文](README.md) | [English](README_EN.md)**


# 有兽Chat
这是一款基于开源大语言模型驱动的有兽焉角色扮演对话Demo，目前支持貔貅皮皮，记忆与性格截止到漫画第500章。

## 目前支持的版本：
:one: 天禄0.5.1.dev
  - 皮皮的脾气十分暴躁！小心不要被干掉或者吃掉~
  - 皮皮可能出现记忆混乱、输出幻觉内容的现象，我们正在改善这一点。
  - _**剧透警告**_ :no_entry_sign::这个版本的皮皮还不知道 *** 的存在，也不知道 *** 的死讯。不信？不信就去问问他！

## 目前状态: 
:white_check_mark: 开放测试

有兽Chat目前使用非常简洁的Gradio网页进行对话，目前最高支持16K上下文（理论上是支持的，但单次输入最好不要超过100字），20轮对话（超出20轮将强制清零）。

欢迎各位来体验对话！你们的反馈和建议对本项目十分重要！

<!-- :no_entry: 暂时下线 -->

## 立即使用
测试链接: https://02beff1db11c3368a1.gradio.live

这是基于Gradio的中转链接，由于本项目频繁的测试，在每次上下线时都会被强制更新链接。我们会在更改链接后第一时间更新链接，如遇链接失效请参考本网站最新链接。

## 声明
  - 想了解更多关于有兽焉的内容？请移步 [有兽焉漫画](https://manga.bilibili.com/detail/mc29329) 和 [有兽焉动漫](https://www.bilibili.com/bangumi/media/md28235647) !
  - 本项目参考并使用了来自[有兽档案馆](https://youshou.wiki/)的数据，感谢他们为本项目做出的贡献！
  - 本项目基于 [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) 和 [LangChain](https://docs.langchain.com.cn/docs/introduction/) 完成。 
  - 本项目将在更新至较为完善的版本后开源，包括但不限于基座模型选择、数据生成规范、后训练流程、增强检索框架、模型历史节点等。敬请关注！
