# ✅ Clase 2: Validación de datos

La **validación de datos** es una técnica clave en la gestión de información digital. Permite **restringir el tipo de datos** que se ingresan en un documento, asegurando precisión y coherencia, especialmente en formularios o archivos compartidos.

---

## 🧠 ¿Por qué es importante?

- **Evita errores humanos** durante el ingreso de datos.
- **Asegura formatos consistentes**, útil en reportes y análisis.
- **Facilita la captura correcta** de información.
- **Permite control total sobre celdas específicas**.

---

## 🛠️ ¿Cómo configurar la validación en Excel?

1. **Selecciona la celda o rango** a validar.
2. Ve a la pestaña **"Datos"**.
3. Haz clic en **"Validación de datos"** dentro de "Herramientas de datos".
4. En la ventana emergente, configura el **tipo de validación** deseado.

---

## 📋 Ejemplos comunes de validación

| Campo              | Tipo de validación                     | Detalle                            |
| ------------------ | -------------------------------------- | ---------------------------------- |
| Nombre del cliente | Cualquier valor con mensaje de entrada | Mensaje: "Ingrese nombre completo" |
| Teléfono           | Longitud específica (10 dígitos)       | Usar fórmula o longitud fija       |
| Fecha de compra    | Menor o igual a la fecha de hoy        | Evita fechas futuras               |
| Tienda             | Número entero entre 1 y 3              | Valida ubicación                   |
| Vendedor           | Lista desplegable de nombres           | Cargada manual o desde otra hoja   |
| Factura requerida  | Fórmula personalizada ("sí" o "no")    | Usar fórmula personalizada         |
| Forma de pago      | Lista basada en otra hoja del libro    | Referencia a celdas externas       |

---

## ✍️ Mensajes personalizados

### 📌 Mensaje de entrada

- Se muestra al seleccionar la celda.
- Ejemplo: "Ingrese el nombre completo del cliente."

### ❌ Mensaje de error

- Se muestra al ingresar un valor inválido.
- Ejemplo: "Formato incorrecto. Ingrese un teléfono de 10 dígitos."

---

## 🔍 Listas y fórmulas en validación

- **Listas**: Definen opciones preestablecidas (ideal para campos como "vendedor" o "forma de pago").
- **Fórmulas personalizadas**: Reglas lógicas específicas.

  **Ejemplo fórmula**:  
  Para permitir solo "sí" o "no":  
  `=O(A1="sí",A1="no")`

---

## 🚀 Opciones avanzadas de validación

| Funcionalidad               | Uso y ventajas                                                            |
| --------------------------- | ------------------------------------------------------------------------- |
| 📌 Circular datos inválidos | Identifica visualmente errores sin bloquear la entrada.                   |
| 🧩 Omitir mensaje de error  | Permite errores sin mostrar advertencias, útil en formularios más libres. |

---

## 📄 Caso práctico: Registro de clientes

En un formulario de registro puedes aplicar validaciones como:

- Teléfono: debe tener 10 dígitos.
- Fecha de compra: no debe ser futura.
- Forma de pago: lista desplegable desde otra hoja.
- Factura: debe ser "sí" o "no".

Esto **mejora la calidad de los registros y reduce errores** de ingreso manual.

## 📌 Infografía: Importancia de la validación de datos

- **Asegura precisión y coherencia en el ingreso de datos**: Previene errores comunes como formatos incorrectos o campos vacíos.

- **Excel permite configurar reglas específicas para cada campo**: Longitud, listas, fechas y fórmulas personalizadas según necesidad.

- **Mensajes de entrada y error guían al usuario en tiempo real**: Mejor experiencia y menos errores.

- **Fórmulas y listas aumentan el control sin complejidad**: Especialmente útil para campos repetitivos o categóricos.

- **Las funciones avanzadas ofrecen revisión sin bloquear el flujo**: Como "Circular datos inválidos" para revisiones visuales.
