(sphinx-intl)=
# Sphinx 国际化

直接使用 {github}`xinetzone/sphinx-intl-deploy` 模板，可以提高 Sphinx 文档的翻译效率。

## 使用方法

1. fork {github}`xinetzone/sphinx-intl-deploy` 项目，或者点击 {guilabel}`Use this template` 使用模板。为了方便描述，记此新项目为 `AA`。
2. 将已经制作好的本地化文件夹 `locales/` 替换项目 `AA` 的文件夹 `locales/`。
3. 修改文件  {file}`.github/workflows/deploy.yml` 以匹配项目 `AA`。

关于如何制作本地化的文件夹 `locales/`，可以参考已经翻译的网站：{xinetzone}`sphinx-intl-deploy/zh-CN`。
