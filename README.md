# Lab 04

**Estudiante:** Israel Huamán Huamán
**Curso:** Programación en Móviles

## Descripción
Aplicación de carrito de compras construida con Jetpack Compose que integra un formulario de captura de datos y una lista dinámica. Calcula el subtotal, IGV (18%) y total en tiempo real.

## Capturas de Pantalla
<img width="1080" height="2340" alt="Screenshot_20260916-144647_Lab04CarritoTecsup" src="https://github.com/user-attachments/assets/b407cc46-9652-45a7-85ed-a76732390fc5" />
<img width="1080" height="2340" alt="Screenshot_20260916-144631_Lab04CarritoTecsup" src="https://github.com/user-attachments/assets/026bb07d-27f9-4b6b-864d-5a1c5989ea13" />




**a) ¿Por qué usar mutableStateListOf y no una MutableList normal?**
Porque `mutableStateListOf` crea una lista observable, si usamos una lista normal al agregar un producto los datos cambian en memoria pero la interfaz no se entera.

**b) ¿Por qué la lista se declara con val y aún así podemos agregarle elementos?**
Usamos `val` para que la referencia a la lista quede fija en la memoria.
**c) ¿Qué hace weight(1f) en la LazyColumn?**
Le indica a la lista que se expanda para ocupar todo el espacio vertical sobrante disponible
