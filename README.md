# Dev-Log-17-Write-Ups

Repositorio personal de **informes técnicos (write-ups)** derivados de
la resolución de máquinas deliberadamente vulnerables.

El objetivo de este repositorio es:

-   Documentar de forma estructurada procesos de **análisis, explotación
    y post-explotación**.
-   Demostrar metodología, capacidad de documentación técnica y
    pensamiento ofensivo/defensivo.

------------------------------------------------------------------------

## 🎯 Objetivo Profesional

Este repositorio forma parte de mi transición profesional hacia el
sector de la **ciberseguridad**.

Cada informe está redactado siguiendo una estructura formal similar a la
utilizada en entornos profesionales.

------------------------------------------------------------------------

## 🧠 Metodología de Trabajo

Las máquinas se abordan siguiendo un enfoque sistemático:

1.  **Reconocimiento**
    -   Enumeración de servicios
    -   Identificación de versiones
    -   Fingerprinting
2.  **Análisis de vulnerabilidades**
    -   Investigación de exploits públicos
    -   Análisis manual de superficie de ataque
3.  **Explotación**
    -   Obtención de acceso inicial
    -   Escalada de privilegios
4.  **Post-explotación**
    -   Persistencia (si aplica)
    -   Enumeración interna
    -   Identificación de riesgos reales
5.  **Informe técnico**
    -   Redacción estructurada
    -   Evidencias documentadas
    -   Evaluación de impacto

------------------------------------------------------------------------

## 📂 Estructura del Repositorio

Cada máquina se encuentra en su propio repositorio:

    /Nombre-de-la-máquina
    │
    ├── img/                      # Evidencias (capturas de pantalla)
    ├── Informe nombre.md         # Versión en Markdown para lectura rápida
    └── Informe nombre.pdf        # Versión en PDF

Ejemplo actual:

    00. Kioptrix L2/
    │
    ├── img/
    ├── Informe kioptrix 2.md
    └── Informe kioptrix 2.pdf

------------------------------------------------------------------------

## 🧪 Máquinas Documentadas

### 1. Kioptrix Level 2

-   Tipo: Máquina vulnerable clásica
-   Enfoque: Enumeración de servicios y explotación web
-   Objetivo: Obtención de privilegios root
-   Informe disponible en `.md` y `.pdf`

*(El repositorio se irá ampliando progresivamente con nuevas máquinas.)*

------------------------------------------------------------------------

## 🛠️ Herramientas Frecuentemente Utilizadas

-   Nmap\
-   Netcat\
-   Burp Suite\
-   Gobuster\
-   Hydra\
-   LinPEAS\
-   Metasploit

*(Las herramientas utilizadas se detallan en cada informe junto con el
razonamiento técnico.)*

------------------------------------------------------------------------

## 📄 Sobre los Informes

Cada documento incluye:

-   Ámbito y alcance
-   Metodología
-   Hallazgos técnicos
-   Evidencias
-   Evaluación de impacto
-   Conclusiones
-   Recomendaciones de mitigación

El objetivo no es solo "resolver la máquina", sino **simular un
entregable profesional real, actuando de la manera más cercana posible
a un entorno profesional.**.

------------------------------------------------------------------------

## ⚖️ Disclaimer

Las máquinas documentadas son entornos **controlados y deliberadamente
vulnerables** diseñados para el aprendizaje.\
No se realizan pruebas sobre sistemas reales sin autorización explícita.

------------------------------------------------------------------------

## 📬 Contacto

Estoy abierto a oportunidades junior en el sector de la ciberseguridad.

Si deseas comentar algún informe o colaborar en proyectos relacionados,
puedes contactarme a través de md.arturo@gmail.com
