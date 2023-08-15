<h2 align="center">duefuse🔩: 基于FUSE的数据使用控制执行点</h2>
<p align="center">
<a href="https://results.pre-commit.ci/latest/github/hitsz-ids/duefuse/main"><img alt="pre-commit.ci status" src="https://results.pre-commit.ci/badge/github/hitsz-ids/duefuse/main.svg"></a>
<a href="https://github.com/hitsz-ids/duefuse/blob/main/LICENSE"><img alt="LICENSE" src="https://img.shields.io/github/license/hitsz-ids/duefuse"></a>
<a href="https://github.com/hitsz-ids/duefuse/releases/"><img alt="Releases" src="https://img.shields.io/github/v/release/hitsz-ids/duefuse"></a>
<a href="https://github.com/hitsz-ids/duefuse/releases/"><img alt="Pre Releases" src="https://img.shields.io/github/v/release/hitsz-ids/duefuse?include_prereleases&label=pre-release&logo=github"></a>
<a href="https://github.com/hitsz-ids/duefuse"><img alt="Last Commit" src="https://img.shields.io/github/last-commit/hitsz-ids/duefuse"></a>
</p>

<p align="center">
<a href="./README.md">中文</a> | <a href="./README_en.md">English</a>
</p>

## 简介

> duefuse是DataUCON项目中的组件之一，DataUCON项目旨在为数据使用控制提供支持。[了解DataUCON](https://dataucon.idslab.io/)。

duefuse🔩是一个基于[FUSE](https://www.kernel.org/doc/html/next/filesystems/fuse.html)的数据使用控制执行点，它可以对接任何可信数据格式引擎，或直接对接决策执行点，以实现对客户端数据访问的控制。

<!-- 这里需要补充ABAUC相关文档，然后替换链接 -->

在[ABAUC控制模型](https://github.com/hitsz-ids/dataucon)当中，duetector可作为PEP（Policy Enforcement Point）来拦截用户请求，与可信数据格式引擎、PDP（Policy Decision Point）等其他组件通信以决定是否允许用户请求。

## 目录

- [主要特性](#主要特性)
- [安装](#安装)
- [快速开始](#快速开始)
- [API文档](#API文档)
- [维护者](#维护者)
- [如何贡献](#如何贡献)
- [许可证](#许可证)

## 主要特性

TBD


## 安装

TBD

## 快速开始

TBD

更多文档和例子可以在[这里](./docs/)找到。

## API文档

TBD

## 维护者

本项目由**哈尔滨工业大学（深圳）数据安全研究院**发起，若您对本项目以及DataUCON项目感兴趣并愿意一起完善它，欢迎加入我们的开源社区。

## 如何贡献

非常欢迎你的加入！[提一个 Issue](https://github.com/hitsz-ids/duefuse/issues/new) 或者提交一个 Pull Request。

开发环境配置和其他注意事项请参考[开发者文档](./DEVELOP.md)。

## 许可证

本项目使用 Apache-2.0 license，有关协议请参考[LICENSE](https://github.com/hitsz-ids/duefuse/blob/main/LICENSE)。
