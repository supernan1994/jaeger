<img align="right" width="290" height="290" src="http://jaeger.readthedocs.io/en/latest/images/jaeger-vector.svg">

[![Build Status][ci-img]][ci] [![Coverage Status][cov-img]][cov] [![Gitter chat][gitter-img]][gitter] [![OpenTracing-1.0][ot-badge]](http://opentracing.io) [![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fjaegertracing%2Fjaeger.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fjaegertracing%2Fjaeger?ref=badge_shield) [![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/1273/badge)](https://bestpractices.coreinfrastructure.org/projects/1273)

# Jaeger - a Distributed Tracing System

本项目主要针对Jaeger最新版本做了一下改动：

  * 使用阿里云logstore做数据存储
  * 支持全局检索

感谢阿里云logstore fork的[jaeger项目](https://github.com/aliyun/aliyun-log-jaeger)，我们没有直接使用这个项目，因为此项目jaeger版本较老，而且已经跟jaeger分离为两个项目，很难合并官方的新功能。  
但我们从中copy了大量的代码，在支持阿里云logstore作为backend的基础上，增加了定制化的功能。
