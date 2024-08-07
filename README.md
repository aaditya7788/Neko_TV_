

# NekoTV

NekoTV is a React-based anime streaming application designed for tvOS. This project leverages Firebase for backend services and local storage. 

## Features

- Stream anime episodes
- Control video playback using the TV remote
- Navigate episodes and seasons
- Change video quality and audio language
- Continue watching section for quick access to ongoing series
- Loading animations for better user experience

## Prerequisites

- Node.js and npm installed
- Expo CLI
- Firebase project setup

## Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/aaditya7788/Neko_TV_.git
   cd Neko_TV_
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up Firebase**

   - Create a new Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Add an Android app to your Firebase project.
   - Download the `google-services.json` file from your Firebase project.
   - Replace the existing `google-services.json` file in the `Neko_TV_` project directory with your downloaded file.

4. **Configure Firebase in your project**

   Ensure the `firebase` and `@react-native-firebase/app` packages are installed and properly configured in your project.

5. **Run the application**

   ```bash
   npm start
   ```

   - For tvOS, run:

     ```bash
     expo run:ios
     ```

## Project Structure

- **`/components`**: Contains all the reusable React components.
- **`/screens`**: Contains the main screens for the application.
- **`/assets`**: Contains static assets like images and fonts.
- **`App.js`**: The main entry point of the application.
- **`firebase.js`**: Firebase configuration and initialization.

## Dependencies

- `react-native-tvos`
- `expo`
- `expo-av`
- `@react-native-firebase/app`
- `axios`
- `react-navigation`
- `react-native-swiper`
- `react-native-reanimated`
- `react-native-safe-area-context`
- `react-native-screens`

For the complete list of dependencies, refer to the `package.json` file.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to all contributors and the open-source community for their support and contributions.

