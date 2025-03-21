# AI Chat Assistant for Android

A modern ChatGPT-like Android application built with Kotlin, following best practices in Android development.

## Features

- Modern, clean chat interface with support for light/dark modes
- AI-powered conversations with context awareness
- Markdown and code syntax highlighting support
- User authentication and chat history management
- Material Design 3 compliant UI

## Architecture

This application follows the MVVM architecture pattern and uses the following technologies:
- Kotlin as the primary language
- Jetpack components (ViewModel, LiveData, Room, Navigation)
- Retrofit for API communication
- Dagger Hilt for dependency injection
- Coroutines for asynchronous operations

## Project Structure

The project is organized into the following main packages:
- `data`: Contains repositories, data sources, and models
- `di`: Contains Dagger Hilt dependency injection modules
- `ui`: Contains activities, fragments, view models, and adapters
- `util`: Contains utility classes and extensions
- `network`: Contains API service definitions
- `db`: Contains Room database implementation

## Getting Started

1. Clone the repository
2. Set up your OpenAI API key in the local.properties file
3. Build and run the application

## License

This project is licensed under the MIT License - see the LICENSE file for details.
