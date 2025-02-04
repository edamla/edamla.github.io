---
layout: default
title: Anasayfa
nav_order: 1
description: "Açık kaynak olarak hazırlanan Proje ve sayfalarımızla alakalı olarak dökümantasyon sayfamız"
permalink: /
---

# E-Damla Open Source | Hoşgeldiniz
{: .fs-9 }

Açık kaynağın herkesin faydasına olduğuna inanıyoruz. Bilginin açık ve özgürce ulaşılabilir olması sorunları çözerek işbirliğini ve teknolojinin gelişimini sağlayacağına inanıyoruz.
{: .fs-6 .fw-300 }

[Başlayalım](#başlangıç){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [GitHub'da bizi inceleyin](https://github.com/edamla/){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Başlangıç

### Bağımlılıklar

Bu sayfa "Just the Docs" projesinden oluşturulmuştur ve [Jekyll](https://jekyllrb.com) ile çalışır, Jekyll bir statik sayfa oluşturucudur ve Ruby dilinde yazılmıştır. Detaylı bilgi için hızlı başlangıç [dosyalarına](https://jekyllrb.com/docs/) bakabilirsiniz. Just the Docs teması herhangi bir özel Jekyll eklentisine gereksinim duymaz. Ve standart Github Pages ile oluşturulur.

### Quick start: Use as a GitHub Pages remote theme

1. Add Just the Docs to your Jekyll site's `_config.yml` as a [remote theme](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/)
```yaml
remote_theme: pmarsceill/just-the-docs
```
<small>You must have GitHub Pages enabled on your repo, one or more Markdown files, and a `_config.yml` file. [See an example repository](https://github.com/pmarsceill/jtd-remote)</small>

### Local installation: Use the gem-based theme

1. Install the Ruby Gem
```bash
$ gem install just-the-docs
```
```yaml
# .. or add it to your your Jekyll site’s Gemfile
gem "just-the-docs"
```
2. Add Just the Docs to your Jekyll site’s `_config.yml`
```yaml
theme: "just-the-docs"
```
3. _Optional:_ Initialize search data (creates `search-data.json`)
```bash
$ bundle exec just-the-docs rake search:init
```
3. Run you local Jekyll server
```bash
$ jekyll serve
```
```bash
# .. or if you're using a Gemfile (bundler)
$ bundle exec jekyll serve
```
4. Point your web browser to [http://localhost:4000](http://localhost:4000)

If you're hosting your site on GitHub Pages, [set up GitHub Pages and Jekyll locally](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll) so that you can more easily work in your development environment.

### Configure Just the Docs

- [See configuration options]({{ site.baseurl }}{% link docs/configuration.md %})

---

## About the project

Just the Docs is &copy; 2017-2019 by [Patrick Marsceill](http://patrickmarsceill.com).

### License

Just the Docs is distributed by an [MIT license](https://github.com/pmarsceill/just-the-docs/tree/master/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/pmarsceill/just-the-docs#contributing).

### Code of Conduct

Just the Docs is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/pmarsceill/just-the-docs/tree/master/CODE_OF_CONDUCT.md) on our GitHub repository.
