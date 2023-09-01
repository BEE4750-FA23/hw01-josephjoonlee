# BEE 4750 Homework 1

Instructions: [![Web Instructions](https://img.shields.io/static/v1?label=HW1&message=HTML&color=b31b1b&labelColor=222222&style=flat)](https://viveks.me/environmental-systems-analysis/assignments/hw1/hw1/) [![PDF Instructions](https://img.shields.io/static/v1?label=HW1&message=PDF&color=b31b1b&labelColor=222222&style=flat)](https://viveks.me/environmental-systems-analysis/assignments/hw1/hw1.pdf)

This homework assignment is focused on simulating a systems model under uncertainty to evaluate risk.

## Learning Objectives

After completing Homework 1, students will be able to:

* derive a descriptive simulations model for a system;
* implement a deterministic model in Julia;
* evaluate tradeoffs across multiple objectives;
* identify how a management strategy might reflect the perspectives of different interested parties;
* critically evaluate how modeling assumptions might influence conclusions of a modeling study.

## What To Submit

Submit a single `.pdf` file to Gradescope. Make sure to tag each problem. You should include code with your submission in code blocks as needed for your solution. Similarly, figures should be captioned appropriately.  **Make sure that your final report includes a References section!**

To generate your `.pdf` directly, you'll need to have LaTeX and Julia installed on your system. From your local HW repository directory, run the `compile_report.jl` script:

```bash
julia compile_report.jl solution-file-name.jmd
```
where `solution-file-name.jmd` is the name of your HW solution file. If you don't have LaTeX installed, and don't want to install it, you can get a sense of how your report will look by compiling it to HTML (it won't be very pretty, as there's no stylesheet, but you'll see all of the code snippets, results, and plots):

```bash
julia compile_report.jl solution-file-name.jmd html
```

If you have the Julia REPL open, you can also compile your file to a `.pdf` using

```julia, eval=false
include("compile_report.jl")
compile_report("solution-file-name.jmd")
```
or to HTML by adding in the optional "html" argument

```julia, eval=false
include("compile_report.jl")
compile_report("solution-file-name.jmd", "html")
```

If you compile to an HTML file, you can then print the resulting HTML file to a PDF using a web browser.

## Assignment Logistics

For information on accessing, writing, compiling, and submitting your report, see [the course website](https://viveks.me/environmental-systems-analysis/assignments/assignment-logistics/).