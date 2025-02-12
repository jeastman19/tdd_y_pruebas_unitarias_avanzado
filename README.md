# JavaScript: TDD y pruebas unitarias avanzado


## Estructura

Las pruebas tienen una estructura semántica que ayuda a comprender el flujo del código:

* **Arrenge**: (Organiza), prepara el escenario para la prueba.
* **Act**: (Actúa), ejecuta el código.
* **Assert**: (Valida), verifica que el resultado sea el esperado.
`

## Buenas Practicas

### 5 Preguntas

1. ué se estás probando?
1. ué debería hacer?
1. uál fue el resultado (comportamiento real)?
1. ual era el resultado esperado (comportamiento esperado)?
1. ómo se puede reproducir la prueba?


### Principios DRY & DAMP

#### DRY
Don't Repeat Youself

#### DAMP

Descriptive And Meaningful Phrases.

Títulos descriptivos y significativos.

- **Descriptivo**: Describe el comportamiento del código.
- **Significativo**: Explica el comportamiento del código.
- **Frase**: Describe el comportamiento del código en una sola frase.

Títulos descriptivos y significativos.

### Buenas Prácticas

* No subas código con pruebas fallidas u omitidas.
* Si otras pruebas fallan, revisa y corrige tu código.
* Si aún así fall, localizar el autor.
* Si puedes corregir una prueba, ¡hazlo!.

### Regla de oro

* Nunca omitir las pruebas.


## Paquetes

* jest: para ejecutar las pruebas
* node-notifier: notifica cuando termine las pruebas
