<script async src="https://www.googletagmanager.com/gtag/js?id={{ site.google_analytics }}"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', '{{ site.google_analytics }}');
</script>

# Author Contributions Checklist Form

Authors must fill out the Author Contributions Checklist (ACC) form. The purpose of the ACC form is to document the artifacts associated with a manuscript (i.e., the data and code supporting the computational findings) and describe how to reproduce the findings. The final version of this document is included as online supplemental material with the published paper and on the [JASA GitHub site](http://github.com/JASA-ACS/) and is referenced in the abstract.

Authors have two options for how to fill out the form. Please choose ONE of the following two options.

  1. You can edit [our R Markdown (Rmd) template](../assets/acc_form.Rmd). 
  2. You can fill out [this Microsoft Word-based form](../assets/acc_form.docx). 

In either case, **please generate a PDF from the form and provide as supplementary material when submitting your manuscript for review**. Please also include the R Markdown or Microsoft Word version as well (this helps us when posting materials to the JASA GitHub site as the ACC form becomes the README file in the repository for the published paper).

To generate a PDF from the R Markdown document, you can click on "Knit to PDF" in RStudio or run `rmarkdown::render('acc_form.Rmd')` from within R. Alternatively, since the R Markdown document contains no code chunks, it can be treated simply as a Markdown document and you can use tools such as `pandoc` to convert the filled form to PDF.

To generate a PDF from the Microsoft Word-based form, follow these steps after having filled out the form:

  - Unprotect the form by unclicking "Developer -> Protect Form".
  - Remove comments by selecting "Review -> Delete -> Delete All Comments in Document".
  - Finally use "File -> Save As -> File Format -> PDF".

## Guidance for preparing the ACC form

ACC forms for published papers can be seen in the Supplementary Materials section of each paper on the JASA website, as well as within the README file of each paper's [JASA GitHub repository](http://github.com/JASA-ACS/). Examples of high-quality reproducibility materials are listed [here](../index.html).

The ACC form will be read by readers after an accepted manuscript is published so please phrase your responses for future readers. For example, use the present tense rather than the future tense: "The dataset is available at..." rather than "The dataset will be available at...". In particular, if the data will be made publicly available but are not yet publicly available, please mark "Data are publicly available" in the relevant question on the form, and indicate in the Notes section at the end how reviewers can access the data during the review process. Such notes should then be deleted when final materials are submitted after acceptance. 

If you have any problems completing the form, please contact jasa.app.cs.aer@gmail.com.
