# Shabrangkala

Shabrangkala is an Android shopping app built with Kotlin and Jetpack Compose. It connects to a WooCommerce/WordPress backend to display products, categories, product variations, and blog posts.

## Features

- Onboarding and user sign-in/sign-up flows
- Browse products and categories
- Search for products
- View product details and variations
- Add products to a cart or wishlist
- Read blog posts
- Local persistence with Room

## Tech stack

- Kotlin
- Jetpack Compose and Material 3
- Retrofit and Gson
- Room
- Koin
- Kotlin Coroutines
- Coil and Lottie

## Requirements

- Android Studio
- Android SDK 33 or newer
- JDK 8 or newer

## Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/AbbasShabrang/Shabrangkala.git
   cd Shabrangkala
   ```

2. Open the project in Android Studio.
3. Sync the Gradle files.
4. Run the `app` configuration on an emulator or Android device.

The app requires internet access to load data from its configured backend API.

## Project structure

- `app/src/main/java` - application code, UI, repositories, networking, and database
- `app/src/main/res` - layouts, themes, icons, fonts, and animations
- `app/src/test` - unit tests
- `app/src/androidTest` - instrumented tests
