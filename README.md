# UATRE — Entorno de trabajo de ejemplo

> Este README es una demostración. La descripción, las tecnologías y la estructura propuestas son ficticias; no representan funcionalidades implementadas ni decisiones oficiales del proyecto UATRE.

## Descripción

Este repositorio imagina un entorno de desarrollo colaborativo para un sistema web de gestión de personal eventual. Su propósito es reunir código, documentación y herramientas que faciliten el trabajo entre Gabriel y un asistente de programación.

La aplicación de ejemplo permitiría registrar trabajadores y empresas, consultar asistencia y organizar pedidos de personal desde un panel web.

## Tecnologías propuestas para la demostración

| Área | Tecnología |
|---|---|
| Interfaz web | React y Vite |
| Servidor | Node.js y Express |
| Base de datos | PostgreSQL |
| Acceso a datos | Prisma |
| Control de versiones | Git y GitHub |
| Editor | Visual Studio Code |

Estas herramientas se presentan como ejemplo y todavía no están configuradas en este repositorio.

## Organización imaginada

```text
uatre/
├── frontend/        # Interfaz de usuario
├── backend/         # API y lógica de aplicación
├── docs/            # Requisitos y documentación
├── tests/           # Pruebas del sistema
├── .env.example     # Variables de entorno sin secretos
└── README.md        # Presentación del repositorio
```

Esta estructura es una propuesta ilustrativa: crear este README no crea esas carpetas ni una aplicación ejecutable.

## Cómo trabajaríamos

1. Definir una tarea concreta y revisar los archivos existentes.
2. Aclarar las reglas del negocio que falten antes de implementarlas.
3. Crear o modificar el código y la documentación necesarios.
4. Ejecutar las verificaciones disponibles y explicar sus resultados.
5. Registrar el cambio en un commit con un mensaje claro.
6. Revisar el resultado en GitHub y continuar con la siguiente tarea.

## Qué puede hacer el asistente

Con el acceso y las herramientas disponibles, el asistente puede ayudar a:

- Leer archivos del repositorio y explicar su contenido.
- Crear y actualizar documentación, como este README.
- Proponer e implementar cambios de código dentro del alcance solicitado.
- Revisar errores y sugerir correcciones.
- Ejecutar pruebas cuando exista un entorno preparado para ello.
- Crear commits y colaborar mediante ramas y pull requests.

Cada tarea debe informar qué cambió, qué se verificó y qué queda pendiente. Una descripción de una función no significa que esa función ya esté implementada.

## Ejemplos de pedidos

- «Explicame cómo está organizado este repositorio».
- «Creá un endpoint de ejemplo y explicame cada parte».
- «Revisá este error y corregilo».
- «Actualizá la documentación para reflejar el cambio».
- «Prepará una rama con una mejora para que pueda revisarla».

## Convenciones de ejemplo

- Usar nombres descriptivos para archivos, variables y funciones.
- Mantener las credenciales fuera del repositorio.
- Documentar cómo configurar y ejecutar la aplicación cuando exista.
- Realizar commits pequeños con un propósito concreto.
- Usar mensajes como `docs: actualizar guía de instalación` o `feat: agregar consulta de trabajadores`.

## Estado actual

El repositorio contiene este README de demostración. Todavía no incluye una aplicación, dependencias, configuración ni comandos de instalación.

---

Ejemplo creado para Gabriel Silva como demostración de escritura en GitHub.
