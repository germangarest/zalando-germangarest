# Clasificación de Prendas con Streamlit

Esta aplicación web, desarrollada con Streamlit, permite clasificar prendas de vestir utilizando un modelo de deep learning entrenado con el dataset Fashion MNIST.

## Características

- Interfaz web intuitiva desarrollada con Streamlit
- Clasificación de 10 tipos diferentes de prendas
- Procesamiento automático de imágenes
- Visualización de resultados en tiempo real
- Containerización con Docker para fácil despliegue

## Categorías de Prendas

La aplicación puede clasificar las siguientes categorías:
- Camiseta/Top
- Pantalón
- Suéter
- Vestido
- Abrigo
- Sandalia
- Camisa
- Zapatilla
- Bolso
- Botas

## Requisitos

- Docker
- Docker Compose

## Cómo ejecutar la aplicación

1. Clona este repositorio:
   ```bash
   git clone <repositorio>
   cd <directorio>
   ```

2. Ejecuta la aplicación con Docker Compose:
   ```bash
   docker-compose up
   ```

3. Abre tu navegador web y accede a:
   ```
   http://localhost:8501
   ```

Para detener la aplicación:
```bash
docker-compose down
```

## Uso

1. Sube una imagen de una prenda de vestir en formato JPG o PNG
2. La aplicación procesará automáticamente la imagen
3. Se mostrará la predicción con la categoría de la prenda

## Modelo

La aplicación utiliza un modelo de deep learning pre-entrenado (`fashion_mnist.keras`) basado en el dataset Fashion MNIST de Zalando.

## Estructura del Proyecto

```
.
├── Dockerfile           # Configuración de la imagen Docker
├── docker-compose.yml   # Configuración de Docker Compose
├── streamlit_app.py     # Aplicación principal
├── requirements.txt     # Dependencias del proyecto
├── fashion_mnist.keras  # Modelo pre-entrenado
└── README.md           # Este archivo
```

## Autor

germangarest