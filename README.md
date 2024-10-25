# SMOB_24 - Innovación para Ciudades Inteligentes

Bienvenido a **SMOB_24**, la solución creada para el desafío **CoSiam Hackday**. Nuestro equipo ha desarrollado una propuesta avanzada para transformar el espacio urbano a través de la tecnología y mejorar la calidad de vida en las ciudades.

## 🌟 Solución Destacada

**SMOB_24** es una plataforma diseñada para proporcionar datos, análisis y visualizaciones en tiempo real, permitiendo a los organismos de la ciudad y a sus habitantes tomar decisiones más informadas. Con un enfoque centrado en **eficiencia urbana, sostenibilidad y tecnología avanzada**, SMOB_24 se convierte en una herramienta indispensable para cualquier ciudad que aspire a convertirse en una **ciudad inteligente**.

## 🎥 Presentación en Video
🔽🔽🔽

Explora nuestra solución en detalle a través de la siguiente presentación. Haz clic en la imagen para ver el video:

[![Ver el video](https://github.com/Hvnt3rK3ys/SMOB_24/blob/main/CoSiam.png)](https://github.com/Hvnt3rK3ys/SMOB_24/blob/main/SMOB.mp4)


🔼🔼🔼

## 🚀 Funcionalidades Clave

- **Análisis de datos urbanos en tiempo real**  
  Nuestra plataforma recoge y procesa datos en tiempo real para ofrecer una visión completa y actualizada de los fenómenos urbanos.

- **Visualización avanzada y paneles personalizables**  
  Los paneles interactivos permiten a los usuarios ver y analizar datos con facilidad, facilitando la toma de decisiones rápidas y efectivas.

- **Compatibilidad con Open Data y API’s públicas**  
  Aprovechamos datos abiertos y APIs públicas para enriquecer nuestra plataforma y ofrecer información integral sin sobrecargar la infraestructura.

- **Optimización de recursos y reducción de huella ambiental**  
  Herramientas de análisis y simulación ayudan a reducir el impacto ambiental mediante un uso más eficiente de los recursos urbanos.

- **Actualización Periódica de Datos**  
  Los datos de las APIs se actualizan periódicamente (cada 3 meses) y se integran en la plataforma de manera automática utilizando un flujo de trabajo en AWS.

## 🧑‍💻 Nuestro Equipo

La experiencia multidisciplinaria de nuestro equipo hace posible esta innovadora solución:

- **Naren Rojas**  
  Ingeniero de Sistemas, especializado en tecnología y desarrollo urbano  
  *Fundación Universitaria Konrad Lorenz*

- **Yeferson Linares**  
  Ingeniero de Sistemas, experto en gestión de datos y visualización  
  *Fundación Universitaria Konrad Lorenz*

- **Manuel Parra**  
  Matemático, enfocado en modelado predictivo y análisis de datos complejos  
  *Fundación Universitaria Konrad Lorenz*

## 🌐 ¿Por Qué SMOB_24?

**SMOB_24** no es solo una plataforma; es un paso hacia un futuro más inteligente y sostenible. Con nuestra tecnología, ayudamos a las ciudades a evolucionar, a anticiparse a problemas y a ofrecer a sus ciudadanos un entorno más seguro y conectado.

## 🚀 Implementación de Actualización Periódica de Datos

### Arquitectura Propuesta

1. **Cron Job con AWS Lambda**:
   - **AWS Lambda**: Utiliza funciones Lambda para programar la ejecución periódica de tareas.
   - **CloudWatch Events**: Configura reglas de CloudWatch Events para desencadenar la función Lambda en intervalos regulares (por ejemplo, cada 3 meses).

2. **Consumir Datos de API**:
   - **HTTP Requests**: La función Lambda realizará solicitudes HTTP a las APIs para obtener los datos actualizados.

3. **Procesamiento y Transformación de Datos**:
   - **AWS Glue**: Utiliza AWS Glue para transformar y limpiar los datos antes de almacenarlos.

4. **Almacenamiento de Datos en Tiempo Real**:
   - **Amazon Kinesis**: Utiliza Kinesis Data Streams para ingestar los datos en tiempo real.
   - **Amazon S3**: Almacena los datos procesados en S3 para su posterior análisis.

5. **Visualización y Análisis**:
   - **Amazon QuickSight**: Utiliza QuickSight para crear dashboards y visualizaciones en tiempo real.
   - **Amazon Elasticsearch**: Utiliza Elasticsearch para búsquedas y análisis de logs en tiempo real.


