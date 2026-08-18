# eduResearchR

`eduResearchR` es un paquete de R diseñado para facilitar el acceso a una colección curada de 15 datasets educativos y de ciencias sociales, listos para la investigación y el análisis estadístico.

## Descripción
Este paquete proporciona una estructura estandarizada para cargar y explorar datos de investigación, permitiendo a estudiantes y profesionales centrarse en el análisis cuantitativo sin necesidad de preprocesamiento complejo.

## Instalación
Puede instalar la versión de desarrollo del paquete con el siguiente comando en R:

devtools::install_github("jlmarmanillo-jlms/eduResearchR", build_vignettes = TRUE)

## Uso
Una vez instalado, cargue el paquete y cualquier dataset disponible:

library(eduResearchR)
data("STARplus")
head(STARplus)

## Viñeta Pedagógica
Para consultar la guía metodológica detallada del paquete, ejecute:

vignette("intro-eduResearchR", package = "eduResearchR")

## Autor
**Jorge Luis Marmanillo Santana**  
Mgtr. en Informática Educativa

## Dataset Sources and Descriptions
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
