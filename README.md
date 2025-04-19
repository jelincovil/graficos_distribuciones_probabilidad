# Gráficos distribuciones probabilidad

Seta web app busca entregar una forma llamativa de visualizar y entender modelo de probabilidad
enfocado en alumnos de ingenieria.

## Descripción de la aplicación
### Shiny App de Funciones de Densidad y Probabilidad (con Plotly) [Shinny app](https://jaimelincovil.shinyapps.io/graficos_distribuciones_shinyapp/)

## Descripción
Esta aplicación **Shiny** permite visualizar interactivamente tanto **densidades** (distribuciones continuas) como **funciones de masa** (distribuciones discretas) para varias familias estadísticas. Emplea la librería **plotly** para ofrecer gráficos con zoom, tooltips y regiones sombreadas (cola inferior, cola superior, ambas colas, zona central o igualdad).

---

## Distribuciones soportadas
- **Continuas**:  
  - Normal  
  - t-Student  
  - Chi‑cuadrado  
  - F de Snedecor  
  - Exponencial  
- **Discretas**:  
  - Binomial  
  - Poisson  
  - Geométrica  

---

## Instalación

```bash
git clone https://github.com/tu-usuario/tu-proyecto.git
cd tu-proyecto
R -e "install.packages(c('shiny','shinythemes','plotly'))"
# Ejecutar la app:
Rscript -e "shiny::runApp('app.R')"
```


## Librerias utilizadas
- [R shinny](https://shiny.posit.co/)
- [Rstudio](https://posit.co/download/rstudio-desktop/)
- [Plotly](https://plotly.com/r/)

