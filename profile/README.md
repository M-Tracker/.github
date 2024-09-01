# Mistake Tracker

Mistake Tracker is an Android application designed to help users keep track of their mistakes, learn from them, and ultimately grow. Users can categorize mistakes, add details, and log lessons learned. The app also includes a feature for sharing mistakes anonymously to receive suggestions from others.

## Features

- **Track Mistakes**: Log and categorize mistakes with details and lessons learned.
- **Mistake Sharing**: Share mistakes anonymously and get feedback from the community.
- **RecyclerView**: Displays a list of mistakes with click events handled by the `ClickToOpenDetailActivity` interface.
- **Custom UI**: Features like `CircleImageView` for user avatars in RecyclerView items.
- **Firebase Authentication**: Secure login and registration using Firebase.

## Screenshots

*Include screenshots or gifs of your app here.*

## Tech Stack

- **Language**: Kotlin
- **Architecture**: MVVM (Model-View-ViewModel)
- **UI**: Jetpack Compose, XML Layouts
- **Database**: Room
- **Network**: Retrofit
- **Coroutines**: Kotlin Coroutines for background operations
- **Firebase**: Firebase Authentication for login functionality

## Project Structure

```bash
├── main
│   ├── activity
│   ├── fragment
│   ├── adapter
│   ├── viewmodel
│   ├── repository
│   ├── database
│   ├── api
│   └── model
