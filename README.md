# <img width="30" height="30" src="https://img.icons8.com/?size=100&id=Ny0t2MYrJ70p&format=png&color=000000" alt="power-bi"> DAX Cheat Sheet

¡Bienvenido/a a Power BI **DAX Cheat Sheet**! Este repositorio es tu compañero ideal para dominar las fórmulas y funciones de DAX (_Data Analysis Expressions_) en Power BI. Ya seas un principiante que busca comprender los conceptos básicos o un analista experimentado que necesita una referencia rápida, ¡aquí encontrarás lo que necesitas!

Este espacio te ofrece una colección organizada de las funciones DAX más utilizadas, cada una con su explicación clara, ejemplos de uso y un archivo .dax con implementaciones prácticas para que puedas aplicarlas directamente en tus modelos de datos.

## 🌎 Acerca de

**DAX** (_Data Analysis Expressions_) es el lenguaje de fórmulas utilizado en Power BI, Power Pivot en Excel y SQL Server Analysis Services. Es crucial para crear columnas calculadas, medidas y tablas calculadas, permitiendo análisis de datos potentes y dinámicos.

Este **DAX Cheat Sheet** está diseñado para ser una fuente de referencia rápida y práctica, facilitando el aprendizaje y la aplicación de las funciones DAX más relevantes en tus proyectos de Power BI. Nuestro objetivo es que puedas escribir fórmulas DAX de manera más eficiente y con mayor confianza.

## 🚀 ¿Qué encontrarás aquí?

- `docs/` → Contiene subdirectorios, cada uno representando una familia de funciones DAX.
  - Cada subdirectorio (`01_math_and_statistical_functions/`, etc.) contiene:
    - Un archivo `.md` (ej: `math_and_statistical_functions.md`) que ofrece una explicación general de las funciones en esa categoría y cómo usarlas.
    - Archivos `.dax` individuales (ej: `01_sum.dax`, `02_sumx.dax`) con ejemplos de código DAX listos para usar para cada función específica.

## 📂 Estructura del Repositorio

El repositorio está organizado de forma modular, agrupando las funciones DAX por categorías para una navegación intuitiva:

```bash
DAX-cheat-sheet/
├── README.md
└── docs/
    ├── 01_math_and_statistcal_functions/
    │   ├── math_and_statistical_functions.md
    │   ├── 01_sum.dax
    │   ├── 02_sumx.dax
    │   └── ...
    ├── 02_filter_functions/
    │   ├── filter_functions.md
    │   ├── 01_filter.dax
    │   ├── 02_calculate.dax
    │   └── ...
    ├── 03_logical_functions/
    │   ├── logical_functions.md
    │   ├── 01_if.dax
    │   ├── 02_and.dax
    │   └── ...
    ├── 04_date_and_time_functions/
    │   ├── date_and_time_functions.md
    │   ├── 01_calendar.dax
    │   ├── 02_date.dax
    │   └── ...
    ├── 05_time_intelligence_functions/
    │   ├── time_intelligence_functions.md
    │   ├── 01_dateadd.dax
    │   ├── 02_datesbetween.dax
    │   └── ...
    └── ...
```

## 📝 ¿Cómo Usarlo?

Para aprovechar al máximo este `DAX-cheat-sheet`, sigue estos pasos:

1. **Clona el repositorio:** Abre tu terminal o Git Bash y clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/ayorick23/DAX-cheat-sheet.git
   ```

2. **Navega al directorio:**

   ```bash
   cd DAX-cheat-sheet
   ```

3. **Explora los comandos:** Dirígete al directorio `docs/` y explora las diferentes categorías de funciones. Por ejemplo, para entender las funciones matemáticas y estadísticas:

   ```bash
   cd docs/01_math_and_statistical_functions/
   ```

4. **Lee las explicaciones:** Abre el archivo `.md` dentro de cada categoría para obtener una descripción general y pautas de uso.

   ```bash
   cat math_and_statistical_functions.md
   ```

5. **Revisa y usa los ejemplos DAX:** Cada archivo `.dax` contiene un ejemplo práctico de cómo se usa la función. Puedes copiar y pegar el código DAX directamente en Power BI Desktop (en una medida, columna calculada o tabla calculada).

   ```bash
   cat 01_sum.dax
   ```

   **Consejo:** Abre Power BI Desktop, crea un modelo de datos simple (puedes usar un archivo CSV de ejemplo) y experimenta con estas funciones para ver cómo se comportan.

## 🤝 Contribuciones

¡Las contribuciones son increíblemente valiosas! Si deseas mejorar este **DAX Cheat Sheet**, añadir nuevas funciones, mejorar explicaciones o proporcionar más ejemplos, por favor:

1. Haz un fork de este repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcion-dax`).
3. Realiza tus cambios y haz commit (`git commit -m 'Añadir funcion DAX TOCSV'`).
4. Haz un push de tus cambios a tu fork (`git push origin feature/nueva-funcion-dax`).
5. Abre un Pull Request en este repositorio.

## 🫂 Referencias y Agradecimientos

Este repositorio ha sido creado recopilando y sintetizando información de diversas fuentes fiables sobre DAX. Quiero extender mi más sincero agradecimiento a las siguientes páginas y recursos, que han sido fundamentales para la construcción de este contenido:

- **Documentación oficial de Microsoft Learn - DAX:** La fuente principal para la definición y el uso de las funciones DAX.
  - [Referencia de expresiones de análisis de datos (DAX)](https://learn.microsoft.com/es-es/dax/)
- **DataCamp:** Hoja de referencia de DAX con las fórmulas y funciones principales.
  - [DAX Cheat Sheet](https://www.datacamp.com/cheat-sheet/dax-cheat-sheet)
- **Power BI - Análisis de Datos e Inteligencia de Negocios** por **Carlos Martínez:** Un recurso invaluable que proporcionó una base sólida y conocimientos prácticos sobre los fundamentos de Power BI y el modelado de datos y funciones DAX complejas.
  - [Curso de Udemy](https://www.udemy.com/course/power-bi-analisis-de-datos-e-inteligencia-de-negocios/?kw=power+bi+-+analisis&src=sac&couponCode=ST21MT30625G2)

¡Agradezco a todos estos recursos por su invaluable contribución al conocimiento de DAX!

## 📃 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## ✉️ Contáctame

Si tienes alguna pregunta o sugerencia, no dudes en contactarme:

[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/ayorick23)
[![Gmail](https://img.shields.io/badge/-Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:mayorickhenry@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/dereckmendez/)
[![Kaggle](https://img.shields.io/badge/-Kaggle-181717?style=flat&logo=kaggle&logoColor=white)](https://www.kaggle.com/dereckmendez)
