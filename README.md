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

# Actualización de documentación del paquete

