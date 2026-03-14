# Docs to PDF Converter | Convertidor de Docs a PDF

[![Java Version](https://img.shields.io/badge/Java-1.7%2B-orange.svg)](https://www.oracle.com/java/technologies/javase-downloads.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 🇺🇸 English Version

### Portfolio Note
> [!NOTE]
> This repository is a **maintained fork** of the original project by [Yeo Kheng Meng](https://github.com/yeokm1/docs-to-pdf-converter). 
> I have adapted and organized this project for my professional portfolio to demonstrate expertise in:
> - Managing legacy Java projects.
> - Documentation and workflow optimization.
> - Practical integration of document conversion tools in enterprise environments.

### Overview
A standalone Java library and command-line tool that converts **DOC, DOCX, PPT, PPTX, and ODT** documents to PDF. It is designed to be lightweight and dependency-free from large suites like LibreOffice.

### Why?
I needed a simple, efficient way to convert Office documents to PDF without the overhead of heavy software or expensive proprietary APIs. This tool combines several open-source libraries into a single, cohesive solution.

### Technologies
- **Java 7+**
- **Maven** for dependency management.
- **Apache POI**: PPT/PPTX processing.
- **docx4j**: DOC processing.
- **xdocreport**: DOCX/ODT conversion.

### Usage
#### Command Line
```bash
java -jar doc-converter.jar -type "type" -input "path" -output "path" -verbose
```
*Example:*
```bash
java -jar doc-converter.jar -input sample.docx -o output.pdf
```

### Caveats
- **DOC**: May have minor paragraph spacing variations.
- **PPT/PPTX**: Converts slides to embedded PNGs within the PDF (ideal for printing).

---

## 🇪🇸 Versión en Español

### Nota de Portafolio
> [!NOTE]
> Este repositorio es un **fork mantenido** del proyecto original de [Yeo Kheng Meng](https://github.com/yeokm1/docs-to-pdf-converter).
> He adaptado y organizado este proyecto para mi portafolio profesional para demostrar habilidades en:
> - Gestión de proyectos Java legados.
> - Optimización de documentación y flujos de trabajo.
> - Integración práctica de herramientas de conversión de documentos en entornos empresariales.

### Descripción General
Una librería Java independiente y herramienta de línea de comandos que convierte documentos **DOC, DOCX, PPT, PPTX y ODT** a PDF. Está diseñada para ser ligera y sin dependencias de suites pesadas como LibreOffice.

### ¿Por qué?
Necesitaba una forma simple y eficiente de convertir documentos de Office a PDF sin la carga de software pesado o APIs propietarias costosas. Esta herramienta combina varias librerías de código abierto en una solución única y cohesiva.

### Tecnologías
- **Java 7+**
- **Maven** para gestión de dependencias.
- **Apache POI**: Procesamiento de PPT/PPTX.
- **docx4j**: Procesamiento de DOC.
- **xdocreport**: Conversión de DOCX/ODT.

### Uso
#### Línea de Comandos
```bash
java -jar doc-converter.jar -type "tipo" -input "ruta" -output "ruta" -verbose
```
*Ejemplo:*
```bash
java -jar doc-converter.jar -input ejemplo.docx -o salida.pdf
```

### Limitaciones Conocidas
- **DOC**: Puede presentar variaciones menores en el espaciado de párrafos.
- **PPT/PPTX**: Convierte las diapositivas en imágenes PNG incrustadas en el PDF (ideal para impresión).

---

## License | Licencia
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
Este proyecto está bajo la **Licencia MIT**. Ver el archivo [LICENSE](LICENSE) para más detalles.
