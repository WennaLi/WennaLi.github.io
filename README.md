# 李文娜的个人主页

这是李文娜的个人学术主页，基于 Jekyll 和 Academic Pages 模板构建，部署地址为 <https://wennali.github.io/>。

## 本地预览

本机当前使用 Homebrew Ruby 3.3 运行预览：

```bash
export PATH="/opt/homebrew/opt/ruby@3.3/bin:/opt/homebrew/lib/ruby/gems/3.3.0/bin:$PATH"
export SDKROOT="/Library/Developer/CommandLineTools/SDKs/MacOSX15.1.sdk"
bundle install
bundle exec jekyll serve -H localhost
```

启动后访问 <http://localhost:4000/>。

## 内容维护

- 首页内容：`_pages/about.md`
- 站点配置：`_config.yml`
- 导航菜单：`_data/navigation.yml`
- CV JSON 数据：`_data/cv.json`
- 图片资源：`images/`
- PDF 等附件：`files/`

模板示例文章、论文、讲座和教学内容已先隐藏；补充真实内容后可以再启用对应页面。
