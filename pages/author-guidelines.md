<script async src="https://www.googletagmanager.com/gtag/js?id={{ site.google_analytics }}"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', '{{ site.google_analytics }}');
</script>

# Author Guidelines

This document outlines the journal's expectations for authors with regards to submission of code and data to allow for reproducibility of the work. During the review process, the reviewers and editors will assess the potential for the work to be reproduced based on the code and data provided. However, as with other aspects of a manuscript, it is ultimately the authors’ responsibility to ensure that the code and data are of high quality and that the work is reproducible. As the focal point for reproducibility information, authors are required to include an [Author Contributions Checklist (ACC) Form](acc.html) with their submission. 

The criteria for reproducibility that will be assessed during the reviewing process are as follows.

 - All required sections of the ACC Form should be complete and clear. 
 - Unless a clear, compelling rationale is provided, the data should be available to the reviewers, and the ACC Form should indicate how it will be made publicly available upon publication (if the data are not publicly available already). Exceptions for reasons of security or confidentiality may be granted by the Editor. In such cases, if possible a pseudo-dataset should be provided that can be used with the code in place of the real dataset.
 - The ACC Form should indicate where the code and data will be made publicly available upon publication of the manuscript, but code and data need not be publicly available at the time of submission when there are concerns about confidentiality. As with the contents of the manuscript, code and data will be considered to be confidential unless they are publicly available at the time of review. If not publicly available and not directly included with the submission, authors should provide clear instructions on how to access the code and data. These instructions can be included in the Notes section in the ACC Form.
 - Artifacts such as code and data that support the results in the manuscript should be deposited in suitable open repositories. Some suitable repositories for code (but not large datasets) include GitHub, GitLab, and BitBucket. Artifacts may also be included as supplementary materials with the published article, but we strongly encourage deposition in public repositories. If authors' materials are not publicly available at the time of submission, they should be included as supplementary materials for the review process. Code and data (<500 MB) in supplementary materials will be deposited upon acceptance in the [JASA area of Figshare](https://tandf.figshare.com/JASA). We encourage authors to obtain DOIs for both code and data.
 - JASA is partnering with [Dataverse](https://dataverse.harvard.edu/dataverse/jasa) to provide repositories for data associated with JASA articles. Data can be deposited in the JASA Dataverse after acceptance, in which case the dataset will officially be part of the JASA Dataverse, or it can be deposited in the general Harvard Dataverse and will be linked to from the JASA Dataverse after acceptance.
 - The data provided with the submission should represent as closely as possible the data originally available to the authors, whether from a public source (e.g., US Census data) or data collected by the authors or their colleagues. Data cleaning/preparation are considered to be part of the workflow that should be reproducible with the code and data provided. 
 - The data should be in a form, including with clear metadata and in a non-proprietary format, that can be used and understood by others. A data dictionary describing the variables used in the reproducible analyses should be included.
 - We encourage authors who use public datasets to cite those datasets, including any DOI for the data.
 - The code should run and reproduce the key results in the paper (data preparation/cleaning, analyses, figures and tables). While determination of which results should be reproducible is based on the authors’ judgment at submission, whether the key results are reproducible will be an important consideration during the review process.
 - The code should be in a form that can be used and understood by others, including being readable at a line-by-line level in terms of syntax and comments. 
 - There should be a clear, documented workflow to reproduce the key results. For workflows involving more than a single script, there should be a master script, Makefile or other mechanism available such that it is clear what each component does, in what order to run the components, and what are the inputs to and outputs from the different components.
 - Once a manuscript is conditionally accepted, the code and data (unless an exception is granted for the latter) must be made available as detailed in the ACC form. Manuscripts will not be accepted and should not be claimed as such by the authors until this occurs.

Please contact the Associate Editors for Reproducibility at [jasa.app.cs.aer@gmail.com](mailto:jasa.app.cs.aer@gmail.com) with any questions about submitting code and data or completing the ACC Form.
