# MAT2409 - Análisis de datos II

Sitio web del curso **MAT2409 - Análisis de datos II**, un curso de estadística inferencial y análisis de datos.

## 📊 Acerca del curso

**MAT2409 - Análisis de datos II** es un curso que introduce a los estudiantes en los fundamentos de la estadística inferencial y el análisis de datos. El curso cubre:

- Estimación de parámetros
- Pruebas de hipótesis
- Análisis de varianza (ANOVA)
- Análisis de datos categóricos
- Regresión lineal simple y múltiple

## 🌐 Sitio web del curso

El sitio web del curso está desplegado en GitHub Pages y contiene:

- Material de los temas
- Prácticas semanales
- Tareas
- Recursos y referencias
- Programa del curso

**Ver sitio:** [https://[tu-usuario].github.io/[nombre-repo]/](https://[tu-usuario].github.io/[nombre-repo]/)

## 🛠️ Tecnologías utilizadas

- **Quarto:** Sistema de publicación científica y técnica
- **R:** Lenguaje principal para análisis estadístico
- **GitHub Pages:** Hosting del sitio web
- **GitHub Actions:** CI/CD para deployment automático

## 📁 Estructura del proyecto

```
/
├── temas/                      # Material por tema
│   ├── 00-repaso/
│   ├── 01-estimacion/
│   ├── 02-pruebas-hipotesis/
│   ├── 03-anova/
│   ├── 04-categoricos/
│   ├── 05-regresion-simple/
│   └── 06-regresion-multiple/
├── practicas/                  # Prácticas semanales
├── tareas/                     # Asignaciones individuales
├── recursos/                   # Software, referencias, datasets
├── data/                       # Datasets del curso
├── images/                     # Imágenes
├── style/                      # Estilos CSS
├── _extensions/                # Extensiones Quarto
├── _quarto.yml                 # Configuración del sitio
└── README.md                   # Este archivo
```

## 🚀 Desarrollo local

### Requisitos

- **Quarto** (versión 1.3 o superior)
- **R** (versión 4.0 o superior)
- **RStudio** (recomendado)

### Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/[tu-usuario]/[nombre-repo].git
   cd [nombre-repo]
   ```

2. Instala paquetes de R necesarios:
   ```r
   install.packages(c("tidyverse", "here", "knitr", "rmarkdown", "quarto"))
   ```

3. Renderiza el sitio:
   ```bash
   quarto render
   ```

4. Vista previa local:
   ```bash
   quarto preview
   ```

El sitio estará disponible en `http://localhost:XXXX`

### Editar contenido

1. Abre el proyecto en RStudio (archivo `.Rproj` si existe)
2. Edita archivos `.qmd` en las carpetas correspondientes
3. Renderiza para ver cambios:
   ```bash
   quarto render
   ```

## 📝 Agregar nuevo contenido

### Agregar una práctica

1. Crea archivo en `practicas/practica-X.qmd`
2. Agrega entrada en `_quarto.yml` bajo sección "Prácticas"
3. Renderiza el sitio

### Agregar una tarea

1. Crea archivo en `tareas/tarea-X.qmd`
2. Agrega entrada en `_quarto.yml` bajo sección "Tareas"
3. Renderiza el sitio

### Agregar datasets

1. Coloca archivo en `data/nombre-dataset.csv`
2. Documenta en `recursos/datasets.qmd`

## 🔄 Deployment

El sitio se despliega automáticamente a GitHub Pages cuando:

- Se hace push a la rama `main`
- Se acepta un pull request a `main`

El workflow de GitHub Actions:
1. Instala Quarto y R
2. Instala paquetes necesarios
3. Renderiza el sitio
4. Despliega a rama `gh-pages`

Ver: `.github/workflows/publish.yml`

## 📄 Licencia

El contenido del curso está bajo licencia [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).

Esto significa que puedes:
- **Compartir:** copiar y redistribuir el material
- **Adaptar:** remezclar, transformar y crear a partir del material

Bajo las siguientes condiciones:
- **Atribución:** Debes dar crédito apropiado
- **Compartir igual:** Si remezclas o transformas el material, debes distribuir tus contribuciones bajo la misma licencia

## 🤝 Contribuciones

Si encuentras errores o tienes sugerencias de mejora:

1. Abre un [Issue](../../issues)
2. O envía un [Pull Request](../../pulls)

## 📧 Contacto

Para preguntas sobre el curso:
- **Instructor:** [Nombre del instructor]
- **Email:** [email]
- **Horario de consultas:** [Horario]

## 🙏 Agradecimientos

Este sitio fue adaptado del template del curso [STA 101](https://sta101-f23.github.io/) de Duke University, creado por Mine Çetinkaya-Rundel.

---

**Última actualización:** Enero 2026
