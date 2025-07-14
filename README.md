# Flappy Bird Clone (React Native)

Este proyecto es un clon simple del clásico Flappy Bird, desarrollado con React Native y Matter.js usando el motor de juegos react-native-game-engine.

## Requisitos

- Node.js (recomendado v18+)
- npm o yarn
- Expo CLI (`npm install -g expo-cli`)

## Instalación de dependencias obligatorias

Antes de ejecutar el proyecto, asegúrate de instalar todas las librerías necesarias. Si falta alguna, la app **NO funcionará**.

Ejecuta en la raíz del proyecto:

```
npm install
```

Esto instalará:
- `react`
- `react-native`
- `expo`
- `expo-status-bar`
- `matter-js`
- `react-native-game-engine`

Si usas yarn:
```
yarn install
```

## Ejecución

1. Inicia el servidor de desarrollo:
   ```
   npm start
   ```
   o
   ```
   expo start
   ```

2. Escanea el QR con la app Expo Go en tu celular, o ejecuta en un emulador Android/iOS.

## Estructura principal

- `App.js`: Componente principal y lógica de juego.
- `components/Bird.js`: Renderiza el pájaro.
- `entities/index.js`: Define las entidades del juego.
- `physics.js`: Lógica física y de colisiones.
- `assets/`: Imágenes y recursos.

## Notas importantes

- Si agregas nuevas dependencias, recuerda correr `npm install`.
- Si tienes problemas con Expo, asegúrate de tener la última versión de Expo Go en tu dispositivo.

---

¡Diviértete jugando y modificando tu propio Flappy Bird!
