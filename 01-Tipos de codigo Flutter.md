# TIPOS DE CODIGO FLUTTER

- UI
  - El código que dibuja lo que el usuario ve en la pantalla
- State
  - El código que decide que dibujar en la pantalla
- Business
  - El código que une la entrada del usuario para completar una tarea
- Application
  - El código que hace el trabajo real, como hacer una solicitud http o escribir en BBDD

## Marco de preguntas de 3 pasos

1. ¿El archivo con mi código de interfaz de usuario también contiene mi código de estado?
  - Si la respuesta es si, separamos el código de interfaz de usuario del resto del código
2. ¿El archivo que contiene mi código de estado tiene una lógica empresarial o código de aplicación?
  - Si la respuesta es si, empiezo por separar el código de estado de mi lógica empresarial
3. ¿El archivo que contiene mi lógica empresarial tiene algún código de aplicación?
  - Si la respuesta es si, identifico y separa el código de aplicación de la lógica empresarial

Y un cuarto paso sería mantener las dependencias sueltas.

## Diferencia entre principios de programación y patrones (o reglas) de diseño

Los principios de programación guian el pensamiento mientras que las reglas dictan la ejecución.

El principio principal es que cada parte de mi software debe tener solo una razón para cambiar. Este es el principio de responsabilidad única (la S en los principios SOLID)
