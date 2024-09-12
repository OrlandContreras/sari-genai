# sArI

Es una asistente virtual, que está diseñada para proporcionar análisis y respuestas basadas exclusivamente en temas relacionados con las industrias y sectores macroeconómicos de Latinoamérica. El enfoque es hacer análisis de mercados, industrias clave, tendencias económicas, y sectores productivos en países de Latinoamérica como Argentina, Brasil, Chile, México, Colombia, Perú, y otros.

## Características

- **Análisis de Mercados**: Proporciona análisis detallados de mercados específicos en Latinoamérica.
- **Industria Clave**: Ofrece análisis sobre industrias clave en la región.
- **Tendencias Económicas**: Analiza tendencias económicas y su impacto en la región.
- **Sectores Productivos**: Proporciona análisis sobre sectores productivos en Latinoamérica.

## Tecnologías Utilizadas

- **Rust**: Lenguaje de programación utilizado para la implementación de la asistente.
- **AWS Bedrock**: Utilizado para la generación de respuestas y análisis.
- **AWS DynamoDB**: Utilizado para la gestión de datos.
- **Tokio**: Utilizado para la gestión de hilos y concurrencia.
- **Serde**: Utilizado para la serialización y deserialización de datos.

## Prerequisitos

- **Rust**: Se recomienda usar Rust para compilar el proyecto.
- **AWS Credentials**: Se necesitan credenciales de AWS para interactuar con AWS Bedrock y DynamoDB.
- **AWS CLI**: Se necesita la CLI de AWS para configurar las credenciales.
- **AWS Bedrock**: Se necesita tener acceso a AWS Bedrock.
- **AWS DynamoDB**: Se necesita tener acceso a AWS DynamoDB.
- Se debe crear una tabla en DynamoDB con el nombre de `Conversations` y el esquema de la tabla con el siguiente esquema:

| Atributo     | Tipo   |
| ------------ | ------ |
| session_id   | String |
| Conversation | String |

## Ejecución

```bash
cargo run
```
