# JASA Reproducibility Pre-Submission Checklist

This checklist summarizes the *minimum expectations* for reproducibility materials accompanying all JASA research paper submissions. Authors should verify **each item** before submission of their reproducibility material. Completing this checklist before article resubmission helps ensure your materials are complete, clearly organized, and ready for review. Reproducibility reviewers check each resubmission against these standards. Catching issues early saves time for everyone and reduces the chance of delays or revision requests during the review process. Authors should **not** turn this in with their submission.

JASA recognizes outstanding reproducibility efforts through the [JASA Reproducibility Award](https://jasa-acs.github.io/repro-award/). Submissions that go beyond the minimum requirements, with exceptionally well-documented code, clear organization, and materials that make it easy for others to build on your work, are eligible for consideration. See [past recipients and evaluation criteria](https://jasa-acs.github.io/repro-award/awardees.html) for examples of what excellent reproducibility looks like in practice. 

## 1. Repository and Structure

- [ ] A top-level README (plain text or markdown) is included.
- [ ] Directory structure is self-explanatory or clearly explained in the README. Consider the [JASA Reproducibility Materials Template](https://github.com/jasa-acs/repro-template).
- [ ] Code, data, and documentation are logically separated.
- [ ] No extraneous files or directories included (e.g., `.git/`, `__MACOSX/`, `.DS_Store/`). 
- [ ] Method implementation, simulation, and data-analysis code are separated when appropriate.
- [ ] Primary software (e.g., R, Python, Julia) and packages (such as R or Python packages) with version numbers are documented in the ACC form, README, or an appropriate file. Software packages that are critical to the research should also be cited in the References section alongside paper citations. 
- [ ] Avoid document formats that may not be accessible to everyone (e.g., only usable with proprietry/paid software).
- [ ] If materials are provided in GitHub (or another Git hosting service), to ensure long-term availability, make sure that you have also either included the materials in the supplementary material or placed them in a permanent archive with a DOI, such as in Zenodo. 

## 2. README Essentials

The README clearly:

- [ ] States which scripts reproduce which figures/tables.
- [ ] States which scripts should be run and in what order.
- [ ] Documents output files or directories.
- [ ] Explains intermediate results, if provided.


## 3. Data Availability and Documentation

- [ ] Data access is clearly described (public URL or request process), including specific steps on how to access the specific files or data needed, if necessary.
- [ ] In situations with restricted data, including data accessible only via a request process, a synthetic/facsimile dataset in the same format as the real data is provided.
- [ ] A data dictionary file defines variables, types, and units, unless the data files are self-describing. Self-describing file formats embed metadata within the data file itself and therefore don't require external documentation.
- [ ] Preprocessing steps are documented, ideally via code. 


## 4. Code Completeness and Organization

- [ ] All code required to reproduce results specified in the ACC form is included.
- [ ] Simulation and competitor methods are provided if results are shown.
- [ ] Only relative file and directory paths are used (no hard-coded absolute paths).
- [ ] Wrapper or master script provided to reproduce results without modification (strongly encouraged).
- [ ] Random seeds set where exact reproducibility is expected.
- [ ] Avoid unnecessary code duplication; shared functions or utilities are defined once and imported/called across analyses, rather than copied into separate directories.


## 5. Code Documentation and Clarity

- [ ] Scripts are commented to explain analytical purpose.
- [ ] Functions are appropriately documented (particularly for user-facing code).
- [ ] Code blocks commented to identify which paper results they produce.
- [ ] No commented-out code remains (without explanation).
- [ ] Key configuration parameters are easy to locate or modify.


## 6. ACC Form Consistency

- [ ] No instructional comments appear in submitted ACC Form PDF.
- [ ] Reproducibility scope is justified if not all results are reproduced.
- [ ] Any referenced online repositories should be public upon acceptance. We encourage linking this at the resubmission stage. 

