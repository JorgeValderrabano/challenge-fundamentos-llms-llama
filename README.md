# Challenge: Fundamentos de LLMs y Arquitectura Llama

## Descripción del Proyecto
Este proyecto forma parte del módulo de *Fundamentos de LLMs y Arquitectura de Llama*. Consiste en la integración práctica con modelos de lenguaje a través de la API de Groq para evaluar su desempeño en tareas de atención al cliente y soporte técnico.

## Objetivos Alcanzados
- **Integración Segura:** Autenticación y manejo seguro de llaves de API mediante `Colab Secrets`.
- **Medición de Desempeño:** Registro automatizado del tiempo de respuesta (latencia) por cada consulta.
- **Estructuración de Datos:** Uso de listas y diccionarios en Python para capturar, almacenar y comparar los resultados obtenidos.

## Resultados
- **Pregunta 1:** ¿Cuáles son los horarios de atención y cómo puedo restablecer mi contraseña?
- **Pregunta 2:** ¿Qué pasos debo seguir para solicitar un reembolso de mi compra?
- **Pregunta 3:** ¿Cómo puedo contactar al equipo de soporte técnico en caso de una falla grave?

### Conclusión
El modelo evaluado procesó las tres consultas de soporte técnico con tiempos de respuesta reducidos (promedio ~0.16 segundos), demostrando su idoneidad para automatizar la atención inicial a clientes.

## Tecnologías Utilizadas
- Python 3
- Google Colab
- Groq API (`groq`)
- Modelos Llama 3
