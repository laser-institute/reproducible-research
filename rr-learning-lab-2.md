# Reproducible Research - Learning Lab 2: Getting Started With RStudio Desktop

## Introduction
This week, we've been using [RStudio Cloud](https://rstudio.cloud/), which is a fully-featured version of the RStudio Interactive Development Environment. Now, we want to support your use of RStudio Desktop.

## Installing RStudio Desktop

It is important to note that RStudio and R are _separate_ software, and that using RStudio Desktop requires you to have also installed R. You may also use R separate from using RStudio, but we recommend using RStudio Desktop because of the features it adds to R (a file and plot viewer, a pane that captures what is in your environment, and code completion, among others). Both R and RStudio are freely available, cross-platform, and open-source.

### To Download R:

- Visit [CRAN](https://cran.r-project.org/) (https:[]()//cran.r-project.org/) to download R 
- Find your operating system (Mac, Windows, or Linux)
- Select the "latest release" on the page for your operating system
- Download and install the application

Don't worry; you will not mess anything up if you download (or even install!) the wrong file. Once you've installed R, you can get started.

### To Download RStudio:

- Visit [RStudio's website](https://www.rstudio.com/products/rstudio/download/) (https[]()://www.rstudio.com/products/rstudio/download/) to download RStudio
- Under the column called "RStudio Desktop FREE", click "Download"
- Find your operating system (Mac, Windows, or Linux)
- Select the "latest release" on the page for your operating system 
- Download and install the application

## Opening RStudio

You can open RStudio like any other application. That's all!

## Projects

One of the first steps of every workflow should be to set up a "Project" within RStudio. 
A Project is the home for all of the files, images, reports, and code that are used in any given project.

We use Projects because they create a self-contained folder for a given analysis in RStudio. 
This means that if you want to share your Project with a colleague, they will not have to reset file paths (or even know anything about file paths!) in order to re-run your analysis.

Furthermore, even if the only person you ever collaborate with is a future version of yourself, using a Project for each of your analyses will mean that you can move the Project folder around on your computer, or even move it to a new computer, and remain confident that the analysis will run in the future (at least in terms of file path structures).

## Your Task for this Learning Lab

Creating a Project is one of the first steps in working on an R-based data science project in RStudio.

From within RStudio, follow these steps:

1. Click on "File"
1. Select "New Project"
1. Choose "New Directory"
1. Click on "New Project"
1. Enter your Project's name in the box that says, "Directory name". We
    recommend choosing a Project name that helps you remember that this is a
    project that involves data science in education. Avoid using spaces in your
    Project name, and instead, separate words with hyphens or underscore
    characters.
1. Choose where to save your Project by clicking on "Browse" next to the box
    labeled "Create project as a subdirectory of:". If you are just using this
    to learn and test out creating a Project, consider placing it in your
    downloads or another temporary directory so that you remember to remove it
    later.
1. Click "Create Project"

At this point, you should have a Project that will serve as a place to store any `.Rmd` or `.R` scripts that you create as you work through this text as well as any data associated with this Project.

We should point out that it is not *necessary* to create a Project for your work, although we _strongly_ recommend it. When you utilize Projects in tandem with the {here} package, you will be set up with an easy-to-use workflow. For more on using Projects with the {here} package, read @bryan2017's [article](https://www.tidyverse.org/blog/2017/12/workflow-vs-script/)(https:[]()//www.tidyverse.org/blog/2017/12/workflow-vs-script/).

To complete this learning lab, add data associated with a project and create an `.Rmd` file. In this `.Rmd` file, load your data file(s) and write at least one additional line of code for your analysis. In short, **your task is to get yourself set up for your independent learning analytic project.**

If you'd like more practice, take a few moments to set up a couple of additional Projects by following the steps listed above.

## How to "Submit" Your Work for this Learning Lab

When complete, message in the "#projects" channel in Slack, "I set up a project in RStudio Desktop! My project is on . . . ."
