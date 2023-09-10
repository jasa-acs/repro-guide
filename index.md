<script async src="https://www.googletagmanager.com/gtag/js?id={{ site.google_analytics }}"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', '{{ site.google_analytics }}');
</script>

# The JASA Reproducibility Guide

As of September 2021, all **invited revisions** to JASA (both Applications & Case Studies and Theory & Methods) must include code, data, and the workflow to reproduce the work presented. We encourage but do not require that initial submissions include the code, data, and workflow.

These web pages provide guidance on reproducibility for authors and reviewers in JASA. 

## Guidance for authors

1. In preparing your materials, please see our [guidelines for authors](pages/author-guidelines).
2. Authors must fill out the [ACC form](pages/acc.html), documenting the reproducibility of their work. 
3. We strongly encourage the use of a Git repository for code and workflow materials (but not large datasets) hosted on a site such as GitHub, GitLab, or BitBucket. If desired, authors might choose to keep the repository private until the time of publication. We provide an optional [template repository](https://github.com/jasa-acs/repro-template) as an example on which you can base your repository. If using a repository, we strongly recommend that the main `README.md` of the repository provide an overview of how to carry out the analyses presented in their manuscript.
4. When submitting your supplementary materials, please submit the [PDF of the ACC form](pages/acc.html) as a separate file in addition to any supplementary material files not directly related to reproducibility (e.g., additional figures/tables, proofs). In addition, if you are submitting reproducibility materials as part of the supplemental materials (instead of, or in addition to, using a repository as discussed above), please submit all reproducibility materials as a single zip file (which we suggest naming as `reproducibility_materials.zip`). Please use a clear directory/folder structure within the zip file to organize your reproducibility materials (perhaps mimicking the structure suggested in our [template repository](https://github.com/jasa-acs/repro-template)).
5. Feel free to look at previously published articles for example reproducible materials. All reproducibility materials for published articles in Applications & Case Studies (those submitted as of September 2016) are available at [https://github.com/jasa-acs](https://github.com/jasa-acs). Below are several recent examples of articles that meet or exceed the reproducibility standards:

  - Le Bao, Changcheng Li, Runze Li & Songshan Yang (2022) Causal Structural Learning on MPHIA Individual Dataset [[article](https://doi.org/10.1080/01621459.2022.2077209)] [[Supplemental material](https://doi.org/10.6084/m9.figshare.19763552.v1)]
   - **2023 JASA Reproducibility Awardee**: Cecilia Balocchi, Sameer K. Deshpande, Edward I. George & Shane T. Jensen (2023) Crime in Philadelphia: Bayesian Clustering with Particle Optimization [[article](https://doi.org/10.1080/01621459.2022.2156348)] [[Supplemental material](https://doi.org/10.6084/m9.figshare.21688991.v1)] [[Github repository](https://anonymous.4open.science/r/particle-optimization-663E/)]
   - **2023 JASA Reproducibility Awardee**:  Lucy L. Gao, Jacob Bien & Daniela Witten (2022) Selective Inference for Hierarchical Clustering [[article](https://doi.org/10.1080/01621459.2022.2116331)] [[Supplemental material](https://doi.org/10.6084/m9.figshare.21313178.v1)] [[Github repository](https://github.com/lucylgao/clusterpval-experiments)] [[R package](https://www.lucylgao.com/clusterpval/)]

## JASA Reproducibility Award

The [JASA reproducibility award](https://jasa-acs.github.io/repro-award) recognizes outstanding computational reproducibility efforts in the statistical field. It was established in 2023, with the inaugural winners recognized at the 2023 Joint Statistical Meetings (JSM). All manuscripts accepted into JASA in a calendar year are eligible for the award, which will be awarded at the JSM the following year.

## Guidance for reproducibility reviewers

While an associate editor may ask one of the reviewers to review a given manuscript for reproducibility, in most cases one of the JASA associate editors for reproducibility (AER) is asked to carry out this review (by selecting the generic 'reviewer for reproducibility' in the review system). 

1. Please see our [guidelines for reviewers](pages/reviewer-guidelines) when reviewing a manuscript for reproducibility.
2. We ask that reproducibility reviewers consider [these review criteria](pages/review-form) and ideally explicitly fill out a review form (simply create a document with the headers as given in that link) and include the completed form as an attachment with your review.

## General resources on reproducibility

Various journals are now requiring or strongly encouraging authors to provide code and data to reproduce their work. In addition, many researchers have written guidance on best practices for reproducibility. These are just a few of the many resources you may find online.

1. [Guidance from a group of reproducibility (aka 'data') editors of social science journals](https://social-science-data-editors.github.io/guidance).
2. The American Economic Association requires code and data for all submissions to the AEA journals. Here is [guidance from the AEA data editor](https://aeadataeditor.github.io/aea-de-guidance).

## Help

Please contact the Associate Editors for Reproducibility at [jasa.app.cs.aer@gmail.com](mailto:jasa.app.cs.aer@gmail.com) with any questions about the guidelines for authors or for reviewers, or if you are interested in learning more about our reproducibility initiative.
