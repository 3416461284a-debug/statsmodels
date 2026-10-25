<!-- 中文用途说明：开始 -->
# 回归分析与统计检验｜statsmodels

> **一句话看懂：做回归、统计检验和时间变化分析。**

| 你想了解什么 | 中文说明 |
|---|---|
| 这个工具能做什么 | 做回归、统计检验和时间变化分析。 |
| 怎么使用 | 通过Python代码建立统计模型、做检验并查看结果。 |
| 适合谁 | 需要做实证研究、回归和时间变化分析的人。 |
| 主要限制 | 缺失值、变量高度重复等问题可能影响结果。 |
| 后续可以怎么改 | 分析前检查数据，输出诊断和结果说明。 |

**当前状态：代码已复制到这个账号；尚未安装或实际运行验证。上面的修改建议还没有实施。**

[查看中文工具总目录](https://github.com/3416461284a-debug/akshare/tree/research-catalog-2026-10-25/%E8%A1%8C%E4%B8%9A%E7%A0%94%E7%A9%B6%E5%B7%A5%E5%85%B7%E7%AE%B1) · [查看各工具的详细评估](https://github.com/3416461284a-debug/akshare/tree/research-catalog-2026-10-25/%E8%A1%8C%E4%B8%9A%E7%A0%94%E7%A9%B6%E5%B7%A5%E5%85%B7%E7%AE%B1/03_详细报告和核验记录/%E7%83%AD%E9%97%A8%E5%B7%A5%E5%85%B7%E7%BC%BA%E9%99%B7%E4%B8%8E%E6%94%B9%E9%80%A0%E6%8A%A5%E5%91%8A.md)

中文用途整理日期：2026年10月25日。
<!-- 中文用途说明：结束 -->

---

<details>
<summary>原项目详细说明（点击展开）</summary>

![Statsmodels logo](docs/source/images/statsmodels-logo-v2-horizontal.svg)

[![PyPI
Version](https://img.shields.io/pypi/v/statsmodels.svg)](https://pypi.org/project/statsmodels/)
[![Conda
Version](https://anaconda.org/conda-forge/statsmodels/badges/version.svg)](https://anaconda.org/conda-forge/statsmodels/)
[![License](https://img.shields.io/pypi/l/statsmodels.svg)](https://github.com/statsmodels/statsmodels/blob/main/LICENSE.txt)
[![Azure CI Build
Status](https://dev.azure.com/statsmodels/statsmodels-testing/_apis/build/status/statsmodels.statsmodels?branchName=main)](https://dev.azure.com/statsmodels/statsmodels-testing/_build/latest?definitionId=1&branchName=main)
[![Codecov
Coverage](https://codecov.io/gh/statsmodels/statsmodels/branch/main/graph/badge.svg)](https://codecov.io/gh/statsmodels/statsmodels)
[![PyPI - Downloads](https://img.shields.io/pypi/dm/statsmodels?label=PyPI%20Downloads)](https://pypi.org/project/statsmodels/)
[![Conda
downloads](https://img.shields.io/conda/dn/conda-forge/statsmodels.svg?label=Conda%20downloads)](https://anaconda.org/conda-forge/statsmodels/)

# About statsmodels

statsmodels is a Python package that provides a complement to scipy for
statistical computations including descriptive statistics and estimation
and inference for statistical models.

# Documentation

The documentation for the latest release is at

<https://www.statsmodels.org/stable/>

The documentation for the development version is at

<https://www.statsmodels.org/dev/>

Recent improvements are highlighted in the release notes

<https://www.statsmodels.org/stable/release/>

Backups of documentation are available at
<https://statsmodels.github.io/stable/> and
<https://statsmodels.github.io/dev/>.

# Main Features

- Linear regression models:
  - Ordinary least squares
  - Generalized least squares
  - Weighted least squares
  - Least squares with autoregressive errors
  - Quantile regression
  - Recursive least squares
- Mixed Linear Model with mixed effects and variance components
- GLM: Generalized linear models with support for all of the
  one-parameter exponential family distributions
- Bayesian Mixed GLM for Binomial and Poisson
- GEE: Generalized Estimating Equations for one-way clustered or
  longitudinal data
- Discrete models:
  - Logit and Probit
  - Multinomial logit (MNLogit)
  - Poisson and Generalized Poisson regression
  - Negative Binomial regression
  - Zero-Inflated Count models
- RLM: Robust linear models with support for several M-estimators.
- Time Series Analysis: models for time series analysis
  - Complete StateSpace modeling framework
    - Seasonal ARIMA and ARIMAX models
    - VARMA and VARMAX models
    - Dynamic Factor models
    - Unobserved Component models
  - Markov switching models (MSAR), also known as Hidden Markov Models
    (HMM)
  - Univariate time series analysis: AR, ARIMA
  - Vector autoregressive models, VAR and structural VAR
  - Vector error correction model, VECM
  - exponential smoothing, Holt-Winters
  - Hypothesis tests for time series: unit root, cointegration and
    others
  - Descriptive statistics and process models for time series analysis
- Survival analysis:
  - Proportional hazards regression (Cox models)
  - Survivor function estimation (Kaplan-Meier)
  - Cumulative incidence function estimation
- Multivariate:
  - Principal Component Analysis with missing data
  - Factor Analysis with rotation
  - MANOVA
  - Canonical Correlation
- Nonparametric statistics: Univariate and multivariate kernel density
  estimators
- Datasets: Datasets used for examples and in testing
- Statistics: a wide range of statistical tests
  - diagnostics and specification tests
  - goodness-of-fit and normality tests
  - functions for multiple testing
  - various additional statistical tests
- Imputation with MICE, regression on order statistic and Gaussian
  imputation
- Mediation analysis
- Graphics includes plot functions for visual analysis of data and model
  results
- I/O
  - Tools for reading Stata .dta files, but pandas has a more recent
    version
  - Table output to ascii, latex, and html
- Miscellaneous models
- Sandbox: statsmodels contains a sandbox folder with code in various
  stages of development and testing which is not considered \"production
  ready\". This covers among others
  - Generalized method of moments (GMM) estimators
  - Kernel regression
  - Various extensions to scipy.stats.distributions
  - Panel data models
  - Information theoretic measures

# How to get it

The main branch on GitHub is the most up to date code

<https://www.github.com/statsmodels/statsmodels>

Source download of release tags are available on GitHub

<https://github.com/statsmodels/statsmodels/tags>

Binaries and source distributions are available from PyPi

<https://pypi.org/project/statsmodels/>

Binaries can be installed in Anaconda

conda install statsmodels

# Getting the latest code

## Installing the most recent nightly wheel

The most recent nightly wheel can be installed using pip.

``` bash
python -m pip install -i https://pypi.anaconda.org/scientific-python-nightly-wheels/simple statsmodels --upgrade --use-deprecated=legacy-resolver
```

## Installing from sources

See INSTALL.txt for requirements or see the documentation

<https://statsmodels.github.io/dev/install.html>

# Contributing

Contributions in any form are welcome, including:

- Documentation improvements
- Additional tests
- New features to existing models
- New models

<https://www.statsmodels.org/stable/dev/test_notes>

for instructions on installing statsmodels in *editable* mode.

# License

Modified BSD (3-clause)

# Discussion and Development

Discussions take place on the mailing list

<https://groups.google.com/group/pystatsmodels>

and in the issue tracker. We are very interested in feedback about
usability and suggestions for improvements.

# Bug Reports

Bug reports can be submitted to the issue tracker at

<https://github.com/statsmodels/statsmodels/issues>

</details>
