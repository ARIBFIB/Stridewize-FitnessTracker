# 🏃‍♀️ Stridewize Fitness Tracker

![Stridewize Logo][]

It is a Fitness Tracker app for Android.

## How this app will work?

- You have to enter your name and weight. Based on that, the app will calculate your calories.
- Click on the start button to start your walk or run.
- Stop whenever you need to stop the run.
- After that, the app will give you details about your path, distance, speed, and calories burned, and show you in an image format.
- You can see your running exercise graph.

## Features

- **Google Map**: ![Google Maps Icon][] The app integrates with Google Maps API to track the user's location and display the workout path.
- **Dependency Injection**: ![Dependency Injection Icon][] The app uses dependency injection to manage the app's dependencies and improve testability.
- **Coroutines**: ![Coroutines Icon][] The app utilizes Kotlin Coroutines for asynchronous programming and task management.
- **Room Database**: ![Room Database Icon][] The app uses the Room database to store and retrieve user data, including workout history and settings.
- **MVVM Architecture**: ![MVVM Architecture Icon][] The app follows the Model-View-ViewModel (MVVM) architectural pattern, promoting separation of concerns and testability.
- **Notification**: ![Notification Icon][] The app uses notifications to provide real-time updates and ensure seamless workout tracking.
- **Foreground Service**: ![Foreground Service Icon][] The app uses a foreground service to track the user's workout even when the app is running in the background.
- **Live Data**: ![Live Data Icon][] The app uses LiveData to observe and update the UI based on changes in the underlying data.
- **Bottom Navigation with Navigation Graph**: ![Bottom Navigation Icon][] The app has a bottom navigation bar with a navigation graph to provide a smooth and intuitive user experience.

## Repository Structure
```
stridewize/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/
│   │   │   │       └── example/
│   │   │   │           └── stridewize/
│   │   │   │               ├── di/
│   │   │   │               ├── model/
│   │   │   │               ├── repository/
│   │   │   │               ├── ui/
│   │   │   │               ├── utils/
│   │   │   │               └── viewmodel/
│   │   │   └── res/
│   │   │       ├── drawable/
│   │   │       ├── layout/
│   │   │       ├── menu/
│   │   │       ├── navigation/
│   │   │       ├── values/
│   │   │       └── xml/
│   │   └── test/
│   │       └── java/
│   │           └── com/
│   │               └── example/
│   │                   └── stridewize/
│   └── build.gradle
├── gradle/
├── gradlew
├── gradlew.bat
└── settings.gradle
```

## License

This project is licensed under the [MIT License](LICENSE).![Stridewize Logo][]![Android Logo][]![Kotlin Logo][]![MIT License Logo][]![Contributions Welcome][]

## 📱 Overview

Stridewize is a comprehensive fitness tracking mobile application built using Android Studio and Kotlin. It seamlessly integrates with Google Maps API and MPAndroid Chart to provide users with a robust and visually appealing experience.

## 🌐 Features

- **Google Maps Integration**: ![Google Maps Icon][] Stridewize utilizes the Google Maps API to track the user's location and display their movement on a map. When a user starts a workout, the app calculates the distance traveled and visualizes it with a red line on the map.
- **MPAndroid Chart**: ![MPAndroid Chart Icon][] The app incorporates the MPAndroid Chart library to display fitness data, such as step count, distance, and other metrics, in a clean and informative manner.
- **Workout Tracking**: ![Workout Tracking Icon][] Users can start and pause their workouts, and the app will record the duration, distance, and other relevant data.
- **Personalized Dashboard**: ![Dashboard Icon][] Stridewize provides a personalized dashboard where users can view their fitness progress, set goals, and track their achievements.

## 🛠️ Installation

1. **Clone the repository:**   ```bash   git clone https://github.com/your-username/stridewize.git
   cd stridewize   ```

2. **Open the project in Android Studio:**
   - Launch Android Studio and select "Open an existing Android Studio project".
   - Navigate to the cloned repository and select the project directory.

3. **Obtain Google Maps API Key:**
   - Go to the Google Cloud Console and create a new project.
   - Enable the Google Maps Android API and obtain an API key.
   - Replace the placeholder `YOUR_API_KEY` in the `strings.xml` file with your API key.

4. **Build and Run the App:**   - Connect an Android device or start an emulator.
   - Click the "Run" button in Android Studio to build and deploy the app.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## 🙏 Acknowledgements

- **Android Studio**: ![Android Studio Icon][] [developer.android.com/studio](https://developer.android.com/studio)
- **Kotlin**: ![Kotlin Icon][] [kotlinlang.org](https://kotlinlang.org/)
- **Google Maps API**: ![Google Maps API Icon][] [developers.google.com/maps](https://developers.google.com/maps)
- **MPAndroid Chart**: ![MPAndroid Chart Icon][] [github.com/PhilJay/MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)

## 🤝 Contributing

Contributions are welcome! Please fork this repository, create a new branch, and submit a pull request.

1. **Fork the repository**
2. **Create a branch** (`git checkout -b feature-foo`)
3. **Commit your changes** (`git commit -am 'Add foo'`)
4. **Push to the branch** (`git push origin feature-foo`)
5. **Create a new Pull Request**

## 📞 Contact

Feel free to reach out if you have any questions or suggestions!

- **Email**: ![Email Icon][] your-email@example.com
- **GitHub**: ![GitHub Icon][] [your-username](https://github.com/your-username)
- **Developer**: ![Developer Icon][] Your Name
- **LinkedIn**: ![LinkedIn Icon][] [your-linkedin-profile](https://www.linkedin.com/in/your-linkedin-profile/)
