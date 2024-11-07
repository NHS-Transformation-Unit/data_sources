<img src="images/TU_logo_large.png" alt="TU logo" width="200" align="right"/>

# Data Sources Quarto Site
This repository contains the source files for a Quarto website that provides an overview of data sources that can be used on TU projects.

## Table of Contents

1. [Purpose](#purpose)
2. [Repository Structure](#repo-structure)
3. [Getting Started](#getting-started)
4. [Raising Issues](#raising-issues)
5. [Contributors](#contributors)

## 1. Purpose

This website has been built, and is still being developed in [Quarto](https://quarto.org/) with the aim of documenting important sources of data that we use on our projects. Beyond documenting data sources the website is also designed to educate others within the team on the data sources that can be used on projects, how to explore these and what they can be helpful for.

## 2. Repository Structure

The repository is structured as:

```plaintext

data-sources/
├── .git/
├── .gitignore
├── _quarto.yml
├── index.qmd
├── pages/
    ├── topic1.qmd
    ├── topic1_a.qmd
    ├── topic1_b.qmd
    ├── topic2.qmd
    ├── topic2_a.qmd
    ├── topic2_b.qmd
    └── ...
├── images/
├── tu_theme.css
├── docs/
└── README.md

```

* `_quarto.yml`: Configuration file for Quarto, specifying website structure and settings.
* `index.qmd`: The homepage content.
* `pages/`: Contains individual `.qmd` files for each of the topics and data sources documented in the website.
* `images/`: Stores images used within the website.
* `tu_theme.css`: Contains the custom `.css` file for TU formatting.
* `docs/`: The output directory for rendered HTML files. These are then used by GitHub Pages to host the website.

## 3. Getting Started

To clone this repository and set-up the project locally:

1. **Clone the repository**:

```bash
git clone https://github.com/NHS-Transformation-Unit/data_sources.git
```
2. **Navigate into the directory**:

```bash
cd data_sources
```
3. **Install Quarto**:
If not already completed then install [Quarto](https://quarto.org/docs/get-started/) or ensure that it is accessible via your IDE of choice.

4. **Render website locally**:

For example within R, run:

```r
quarto::quarto_render()
```
5. **Preview the site**:

Open the HTML files in the `docs/` folder to view the website locally.

## 4. Raising Issues
If you are raising an issue due to a bug or for adding a missing data source then please follow these guidelines:

* __Title__: Clearly and concisely describe the issue.
* __Labels__: Add the relevant label (e.g. `bug`, `enhancement`, etc.) to help the issue be appropriately categorised.
* __Description__: Provide a clear description of the issue including screenshots if necessary.
* __Steps to reproduce__: If reporting a bug, please outline the steps to reproduce the issue.

## 5. Contributors

* __[Andy Wilson](https://github.com/ASW-Analyst)__