# <span style="font-family: 'Times New Roman', serif; font-size: 11pt;">Práctica Investigativa: Verificación del Método SVD-RDPG para Medir Polarización</span>

<div style="font-family: 'Times New Roman', serif; font-size: 11pt;">

## Descripción General

Este repositorio contiene la implementación y análisis del método basado en Descomposición en Valores Singulares de Grafos con Producto Punto Aleatorio (SVD-RDPG) para medir polarización estructural en redes sociales, con énfasis en evaluar su potencial para monitoreo de polarización en tiempo real. El método fue propuesto por Anastasi et al. (2025) y utiliza la dimensión de embedding como medida de polarización independiente del tamaño de la red.

## Notebooks

### YouTubeGraphs.ipynb

**Experimento 1: Grafos Temporales de YouTube**

Este notebook implementa el análisis de interacciones de usuarios de YouTube relacionadas con el juicio de Álvaro Uribe Vélez durante el período del 23 de febrero al 15 de abril de 2025. El objetivo principal es evaluar la evolución temporal de la polarización mediante el seguimiento de la dimensión de embedding en diferentes ventanas temporales.


### VaccinesGraphs.ipynb

**Experimento 2: Redes de Twitter sobre COVID-19 y Vacunación**

Este notebook analiza redes de retweets bidireccionales relacionadas con COVID-19 y vacunación durante los años 2020, 2021 y 2022 en Francia. El objetivo es validar la dimensión de embedding mediante comparación con métricas estructurales tradicionales y analizar la evolución temporal de la polarización durante la pandemia.


### TwitterGraphs.ipynb

**Experimento 3: Redes de Elecciones Parlamentarias Finlandesas**

Este notebook evalúa la capacidad del método para distinguir entre temas controversiales y no controversiales utilizando 183 redes de retweets de las elecciones parlamentarias finlandesas de 2019. El análisis se centra en la evolución temporal de la dimensión de embedding a través de tres períodos electorales.


### EliteTwitter.ipynb

**Experimento 4: Redes de Elite y Masa en Twitter**

Este notebook compara la evolución temporal de la polarización en cinco temas políticos durante las elecciones parlamentarias finlandesas de 2019 y 2023. El análisis incluye redes agregadas de elite (políticos, periodistas, influencers) y masa (usuarios generales).



### SyntheticData.ipynb

**Experimento 5: Validación con Redes Sintéticas**

Este notebook valida la premisa fundamental del método: la dimensión de embedding depende de la complejidad estructural, no del tamaño de la red. Se generan redes sintéticas que preservan diferentes niveles de estructura topológica mediante tres niveles de aleatorización.


</div>
