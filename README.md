# 📇 Tarjeta de Presentación Digital - Ejercicio 4

[![Kotlin](https://img.shields.io/badge/Kotlin-1.9.0-blue.svg)](https://kotlinlang.org)
[![Compose](https://img.shields.io/badge/Jetpack%20Compose-1.6.0-brightgreen)](https://developer.android.com/jetpack/compose)

<div align="center">
  <img src="https://github.com/rodrigoangeloni/ipdm-oto-2025-rodrigo_angeloni_ejercicio-4/raw/main/app/src/main/res/drawable-nodpi/captura_ejercicio_4.png" width="300" alt="Captura de la tarjeta de presentación">
</div>

## 👨‍💻 Información del Desarrollador
- **Nombre**: Rodrigo Angeloni
- **Título**: Estudiante de Informática
- **Teléfono**: +11 (123) 444 555 666
- **Red Social**: @RodrigoAngeloni
- **Email**: rodrigoangeloni@gmail.com

## 🛠 Tecnologías Utilizadas
```kotlin
@Composable
fun BusinessCardScreen() {
    Column(
        modifier = Modifier
            .fillMaxSize()
            .background(Color(0xFFD2E8D4)),
        // Contenido de la tarjeta...
    ) {
        // Sección superior (logo y datos personales)
        // Sección inferior (contacto)
    }
}
