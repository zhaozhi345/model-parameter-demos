# 模型参数互动演示

两份课堂HTML的网页入口，顶部可切换出现惩罚和频率惩罚，直接拖滑块查看柱图。

- Presence Penalty：看token是否出现过。
- Frequency Penalty：按token出现次数施加惩罚。
- 教学模拟，不调用真实模型；例句是静态预写文本。

演示原始素材由用户提供：表面发散度.html、重复惩罚度.html。相关课堂演示合集：https://think2do.github.io/mo-xing-can-shu-shuo-ming/

本版本统一中文解释、增加切换入口、将D3依赖放入仓库，并调整纵轴，避免负惩罚时柱图被裁掉。D3 v7.8.5保留发布文件头中的版权与ISC许可链接：https://github.com/d3/d3/blob/main/LICENSE 。

GitHub Pages从main分支根目录发布。仓库可见性与网页访问权限是两个设置，私有仓库并不自动意味着Pages页面只有本人可访问。
