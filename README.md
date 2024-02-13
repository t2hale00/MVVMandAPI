# MVVM Todo App with API Integration

This repository contains a simple Todo Android app built using the MVVM (Model-View-ViewModel) architecture, which retrieves data from an API that returns JSON data.

## Overview

This app fetches todo items from a remote API and displays them in a list using Android Kotlin with Jetpack Compose. The MVVM architecture pattern is employed to separate concerns and improve code organization.

## Setup

To run this app locally, follow these steps:

1. Clone this repository to your local machine.
2. Open the project in Android Studio.
3. Ensure you have the necessary dependencies and SDKs installed.
4. Run the app on an emulator or physical device.

## Key Components

- **Data Model**: The `Todo` data class represents a single Todo item.
- **API Service**: The `TodosApi` interface defines functions to fetch Todos from the API using Retrofit.
- **ViewModel**: The `TodoViewModel` class manages the UI-related data and performs asynchronous API calls.
- **UI Implementation**: The UI components are created using Jetpack Compose, with the `TodoScreen` composable displaying the list of Todos.



