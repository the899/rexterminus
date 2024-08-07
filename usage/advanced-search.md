# 高级搜索

原生 Emby 的搜索在某些情况下存在延迟并且无法模糊搜索。终点站对服务端做出了修改，并支持以下功能：

1. 搜索实现本身几乎没有延迟(1ms内)，只有网络延迟；
2. 支持中字从任意位置搜索，不再要求从首字开始输入；
3. 支持拼音首字母搜索(任意位置)；
4. 允许小幅度词序错乱；
5. 支持中字/拼音/首字母混搜。

> **例如：** 搜索「老友记」、「友记」、「lyj」、「友老记」、「l友记」均可得到「老友记」这个搜索结果。如图：

![img.png](../assets/1.7aa3d402.png)

> *高级搜索支持官方客户端及 web 端，第三方修改的客户端可能无法实现。

注1：搜索名请参考 [TMDB](https://web.archive.org/web/20230605005641/https://www.themoviedb.org/) 上的 zh-cn 译名以及原产地名。由于 TMDB 的规则，mod 删除了大量在 Netflix, Disney Plus 等国外平台上映却未在中国大陆上映的剧集及电影的 zh-cn 译名，在此情况下请使用原产地名作为搜索关键词。

注2：高级搜索功能仅支持一二三妹等 Emby 端服务器，不支持四妹 Infuse 服务器。