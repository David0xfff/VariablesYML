# 🔐 Azure DevOps Pipeline: Uso de Variables y Secretos

Este proyecto demuestra cómo utilizar variables y secretos en un pipeline de Azure DevOps. Se incluyen variables definidas directamente en el archivo YAML y una variable secreta referenciada desde un grupo de variables.

## 📁 Estructura del pipeline

El archivo `azure-pipelines.yml` contiene lo siguiente:

- Activación automática al hacer cambios en la rama `main`.
- Definición de variables visibles y secretas.
- Ejecución de un job que imprime el contenido de las variables (el secreto se enmascara automáticamente).

