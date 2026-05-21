# weather-frontend-m6

## Este proyecto corresponde a una plataforma web orientada a mostrar el estado del tiempo en distintas ciudades de Chile, presentando la información de manera clara, ordenada y accesible para el usuario , la informacion climatica se obtiene mediante una API.

## App de Clima SPA - Vue.js

## Descripción

Esta aplicación fue desarrollada con Vue.js y Vue Router como una SPA (Single Page Application).

La app permite ver información del clima de distintas ciudades de Chile utilizando la API de Open-Meteo.

El usuario puede:

- Ver ciudades con su clima actual.
- Buscar ciudades.
- Ver el detalle de cada ciudad.
- Revisar el pronóstico semanal.
- Ver estadísticas del clima semanal.
- Navegar entre vistas sin recargar la página.

API utilizada:

- https://open-meteo.com

---

## Se utilizaron las siguientes directivas de Vue:

- v-for
  Para recorrer ciudades y pronósticos.

- v-if
  Para mostrar mensajes cuando no existen resultados.

- v-model
  Para el buscador de ciudades.

- @click
  Para interacción con botones.

- {{ }}
  Para mostrar datos dinámicos.

# Vistas principales

## Home (/)

La vista principal muestra:

- Lista de ciudades.
- Temperatura actual.
- Estado del clima.
- Índice UV.
- Buscador de ciudades.

Cada ciudad tiene un botón para ver más detalles.

---

## Detalle (/lugar/:id)

La vista detalle muestra:

- Imagen de la ciudad.
- Temperatura actual.
- Estado del clima.
- Humedad.
- Pronóstico semanal.
- Estadísticas del clima.
- Alertas climáticas.

También incluye un botón para volver al Home.

---

## Nosotros (/about)

Vista informativa sobre:

- Los climas de Chile.
- Explicación de zonas climáticas.
- Información general de la aplicación.

---

## Componentes Utilizados

App.vue
NavbarView.vue
FooterView.vue
HomeView.vue
DetalleView.vue
AboutView.vue

## Rutas Utilizadas

La aplicación utiliza Vue Router con las siguientes rutas Con su ruta y descripción:

-/lugar/:id/Detalle de una ciudad
-/about /Información sobre la web

## Ejecución del proyecto

Para ejecutar este proyecto de manera local:

1. Clonar o descargar el repositorio:  
   https://github.com/jorgeurrutia21/weather-front-end-m6

2. Boton derecho en la carpeta del proyecto y abrir la consola Git Bash Here.

3. Ejecutar los comandos pnpm install para instalar los node-modules y pnpm dev para ingresar al app.

4. Ingresar a esta URL http://localhost:5173 para ver la app.

---

## Objetivo del proyecto

El objetivo principal es entregar información meteorológica de distintas ciudades de Chile, permitiendo al usuario consultar tanto el clima actual como el pronóstico estimado para los próximos 7 días de diferentes ciudades de Chile.

---

## Autor

_Jorge Urrutia_
