# Registro de Prompts

En este archivo debés documentar los prompts que usaste con herramientas de IA
(GitHub Copilot, ChatGPT, etc.) durante el desarrollo del TP.

**¿Por qué?** Queremos que aprendas a trabajar con IA de forma reflexiva:
que sepas qué le pediste, qué obtuviste, y si tuviste que corregirlo.

---

## Formato para cada entrada

```
### [Número] - [Módulo]

**Herramienta**: GitHub Copilot / ChatGPT / otra

**Prompt usado**:
> Escribí acá exactamente lo que le pediste a la IA

**Resultado obtenido**:
Describí brevemente qué generó (código, explicación, etc.)

**¿Lo usaste tal cual o lo modificaste?**
Explicá qué cambios hiciste y por qué (o por qué no cambiaste nada).
```

---

## Mis prompts

### 1 - variables.py

**Herramienta**: 
>##Gemini 
**Prompt usado**:
> ## variables.py (Patrón: Receta)
Prompt:
> Actuá como tutor de Python 3.13. Dame una receta paso a paso para completar estas 5 funciones con su nombre de funcion y su tipo de dato, de entrada y salida.
> 1) crear_saludo(nombre) -> devuelve "Hola, {nombre}!"
> 2) suma_enteros(a, b) -> devuelve la suma.
> 3) es_mayor_de_edad(edad) -> devuelve True si es >= 18.
> 4) tipo_de_dato(valor) -> devuelve el nombre del tipo (como string).
> 5) convertir_a_float(valor) -> convierte un string a número decimal.
> Mostrame el código limpio para pegar en mi archivo.

**Resultado obtenido**:

>La IA proporciono el código de las funciones permitiendo que los pytest -v funcionen

**¿Lo usaste tal cual o lo modificaste?**
Use el mismo tipo de PROMPT, pero no el que estaba en el github.

---

### 2 - condicionales.py (interaccion invertida)

**Herramienta**: 
>#Gemini
**Prompt usado**:

> Quiero implementar cuatro funciones en Python: `clasificar_numero`, `mayor_de_tres`, `clasificar_nota` y `es_bisiesto`
Antes de proporcionarme el código, actuá como un verificador y haceme 3 preguntas clave sobre las reglas de negocio, el orden de las condiciones y los casos borde (como el año bisiesto o las notas) para confirmar que entiendo la lógica. Una vez que responda, generá el código final.

Sobre las notas (clasificar_nota): Si un alumno saca un 9.5, ¿qué categoría debería devolver el programa? ¿Importa el orden en que pongamos los if (por ejemplo, preguntar primero si es mayor a 6 o primero si es mayor a 9)?
>sobresaliente. si importa.
Sobre el número mayor (mayor_de_tres): ¿Qué debería pasar si los tres números son iguales (ejemplo: 5, 5, 5)?
>Deberia devolver el numero y listo.
Sobre el año bisiesto (es_bisiesto): Según la regla del PDF, el año 2100 es divisible por 4 y por 100, pero NO por 400. ¿Entonces es bisiesto o no?
>Nop

**Resultado obtenido**:
La IA realizó preguntas de validación sobre el orden de los condicionales, el manejo de números iguales y la lógica de años bisiestos. Tras aclarar que el orden de las notas debe ser descendente y que la función de mayor debe devolver solo el entero, se procedió a implementar el código.

**¿Lo usaste tal cual o lo modificaste?**
Use el mismo tipo de PROMPT, pero no el que estaba en el github.

---

### 3 - listas.py

**Herramienta**: 

**Prompt usado**:
> 

**Resultado obtenido**:


**¿Lo usaste tal cual o lo modificaste?**


---

### 4 - diccionarios.py

**Herramienta**: 

**Prompt usado**:
> 

**Resultado obtenido**:


**¿Lo usaste tal cual o lo modificaste?**


---

### 5 - loops.py

**Herramienta**: 

**Prompt usado**:
> 

**Resultado obtenido**:


**¿Lo usaste tal cual o lo modificaste?**


---

### 6 - funciones.py

**Herramienta**: 

**Prompt usado**:
> 

**Resultado obtenido**:


**¿Lo usaste tal cual o lo modificaste?**


---

### 7 - operaciones.py

**Herramienta**: 

**Prompt usado**:
> 

**Resultado obtenido**:


**¿Lo usaste tal cual o lo modificaste?**


---

## Reflexión final

Respondé brevemente (3-5 oraciones):

- ¿Qué aprendiste sobre cómo formular buenos prompts?
- ¿En qué casos la IA fue útil y en cuáles no?
- ¿Qué harías diferente la próxima vez?
