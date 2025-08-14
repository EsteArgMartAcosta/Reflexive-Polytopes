# 🌓Politopos Reflexivos🌖
<span style="font-size: 24px;"></span>
_____________________________

<div align="justify">
Este repositorio contiene los códigos y materiales desarrollados en el marco de la investigación sobre:  
<ul>
  <li><strong>Politopos reflexivos</strong> — estudio estructural, clasificación parcial y análisis de sus invariantes combinatorios y métricos.</li>
  <li><strong>Grafos completos <em>k</em>-partitos</strong> — construcción, propiedades y su relación con politopos asociados (como politopos de corte y politopos de permutaciones).</li>
  <li><strong>Exploración de nuevos politopos reflexivos</strong> — identificación y caracterización de familias previamente no documentadas, así como búsqueda computacional asistida por software especializado.</li>
  <li><strong>Interacciones con otras áreas</strong> — conexiones con teoría de Ehrhart, geometría toroidal y problemas de optimización combinatoria.</li>
</ul>
</div>


<p align="center">
  <img src="https://nedbatchelder.com/pix/jenn-polytope.jpg" alt="Visualización de un poliedro relacionado con la teoría de Ehrhart" width="300">
</p>



# 🎖️ Tabla de Contenido 🎖️
<span style="font-size: 24px;"></span>
_____________________________
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ee/Zome-like.png/480px-Zome-like.png" alt="Imagen Zome-like"width="280">
</p>



1. [Construcción Gráficos](#construccion-graficos)
2. [Envolvente Convexa](#envolvente-convexa)
3. [Triangulaciones](#triangulaciones-algoritmos)
4. [Teoría de Ehrhart en SageMath](#teoria-ehrhart-sagemath)
5. [Topología Algebraica (Cohomología de Rham)](#topologia-algebraica)
6. [Geometría Diferencial](#geometria-diferencial)
7. [Funciones Zeta](#funciones-zeta)
8. [Grafos y Politopos](#Grafos-Politopos)



# 🥷🚨 REQUERIMIENTOS DE EJECUCIÓN 🚨🥷
<span style="font-size: 24px;"></span>
____________________________________

<p align="center">
  <img src="https://images.zapnito.com/cdn-cgi/image/metadata=copyright,format=auto,quality=95,fit=scale-down/https://images.zapnito.com/users/717496/posters/e2e24f08-ec2c-4e55-ae2b-f2e86d55051e_large.png" alt="Nueva imagen relacionada" width="200">
</p>


<div align="justify">
Todos los códigos de este repositorio han sido desarrollados en Google Colab para facilitar su ejecución y visualización.  
Cada archivo está vinculado a este repositorio de GitHub, por lo que se puede abrir y correr los notebooks directamente en Colab sin necesidad de instalaciones locales.
</div>



**Para ejecutarlos:**

- Haga clic en el enlace de cada notebook o súbalo a su Google Drive.
- Asegúrese de tener una cuenta de Google activa para usar Google Colab.

> **Importante:** Los notebooks de la carpeta Teoría de Ehrhart en SageMath requieren el uso de SageMath.  
> Google Colab no incluye SageMath por defecto, por lo que debe instalarse manualmente.

> **Instalación en Colab:**  
> Para ejecutar SageMath en Google Colab, puede incluir la siguiente celda al comienzo del notebook.  
> Tenga en cuenta que esta instalación puede tardar varios minutos y no está oficialmente soportada por Google Colab.

```jsx
!sudo apt update -y
!sudo apt install -y sagemath
```

> Alternativamente, pueden ejecutarse en un entorno local que tenga SageMath instalado, o utilizar plataformas como CoCalc que ofrecen soporte directo para Sage.

> **Nota:** Si prefiere, también puede descargar los notebooks y ejecutarlos en su entorno local compatible con Jupyter.
