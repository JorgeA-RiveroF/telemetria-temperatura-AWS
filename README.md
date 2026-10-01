# Sistema de Telemetría IoT con AWS IoT Core y SageMaker
¿De qué se trata el proyecto?
Este proyecto es un prototipo funcional de Inteligencia Artificial de las Cosas (AIoT) de extremo a extremo. Consiste en capturar la temperatura ambiental utilizando un microcontrolador económico ESP32 con un sensor físico, transmitir esos datos de forma segura a la nube en tiempo real y procesarlos mediante modelos predictivos. El objetivo principal es documentar todo el flujo arquitectónico para crear contenido técnico y educativo accesible para la comunidad de AWS.


## Herramientas a utilizar
El ecosistema tecnológico está dividido en hardware y servicios en la nube de AWS:
Hardware: Microcontrolador ESP32 y un sensor de temperatura (DHT11/DHT22 o DS18B20)/potenciómetro.
Conectividad: Protocolo MQTT cifrado mediante certificados X.509.
Ingesta de Datos: AWS IoT Core.
Almacenamiento: Reglas de AWS IoT para depositar los datos crudos en Amazon S3.
Inteligencia Artificial: Amazon SageMaker para la detección de anomalías y predicción de tendencias de temperatura.


## Presupuesto Estimado
El proyecto está diseñado bajo la filosofía de bajo costo, ideal para desarrolladores y estudiantes:
Hardware: ~$5.00 a $10.00 USD (Costo único del ESP32 y el sensor).
Infraestructura AWS: $0.00 USD (Totalmente cubierto por la Capa Gratuita de AWS).


## Valor Entregado
Educación Práctica: Rompe la barrera entre el hardware y el software, demostrando que implementar AIoT no requiere infraestructura costosa.
Patrón de Arquitectura Reutilizable: Proporciona una plantilla base y código limpio que cualquier desarrollador puede replicar para monitorear otras variables (humedad, presión, vibración).
Migración Tecnológica: Enseña a la comunidad a utilizar Amazon SageMaker como la alternativa moderna y estratégica de largo plazo para la detección de anomalías en series temporales.
