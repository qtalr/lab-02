# Lab 2: Reading, inspecting, and writing data

<!-- 
- [ ] Create dev container
-->

## Preparation

- Read/ annotate: [Recipe \#2](https://qtalr.github.io/qtalrkit/articles/recipe-2.html). You can refer back to this document to help you at any point during this lab activity.

## Objectives

- Review using Markdown syntax for formatting, including tables, numbering sections, and citations and references
- Practice interleaving code and prose in a Quarto document
- Learn to read, inspect, and write structured data using R functions and Quarto code blocks
- Practice describing data using prose and code in a Quarto document

## Instructions

### Getting started

1. Create a Quarto document using the RStudio toolbar
  - Provide the title: "Reading, inspecting, and writing data"
  - Provide the author: \<Your Name\>
2. Render the Quarto document (without changes)
  - Click the 'Render' button on the RStudio toolbar
  - Save the Quarto file with the name `lab-2.qmd`.

### Reading, inspecting, and writing data

In the repository for this lab, you will find three data files corresponding to the data origin, data dictionary, and the data itself. 

  - `data_origin.csv`
  - `data_dictionary.csv`
  - `data.csv` 

1. Create the following sections in your `.qmd` document:

  - About the data
  - Inspect the data
  - Subset the data
  - Write the data

2. In the section "About the data", use strategies from Recipe 2 to load the necessary packages to read and inspect rectangular data and read the data origin and data dictionary files. Then, write a paragraph describing the data. Include the following information:

   1. What is the name of the data source?
   2. Where did it come from?
   3. What is the sampling frame?

3. In the section "Inspect the data", read and inspect the dataset. Write a paragraph describing the data. Include the following information:

   1. How many variables are included?
   2. What are the variable types?
   3. How many observations are included?

4. In the section "Subset the data", use strategies from Recipe 2 to subset the data to include some combination of columns and rows that you could find relevant to extract from the original dataset. Write a paragraph describing the data you have subsetted. Include the following information:

   1. How does the subsetted data differ from the original data?
   2. What are the dimensions of the subsetted data?
   3. What are the variable types?

Note: You may find the PENN 'pos' tagset useful to help you understand the values of the 'pos' variable. You can find the tagset [here](https://catalog.ldc.upenn.edu/docs/LDC95T7/cl93.html). 

5. In the section "Write the data", use strategies from Recipe 2 to write the subsetted data to a file. Describe where the file is located and what format it is in.

6. Render the `.qmd` as a PDF or a Word document

7. (optional) Explore adding a markdown table to your Quarto document and make a cross-reference in your summary prose. The `knitr` package provides a function `kable()` for creating markdown tables from rectangular data. You can read more about [creating tables from R data frames](https://quarto.org/docs/authoring/tables.html#computations) on the Quarto website.

## Assessing your progress

1. Add a section which describes your learning in this lab.

Some questions to consider: 

  - What did you learn?
  - What did you find most/ least challenging?
  - What resources did you consult? 
    - Instructor? R or Quarto documentation, Websites (provide links)?
  - What more would you like to know about reading, inspecting, and/ or writing data in R and/ or Quarto?
    - Find potential resources you might consult to continue your learning. Provide links and a brief description of the resource.

## Submission for feedback

1. To prepare your lab report for submission you will need to render your Quarto document to PDF or Word. 
2. Download this file to your local computer.
3. Submit your report as described by your instructor.

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.