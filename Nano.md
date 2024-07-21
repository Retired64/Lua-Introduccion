### Guía Detallada de `nano` en Termux

#### **1. Introducción a `nano`**

`nano` es un editor de texto simple y fácil de usar que se ejecuta en la terminal. Es ideal para usuarios que necesitan editar archivos de texto desde la línea de comandos.

#### **2. Instalación de `nano`**

Para instalar `nano` en Termux, usa el siguiente comando:
```sh
pkg install nano
```

#### **3. Creación y Edición de Archivos**

Para crear o editar un archivo con `nano`, usa el comando:
```sh
nano nombre_del_archivo
```
Ejemplo:
```sh
nano mi_archivo.txt
```

#### **4. Navegación Básica**

- **Teclas de flecha**: Usadas para mover el cursor alrededor del texto.
- **Inicio y Fin**: Usar `Ctrl + A` para ir al inicio de la línea y `Ctrl + E` para ir al final de la línea.

#### **5. Edición de Texto**

- **Escribir texto**: Simplemente comienza a escribir donde esté el cursor.
- **Borrar caracteres**: Usa la tecla `Backspace` para borrar el carácter antes del cursor y `Ctrl + D` para borrar el carácter bajo el cursor.

#### **6. Guardar Archivos**

Hay varias formas de guardar un archivo en `nano`:

- **Guardar Rápidamente**:
  - Presiona `Ctrl + O`, luego `Enter` para confirmar el nombre del archivo y guardar.
  
- **Guardar con Confirmación**:
  - Presiona `Ctrl + O`, escribe el nombre del archivo si deseas cambiarlo, luego presiona `Enter`.
  
- **Guardar y Salir**:
  - Presiona `Ctrl + X`, y si tienes cambios sin guardar, `nano` te preguntará si deseas guardar. Presiona `Y` para confirmar, luego `Enter` para guardar con el nombre actual.

#### **7. Salir de `nano`**

Para salir de `nano`:
- Presiona `Ctrl + X`.

#### **8. Borrar Archivos**

Para borrar un archivo, utiliza el comando `rm`:
```sh
rm nombre_del_archivo
```
Ejemplo:
```sh
rm mi_archivo.txt
```

#### **9. Modificación de Líneas**

- **Ir a una Línea Específica**:
  - Presiona `Ctrl + _` (Ctrl más la tecla de subrayado), escribe el número de la línea, y luego `Enter`.

- **Cortar una Línea**:
  - Mueve el cursor a la línea que deseas cortar y presiona `Ctrl + K`.

- **Pegar una Línea**:
  - Mueve el cursor a donde deseas pegar la línea cortada y presiona `Ctrl + U`.

- **Copiar una Línea**:
  - Mueve el cursor a la línea que deseas copiar, presiona `Alt + 6`, luego mueve el cursor a donde deseas pegar y presiona `Ctrl + U`.

#### **10. Búsqueda y Reemplazo**

- **Buscar Texto**:
  - Presiona `Ctrl + W`, escribe el texto que deseas buscar, y presiona `Enter`.

- **Reemplazar Texto**:
  - Presiona `Ctrl + \`, escribe el texto a reemplazar, presiona `Enter`, escribe el texto nuevo, y presiona `Enter`.

#### **11. Deshacer y Rehacer**

- **Deshacer**:
  - Presiona `Ctrl + _` (Ctrl más el guion bajo), luego `U`.

- **Rehacer**:
  - Presiona `Ctrl + _` (Ctrl más el guion bajo), luego `E`.

#### **12. Ajuste de Texto**

- **Justificación del Texto**:
  - Presiona `Ctrl + J` para justificar el párrafo donde está el cursor.

#### **13. Ver la Ayuda**

Para ver la ayuda en `nano`, presiona `Ctrl + G`. Esto mostrará una lista de comandos y atajos disponibles.

#### **Resumen de Atajos Clave en `nano`**

- **Guardar archivo**: `Ctrl + O`, luego `Enter`.
- **Guardar y salir**: `Ctrl + X`, luego `Y` y `Enter`.
- **Salir sin guardar**: `Ctrl + X`, luego `N`.
- **Cortar línea**: `Ctrl + K`.
- **Pegar línea**: `Ctrl + U`.
- **Buscar texto**: `Ctrl + W`.
- **Reemplazar texto**: `Ctrl + \`.
- **Ir a una línea específica**: `Ctrl + _`, ingresa el número de línea, `Enter`.
- **Deshacer**: `Ctrl + _`, luego `U`.
- **Rehacer**: `Ctrl + _`, luego `E`.

Esta guía cubre los aspectos esenciales y detallados de cómo usar `nano` en Termux, permitiéndote manejar archivos de texto de manera eficiente desde la terminal
