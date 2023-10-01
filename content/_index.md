### Overview

**Simsite** is a web-based vignettes for illustrating the usage of our simulation pipeline for single-cell and spatial transcriptome data.

The **online shiny tool** for **method selection and data simulation** can be accessed [here](http://47.254.148.113:3838/app/simshiny).

Simsite contains three main sections:

* Programming usage. All demonstrations and programming environment are in **R**. It shows the pipeline from environment configuration, parameter estimation, data simulation and output assessment.

* References. [simmethods](https://github.com/duohongrui/simmethods) is the core package in our project. We collected 49 methods and bundled them into a single package. For each method, we prepared a detailed vignette for users.

* [Online tool](http://47.254.148.113:3838/app/simshiny) for method selection and simulation. We also provided an interactive website for users to select a suitable simulation method and simulate datasets conveniently.

#### Quick start

[Programming start](/programming/) ⬅

[Install R packages or download Docker images](/programming/1-installation) ⬅

[Online tool for method selection and data simulation tool](http://47.254.148.113:3838/app/simshiny) ⬅

### Features

* A [Docker image](https://hub.docker.com/repository/docker/duohongrui/simpipe/general) is provided to help users configure the environment easily.

* An interactive online tool can be used.

* Detailed vignettes for each simulation method using [simmethods](https://github.com/duohongrui/simmethods) package.

### Help and Issues

If you need help or have any issue about our tools and vignettes. Send an email to duohongrui(duohongrui@cqnu.edu.cn) or raise an issue on [github](https://github.com/duohongrui).

### New Methods

We are glad to add new simulation methods (especially for simulating spatial transcriptome data) if some methods are innovative and new. If you have the requirements, please tell Hongrui Duo by email(duohongrui@cqnu.edu.cn) or raise an [issue](https://github.com/duohongrui/simmethods/issues) for that.