# 📔 Mi Diario Digital

> Taller Final — Desarrollo de Aplicaciones Móviles con Kotlin y Android  
> Autores: **Cristian Faneite** y **Stefany Rodriguez**

---

## 🎯 Objetivo

Desarrollar una aplicación móvil en Android con Kotlin que permita:

Escribir y consultar entradas de diario (con título, fecha y contenido).
Guardarlas en una base de datos local (Room).
Consultar el clima del día a través de una API pública.
Cambiar el modo claro/oscuro de la aplicación, guardando esta preferencia.
Personalizar la experiencia con una interfaz limpia y amigable.

---

## 🛠️ Tecnologías utilizadas

- **Kotlin** (funciones, lambdas, data classes)
- **Android Studio**
- **Jetpack Compose** (interfaz declarativa moderna)
- **Material3**
- **Room** (base de datos local)
- **DataStore** (guardar preferencias del usuario)
- **Retrofit2** (consumo de API)
- **Coil** (carga de imágenes del clima)

---

## 🧩 Módulos del proyecto

| Carpeta | Contenido |
|--------|-----------|
| `fundamentos-kotlin/` | Uso de Kotlin: funciones, lambdas, data classes |
| `desarrollo-android/` | Código completo del proyecto Android Studio |
| `interfaz-ui-ux/` | Diseño con Jetpack Compose y Material 3 |
| `persistencia-datos/` | Implementación de Room: entidad, DAO, DB, ViewModel |
| `conectividad-redes/` | API del clima con Retrofit + Coil para íconos |

---

## 📸 Capturas de pantalla

> Puedes agregar tus propias capturas aquí (reemplazen las imágenes):

| 🏠 Pantalla principal | ☁️ Clima consultado | 🌙 Modo oscuro |
|----------------------|--------------------|----------------|
| ![home](capturas/home.png) | ![clima](capturas/clima.png) | ![dark](capturas/dark.png) |

---

## ▶️ Instrucciones para ejecutar

1. Clonar el repositorio:

```bash
git clone https://github.com/TuUsuario/TallerFinal_CristianFaneite_StefanyRodriguez.git

2.Abrir el proyecto en Android Studio

3.En el archivo MainScreen.kt, agregar su API Key de OpenWeather:

val apiKey = "TU_API_KEY"

4.Ejecutar en emulador o dispositivo con conexión a internet

//API utilizada
OpenWeather API
https://openweathermap.org/api

Se utiliza el endpoint /weather?q={ciudad} para obtener:
Temperatura actual
Ícono del clima
Nombre de la ciudad

//Conclusión
Este proyecto nos permitió integrar múltiples componentes del ecosistema Android moderno
(Jetpack Compose, Room, Retrofit, DataStore) en una aplicación funcional, atractiva y útil.
La experiencia también fortaleció el trabajo en equipo y la organización modular del código.
