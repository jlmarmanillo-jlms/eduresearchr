# eduResearchR

`eduResearchR` is an R package designed to facilitate access to a curated collection of 15 educational and social science datasets, ready for research and statistical analysis.

## Description
This package provides a standardized structure for loading and exploring research data, enabling students and professionals to focus on quantitative analysis without the need for complex preprocessing.

## Installation
You can install the development version of the package with the following command in R:

```r
devtools::install_github("jlmarmanillo-jlms/eduResearchR", build_vignettes = TRUE)
```

## Usage
Once installed, load the package and any available dataset:
```r
library(eduResearchR)
data("STARplus")
head(STARplus)
```

## Pedagogical vignette
To consult the detailed methodological guide of the package, run:
```r
vignette("intro-eduResearchR", package = "eduResearchR")
```

## Author
Jorge Luis Marmanillo Santana

M.Sc. in Educational Informatics

## Dataset sources and descriptions
The 15 datasets included in **`eduResearchR`** have been curated and organized from standard R packages to facilitate educational research and applied statistical analysis:

* `apipop.rda`: Academic Performance Index student and school-level dataset.
* `CASchools.rda`: California Test Score Data for school districts.
* `classroom.rda`: Classroom-level data on student achievement and instruction.
* `collegeDistance.rda`: High School and Beyond dataset on higher education accessibility.
* `EducationLiteracy.rda`: Cross-national indicators of educational literacy and attainment.
* `ExamScores.rda`: Student examination scores and performance metrics.
* `FirstYearGPA.rda`: First-year college GPA and academic predictor variables.
* `MathAchieve.rda`: Mathematics achievement scores from high school students.
* `NELS.rda`: National Education Longitudinal Study (NELS) of 1988 dataset on school effectiveness.
* `pisausa.rda`: Program for International Student Assessment (PISA) data for the United States.
* `school.rda`: Institutional indicators and structural school characteristics.
* `schoolProgram.rda`: Evaluation data on school academic programs and interventions.
* `schools.rda`: Census and demographic data across primary and secondary schools.
* `STARplus.rda`: STAR project dataset on class size reduction and student achievement with non-experimental controls.
* `STUDENT.rda`: Student-level demographic and academic performance records.
