# Project Overview
**TechNews Daily** is a fully functional Android app built entirely with Kotlin and Jetpack Compose. It aims to provide users with the latest technology news, articles, and updates, serving as a valuable resource for tech enthusiasts and developers. The app is designed with best practices in mind, ensuring a smooth user experience and up-to-date information.

## Tech Stacks

**Programming Languages:**  
- Kotlin  
- Java  

**Frameworks and Libraries:**  
- Jetpack Compose  
- Spring Boot (for backend services)  

**Build Tools:**  
- Gradle  

**Dependency Injection:**  
- Hilt  

**Testing Frameworks:**  
- JUnit  
- Espresso  
- Roborazzi (for screenshot testing)  

**UI/UX Design:**  
- Material 3  

# Key Features
- **News Feed**: Users can browse through the latest technology news articles and updates.
- **Topic Follow**: Users can follow specific topics of interest and receive notifications when new content is published.
- **Search Functionality**: Easily search for articles and topics to stay informed about specific areas of technology.
- **Dynamic Themes**: Supports dynamic color theming based on user preferences, including dark mode.

# Testing
TechNews Daily incorporates testing strategies using dependency injection with Hilt, allowing for realistic testing scenarios without relying on mocking libraries.

# Testing Approaches
Unit Tests: Use real implementations for testing data layer components.
Instrumentation Tests: Utilize a temporary folder for user preferences, ensuring realistic data flow during tests.
To execute tests, run the following Gradle tasks:

testDemoDebug: Runs all local tests against the demoDebug variant.
connectedDemoDebugAndroidTest: Runs all instrumented tests against the demoDebug variant.

![WhatsApp-Image-2024-11-01-at-12 36](https://github.com/user-attachments/assets/4fab747f-e5cf-43fd-b719-d58dee6809d4)


# UI Design
The app follows Material 3 design guidelines, with all screens and UI elements built using Jetpack Compose. It features:

Dynamic Color: Adapts to the user's current color theme.
Default Theme: Utilizes predefined colors when dynamic color is unsupported.
Dark Mode Support: Each theme supports dark mode for improved accessibility.
Adaptive layouts ensure compatibility across various screen sizes.

## My Contributions:
As the Android Developer for **TechNews Daily**, I am responsible for implementing the app's features using Kotlin and Jetpack Compose, ensuring a seamless user interface and experience. I collaborate with backend developers to integrate Spring Boot services, manage dependencies with Hilt for efficient testing, and ensure code quality through unit and instrumentation testing.
