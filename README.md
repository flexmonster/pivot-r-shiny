# Flexmonster Pivot Table & Charts integration with R Shiny
[![Flexmonster Pivot Table & Charts](https://cdn.flexmonster.com/landing.png)](https://www.flexmonster.com?r=github)
Website: [www.flexmonster.com](https://www.flexmonster.com?r=github)

## Flexmonster Pivot Table & Charts

Flexmonster Pivot is a powerful JavaScript tool for interactive web reporting. It allows you to visualize and analyze data from JSON, CSV, SQL, NoSQL, Elasticsearch, and OLAP data sources quickly and conveniently. Flexmonster is designed to integrate seamlessly with any client-side framework and can be easily embedded into your application.

This repository contains a sample [R](https://www.r-project.org/) + [Shiny](https://www.rstudio.com/products/shiny/) project for Flexmonster Pivot Table & Charts.

Table of contents:

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Related Flexmonster docs](#related-flexmonster-docs)

## <a id="prerequisites"></a>Prerequisites

- [R](https://www.r-project.org/)
- [Shiny package](https://www.rstudio.com/products/shiny/)

  Install it from the R Console:
  ```bash
  install.packages("shiny")
  ```

## <a id="installation"></a>Installation

1. Download a `.zip` archive with the sample project or clone it from GitHub with the following command:

```bash
git clone https://github.com/flexmonster/pivot-r-shiny.git && cd pivot-r-shiny
```

2. Run the sample project from the R Console:

```bash
library(shiny)
runApp('~/my-proj')
```

## <a id="related-flexmonster-docs"></a>Related Flexmonster docs
- [Integration with R Shiny](https://www.flexmonster.com/doc/integration-with-r-shiny?r=github) — learn how to integrate Flexmonster into an R Shiny project.
