# Lista de Amigos - Sorteo Aleatorio

## Descripción
Este proyecto permite a los usuarios **crear una lista de amigos**, visualizarla en pantalla y **sortear un amigo de manera aleatoria**.  
Está desarrollado con **HTML, CSS y JavaScript**, ideal para aprender conceptos básicos de programación como arreglos, ciclos, funciones y manipulación del DOM.

---

## Funcionalidades

- **Agregar amigos:** Permite ingresar nombres en un campo de texto y añadirlos a la lista. Valida que no esté vacío.  
- **Visualizar lista de amigos:** Muestra todos los amigos agregados en la página, actualizándose cada vez que se añade un nuevo amigo.  
- **Sorteo aleatorio:** Selecciona un amigo al azar usando `Math.random()` y `Math.floor()`.  
- **Limpieza del campo:** El campo de entrada se limpia automáticamente después de agregar un amigo.  

---

## Tecnologías Utilizadas

- **HTML**: Estructura de la página.  
- **CSS**: Estilos básicos y presentación (opcional).  
- **JavaScript**:  
  - Manejo de arrays.  
  - Funciones y ciclos (`for`, `while`).  
  - Validaciones simples.  
  - Manipulación del DOM (`getElementById`, `createElement`, `innerHTML`).  
  - Generación de números aleatorios (`Math.random()`, `Math.floor()`).  

---

## Uso

1. Abrir `index.html` en un navegador web.  
2. Escribir un nombre en el campo de entrada.  
3. Presionar **Agregar** para añadirlo a la lista.  
4. Presionar **Sortear Amigo** para seleccionar un nombre aleatorio.  
5. El resultado aparecerá en pantalla.  

---

## Funciones Principales

```javascript
function agregarAmigo() { ... }   // Añade un amigo al array y actualiza la lista
function actualizarLista() { ... } // Muestra todos los amigos en la lista
function sortearAmigo() { ... }    // Selecciona un amigo aleatoriamente y lo muestra



