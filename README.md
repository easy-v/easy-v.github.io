# Chirpy 入门

[![Gem 版本](https://img.shields.io/gem/v/jekyll-theme-chirpy)][gem]&nbsp;
[![GitHub 许可证](https://img.shields.io/github/license/cotes2020/chirpy-starter.svg?color=blue)][mit]

通过 [**Chirpy**][chirpy] 主题安装包 [RubyGems.org][gem] 安装时，Jekyll 只能读取主题 gem 文件中的 `_data`、`_layouts`、`_includes`、`_sass` 和 `assets` 文件夹里的文件，以及 `_config.yml` 文件的少部分选项。如果你曾经安装过此主题 gem，可以使用命令 `bundle info --path jekyll-theme-chirpy` 定位这些文件。

Jekyll 团队声称这是为了让用户有更多的自主权，但这也导致用户在使用功能丰富的主题时无法享受开箱即用的体验。

要充分使用 **Chirpy** 的所有功能，需要将主题 gem 中的其他关键文件复制到你的 Jekyll 站点中。以下是需要复制的文件列表：

```shell
.
├── _config.yml
├── _plugins
├── _tabs
└── index.html
```

为了节省你的时间，同时防止在复制文件时丢失一些文件，我们提取了最新版本 **Chirpy** 主题和 [CD][CD] 工作流的那些文件/配置到此处，以便你可以在几分钟内开始写作。

## 使用

请查看[主题文档](https://github.com/cotes2020/jekyll-theme-chirpy/wiki)。

## 贡献

这个存储库会随着主题存储库的新发布自动更新。如果你遇到任何问题或想要为其改善贡献，请访问[主题存储库][chirpy]提供反馈。

## 许可证

此作品根据 [MIT][mit] 许可证发布。

[gem]: https://rubygems.org/gems/jekyll-theme-chirpy
[chirpy]: https://github.com/cotes2020/jekyll-theme-chirpy/
[CD]: https://en.wikipedia.org/wiki/Continuous_deployment
[mit]: https://github.com/cotes2020/chirpy-starter/blob/master/LICENSE