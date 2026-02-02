# 🧮 Guía de Usuario - Calculadora Web

**Versión:** 1.0  
**Fecha:** 02 de febrero de 2026

---

## 📋 Introducción

Esta calculadora web es una aplicación interactiva desarrollada con HTML, CSS y JavaScript que te permite realizar operaciones matemáticas básicas directamente desde tu navegador. No requiere instalación de software adicional ni conexión a internet una vez cargada.

## ✨ Características Principales

- **Operaciones matemáticas básicas**: suma, resta, multiplicación y división
- **Interfaz intuitiva**: diseño visual moderno y fácil de usar
- **Soporte de teclado**: puedes usar tanto el ratón como tu teclado
- **Pantalla digital**: muestra tus operaciones en tiempo real
- **Botón de borrado**: corrige errores fácilmente

---

## 🎨 Componentes de la Calculadora

### 📺 Pantalla
La pantalla muestra los números que introduces y el resultado de tus operaciones. Tiene un fondo oscuro con números en blanco para facilitar la lectura.

### 🔢 Botones Numéricos
Los números del 0 al 9 te permiten introducir valores. El botón "0" es más ancho para mayor comodidad.

### ➗ Botones de Operadores
- **+** Suma
- **-** Resta
- **×** Multiplicación
- **/** División

### 🔧 Botones de Control
- **C** (Clear): Limpia toda la pantalla y reinicia la calculadora
- **←** (Backspace): Borra el último dígito introducido
- **=** (Igual): Calcula y muestra el resultado de la operación
- **.** (Punto decimal): Permite introducir números decimales

---

## 🎯 Cómo Usar la Calculadora

### Con el Ratón 🖱️

1. **Introduce el primer número** haciendo clic en los botones numéricos
2. **Selecciona una operación** (+, -, ×, /)
3. **Introduce el segundo número**
4. **Presiona el botón "="** para ver el resultado

### Con el Teclado ⌨️

Puedes usar las siguientes teclas:

- **Números 0-9**: Introducir dígitos
- **Punto (.)**: Introducir decimales
- **+, -, *, /**: Operadores matemáticos
- **Enter o =**: Calcular resultado
- **Escape (Esc)**: Limpiar todo
- **Backspace**: Borrar último carácter

---

## 🔍 Explicación de las Funciones

### 🔢 agregarNumero()
Esta función se encarga de añadir números a la pantalla cuando haces clic en un botón numérico. Si acabas de obtener un resultado y presionas un número, comenzará una nueva operación.

### ➕ agregarOperador()
Añade operadores matemáticos a tu cálculo. Si intentas añadir dos operadores seguidos, reemplazará el anterior por el nuevo.

### 🧮 calcular()
Procesa la operación matemática completa y muestra el resultado en la pantalla. Si hay algún error en la operación, mostrará "Error".

### 🗑️ limpiar()
Borra completamente la pantalla y reinicia la calculadora a su estado inicial (mostrando "0").

### ⬅️ borrar()
Elimina el último carácter introducido. Si solo queda un carácter, lo reemplaza por "0".

### 📺 actualizarPantalla()
Refresca lo que se muestra en la pantalla cada vez que introduces un número o realizas una operación.

---

## 💡 Ejemplos de Uso

### Ejemplo 1: Suma Simple
1. Presiona **5**
2. Presiona **+**
3. Presiona **3**
4. Presiona **=**
5. Resultado: **8**

### Ejemplo 2: Operación con Decimales
1. Presiona **7**
2. Presiona **.**
3. Presiona **5**
4. Presiona **×**
5. Presiona **2**
6. Presiona **=**
7. Resultado: **15**

### Ejemplo 3: Corregir un Error
1. Presiona **9**
2. Presiona **8** (te equivocaste)
3. Presiona **←** (borrar)
4. Presiona **3**
5. Presiona **+**
6. Presiona **7**
7. Presiona **=**
8. Resultado: **100**

---

## ⚠️ Notas Importantes

- 🚫 **No dividas por cero**: La calculadora mostrará "Error"
- 📏 **Números muy largos**: Pueden salirse de la pantalla
- 🔄 **Después de "="**: Al introducir un nuevo número, comenzará una operación nueva
- ✏️ **Un solo punto decimal**: Solo puedes usar un punto por número

---

## 🎓 Para Estudiantes

Esta calculadora es un excelente proyecto para aprender:

- **HTML**: Estructura de la página web
- **CSS**: Diseño y estilos visuales
- **JavaScript**: Lógica y funcionalidad interactiva
- **Eventos**: Cómo responder a clics y pulsaciones de teclado
- **DOM**: Manipulación de elementos en la página

### 📚 Conceptos Clave que Aprenderás

1. **Grid Layout**: Organización de botones en una cuadrícula
2. **Event Listeners**: Captura de eventos de usuario
3. **Funciones**: Reutilización de código
4. **Condicionales**: Toma de decisiones en el código
5. **Manipulación de strings**: Trabajo con texto y números

---

## 🚀 Mejoras Futuras Sugeridas

Para practicar, podrías añadir:

- ✅ Historial de operaciones
- ✅ Operaciones científicas (raíz cuadrada, potencias)
- ✅ Soporte para paréntesis
- ✅ Modo oscuro/claro
- ✅ Guardado de resultados
- ✅ Calculadora de porcentajes

---

## 📞 Soporte

Si encuentras algún problema o error:

1. Presiona el botón **C** para reiniciar
2. Recarga la página en tu navegador
3. Verifica que estés usando un navegador moderno

---

**¡Disfruta calculando! 🎉**

#Tareas pendientes:
- [x] Añadir funciones de memoria
- [ ] Incluir conversión de binario a hex
- [ ] Añadir pin de usuario

#Imagen desde una URL:
![foto](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Felectrowizard.net%2Fwp-content%2Fimages%2Ffree-edqa-6502-Mosfet-Datasheet.jpg&f=1&nofb=1&ipt=94a08338aee9edb64ca74553614931530b0a8c2cb925b0c62d90f5e7403d5b5c)
