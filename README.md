# Aplicación móvil de gestión de citas médicas

## Descripción

Este proyecto presenta el análisis y selección de un stack de desarrollo para una aplicación móvil de gestión de citas médicas compatible con Android e iOS.

## Comparativa de frameworks

Se analizaron tres alternativas:

* **Flutter:** utiliza Dart y permite compartir gran parte del código entre Android e iOS.
* **React Native + Expo:** utiliza JavaScript/TypeScript y cuenta con un amplio ecosistema.
* **Kotlin Multiplatform:** utiliza Kotlin y permite compartir principalmente la lógica de la aplicación.

Después del análisis se seleccionó Flutter debido a su desarrollo multiplataforma, rendimiento y facilidad para compartir código.

## Stack seleccionado

* **Framework:** Flutter
* **Lenguaje:** Dart
* **IDE:** Android Studio
* **Plataformas:** Android e iOS
* **Comunicación:** API REST mediante HTTPS
* **Almacenamiento:** almacenamiento local y base de datos remota

## Hardware requerido

La aplicación utilizará:

* Cámara para escanear códigos QR
* Conexión Wi-Fi o datos móviles
* Almacenamiento local para consultar información sin conexión
* Notificaciones para recordar las citas

No son necesarios sensores como GPS, giroscopio o Bluetooth para las funciones principales.

## Entorno de desarrollo

Se utilizará Android Studio con:

* Flutter SDK
* Dart SDK
* Android SDK
* Flutter Plugin
* Dart Plugin
* Android Emulator

La configuración se comprobará mediante `flutter doctor`.

## Conclusión

El stack seleccionado es Flutter con Dart porque permite desarrollar una aplicación para Android e iOS utilizando una base de código compartida y proporciona las herramientas necesarias para implementar las funciones principales de la aplicación.

## Autor

Elías Rivera
