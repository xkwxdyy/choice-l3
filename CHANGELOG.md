# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]


## [v2.3.0] - 2021-12-24


### Added
- `prelabel`增加了同义键值: `pre-label`
- `poslabel`增加了同义键值: `pos-label`, `postlabel`, `post-label`
- 自动识别内容中是否有includegraphic，并自动调整anchor
- 增加了`autopic`键值，设置图片的默认排版anchor

### Changed
- `xshift`修改为`firstcolsep`的dim设置
- 原来的`yshift`修改为`belowsep`
- 用修改`topsep`的方式定义yshift

### Removed
- 去掉了`firstcolsep`等一系列同义键值


### Fixed
- 删除`coffinchoice`排版时的`\noindent`, `topsep`键值产生了预想的效果（原来是会产生`bottom`的效果）