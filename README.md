<p align="right">
    <a href="https://badge.fury.io/rb/just-the-docs"><img src="https://badge.fury.io/rb/just-the-docs.svg" alt="Gem version"></a> <a href="https://github.com/just-the-docs/just-the-docs/actions/workflows/ci.yml"><img src="https://github.com/just-the-docs/just-the-docs/actions/workflows/ci.yml/badge.svg" alt="CI Build status"></a> <a href="https://app.netlify.com/sites/just-the-docs/deploys"><img src="https://api.netlify.com/api/v1/badges/9dc0386d-c2a4-4077-ad83-f02c33a6c0ca/deploy-status" alt="Netlify Status"></a>
</p>
<br><br>
<p align="center">
    <h1 align="center">Just the Docs</h1>
    <p align="center">A modern, highly customizable, and responsive Jekyll theme for documentation with built-in search.<br>Easily hosted on GitHub Pages with few dependencies.</p>
    <p align="center"><strong><a href="https://just-the-docs.com/">See it in action!</a></strong></p>
    <br><br><br>
</p>

<p align="center">A video walkthrough of various Just the Docs features</p>

https://user-images.githubusercontent.com/85418632/211225192-7e5d1116-2f4f-4305-bb9b-437fe47df071.mp4

## Installation

### Use the template

The [Just the Docs Template] provides the simplest, quickest, and easiest way to create a new website that uses the Just the Docs theme. To get started with creating a site, just click "[use the template]"!

Note: To use the theme, you do ***not*** need to clone or fork the [Just the Docs repo]! You should do that only if you intend to browse the theme docs locally, contribute to the development of the theme, or develop a new theme based on Just the Docs.

You can easily set the site created by the template to be published on [GitHub Pages] – the [template README] file explains how to do that, along with other details.

If [Jekyll] is installed on your computer, you can also build and preview the created site *locally*. This lets you test changes before committing them, and avoids waiting for GitHub Pages.[^2] And you will be able to deploy your local build to a different platform than GitHub Pages.

More specifically, the created site:

- uses a gem-based approach, i.e. uses a `Gemfile` and loads the `just-the-docs` gem
- uses the [GitHub Pages / Actions workflow] to build and publish the site on GitHub Pages

Other than that, you're free to customize sites that you create with the template, however you like. You can easily change the versions of `just-the-docs` and Jekyll it uses, as well as adding further plugins.

### Use RubyGems

Alternatively, you can install the theme as a Ruby Gem, without creating a new site.

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "just-the-docs"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: just-the-docs
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install just-the-docs

Alternatively, you can run it inside Docker while developing your site

    $ docker-compose up

## Usage

[View the documentation][Just the Docs] for usage information.

## Contributing

Bug reports, proposals of new features, and pull requests are welcome on GitHub at https://github.com/just-the-docs/just-the-docs. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

### Submitting code changes:

- Submit an [Issue](https://github.com/just-the-docs/just-the-docs/issues) that motivates the changes, using the appropriate template
- Discuss the proposed changes with other users and the maintainers
- Open a [Pull Request](https://github.com/just-the-docs/just-the-docs/pulls)
- Ensure all CI tests pass
- Provide instructions to check the effect of the changes
- Await code review

### Design and development principles of this theme:

1. As few dependencies as possible
2. No build script needed
3. First class mobile experience
4. Make the content shine

## Development

enuSpace gitHub HomePage : https://expnuni.github.io/enuspace_doc/

enuSpace Overview


enuSpace는 HMI/SCADA/DCS/IOT/AI 분야에서 활용되는 다기능 통합개발자 솔루션입니다. 그래픽 편집 및 런타임 뷰어 기능을 포함하고 있으며, 동적 데이터 가시화 도구를 제공합니다. 객체 지향 프로그래밍(Object Oriented Programming:OOP)개념을 도입한 사용자정의 라이브러리를 생성하여 그래픽 컴포넌트로 적용 가능합니다.

enuSpace는 동적 디스플레이와 시뮬레이션 도구가 통합되어 로직 및 알고리즘 라이브러리 블럭을이용하여 데이터 연결선 만으로 플로우베이스 프로그래밍(Flowbased Programming)이 가능합니다. 연산결과는 동적 디스플레이 객체를 통하여 표현합니다.

enuSpace는 소프트웨어 개발자 도구(Software Development Kit :SDK)를 제공하며, SDK그래픽 기능을 활용하여 빠르고 수려한 윈도우 그래픽 프로그램을 개발할수 있습니다.

## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

[^2]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

[Jekyll]: https://jekyllrb.com
[Just the Docs Template]: https://just-the-docs.github.io/just-the-docs-template/
[Just the Docs]: https://just-the-docs.com
[Just the Docs repo]: https://github.com/just-the-docs/just-the-docs
[GitHub Pages]: https://pages.github.com/
[Template README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use the template]: https://github.com/just-the-docs/just-the-docs-template/generate
