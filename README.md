# Mapa Cerebral — Test de dominancia cerebral (Benziger)

Test web, anónimo y a ciegas, basado en el modelo de dominancia cerebral de **Katherine Benziger**
(los cuatro modos de pensamiento: Basal Izquierdo, Basal Derecho, Frontal Derecho y Frontal Izquierdo).

La persona primero marca frases sin saber qué miden, luego se identifica con 4 descripciones (escala 0–5)
y recién al final descubre su **mapa cerebral** con el puntaje de cada cuadrante.

## Esquema de colores (cuadrantes)

| Cuadrante | Color | Arquetipo |
|---|---|---|
| Frontal Izquierdo | 🔵 Azul | El Estratega |
| Frontal Derecho | 🟡 Amarillo | El Visionario |
| Basal Izquierdo | 🟢 Verde | El Organizador |
| Basal Derecho | 🔴 Rojo | El Conector |

## Puntaje

Cada modo: **frases tildadas (0–15) + escala de identificación (0–5) = máx. 20 por modo**.

## Registro de respuestas (opcional)

Si al completar el test se envían los resultados a una Google Sheet, la configuración está en
`index.html`, en la constante `SHEET_ENDPOINT` (URL del Web App de Google Apps Script).
Si se deja vacía, el test funciona igual pero no registra nada.

Se registra, por persona: fecha, datos demográficos (edad, sexo, educación, ciudad, ocupación),
los 4 puntajes por cuadrante y el modo dominante. **Anónimo** (sin nombre ni email).

> Nota: al desplegarse como página pública, la URL del endpoint queda visible en el código fuente.

## Despliegue

Es una página estática (un solo `index.html`). Se puede publicar con **GitHub Pages**:
Settings → Pages → Branch: `main` / carpeta `/root`.

## Bibliografía

Descripciones de cada modo apoyadas en *"Dos manos, cuatro cerebros"* (Dra. K. Benziger).
