# Calidad de Software
# Autor: Dario Guayasamin
Este repositorio está orientado a la materia de Calidad de Software y tiene como objetivo reforzar conceptos básicos sobre la construcción, validación y mejora de software.

## ¿Qué es la calidad de software?

La calidad de software se refiere a qué tan bien un sistema cumple con los requisitos funcionales y no funcionales, además de ofrecer una experiencia confiable, mantenible y segura para el usuario.

Algunos aspectos clave son:

- Correctitud: que el software haga lo que debe hacer.
- Confiabilidad: que funcione de manera estable.
- Mantenibilidad: que sea fácil de modificar y evolucionar.
- Usabilidad: que sea fácil de usar.
- Rendimiento: que responda de forma eficiente.
- Seguridad: que proteja la información y evite fallos críticos.

## Requisitos y validación

Un requisito define lo que debe hacer el sistema. Cuando se valida un software, se comprueba que cumple con esos requisitos mediante diversas técnicas de prueba.

## Pruebas de software

Las pruebas son actividades fundamentales para asegurar que el software funcione correctamente y que los cambios no introduzcan errores.

### Pruebas unitarias

Las pruebas unitarias verifican el comportamiento de funciones, métodos o módulos de forma aislada.

Objetivos:

- Validar lógica de negocio pequeña.
- Detectar errores tempranamente.
- Facilitar la refactorización.

Ejemplo de enfoque:

- Entrada esperada.
- Salida esperada.
- Verificación de casos válidos e inválidos.

### Pruebas end-to-end (E2E)

Las pruebas E2E validan el sistema completo desde la perspectiva del usuario, simulando flujos reales de uso.

Objetivos:

- Comprobar la integración entre módulos.
- Verificar escenarios reales de negocio.
- Confirmar que la aplicación funciona correctamente en conjunto.

Ejemplo de flujo:

- Iniciar la aplicación.
- Ingresar datos.
- Ejecutar una acción.
- Validar resultados visibles en la interfaz o en el sistema.

## Diferencia entre pruebas unitarias y E2E

- Pruebas unitarias: validan partes pequeñas y aisladas del código.
- Pruebas E2E: validan el producto completo con interacción real o simulada del usuario.

Ambas son importantes y complementarias: las unitarias detectan errores rápidos y localizados, mientras que las E2E aseguran que el sistema funciona en conjunto.

## Buenas prácticas

- Escribir pruebas claras y mantenibles.
- Probar casos positivos y negativos.
- Ejecutar pruebas de forma automática.
- Mantener una cobertura razonable.
- Revisar fallas antes de integrar cambios.

## Objetivo del curso

El propósito principal de esta materia es comprender que la calidad no es solo una característica final, sino un proceso continuo que incluye análisis, diseño, pruebas, revisión y mejora constante.

---

Este README sirve como punto de partida para documentar conceptos básicos y futuras actividades del repositorio relacionadas con la calidad de software.
