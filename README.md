# Camera App

This is a mobile application built with Expo and React Native, focused on camera functionalities.

## Getting Started

### Prerequisites

- Node.js and npm/yarn/bun installed
- Expo CLI installed (`npm install -g expo-cli` or `bun install -g expo-cli`)
- Development environment set up for React Native (Android Studio/Xcode if testing on emulators/simulators)

### Installation

1.  Clone the repository:
    ```bash
    git clone <your-repository-url>
    cd camera
    ```
2.  Install dependencies:

    ```bash
    # Using npm
    npm install

    # Using yarn
    yarn install

    # Using bun
    bun install
    ```

### Running the App

Use the following scripts to run the application:

- **Start the development server:**
  ```bash
  bun start
  ```
  This will open the Expo DevTools in your browser. You can then run the app on:
  - An Android emulator/device (`bun run android`)
  - An iOS simulator/device (`bun run ios`)
  - A web browser (`bun run web`)

## Available Scripts

- `bun start`: Starts the Expo development server.
- `bun run android`: Starts the app on a connected Android device or emulator.
- `bun run ios`: Starts the app on an iOS simulator or connected device.
- `bun run web`: Starts the app in a web browser.

## Technologies Used

- React Native
- Expo SDK (~51)
- Expo Router (~3.5)
- TypeScript
- Expo Camera
- Expo Media Library
- Expo AV / Expo Video

## Project Structure

```
.
├── assets/              # Static assets (icons, splash screens)
├── src/
│   ├── app/             # Expo Router routes/screens
│   │   ├── _layout.tsx  # Main layout component
│   │   ├── [name].tsx   # Dynamic route example (if applicable)
│   │   ├── camera.tsx   # Camera screen component
│   │   └── index.tsx    # Home/Index screen component
│   └── utils/           # Utility functions
│       └── media.ts     # Media handling utilities
├── .gitignore
├── app.json             # Expo configuration
├── babel.config.js      # Babel configuration
├── package.json         # Project dependencies and scripts
├── tsconfig.json        # TypeScript configuration
└── README.md            # This file
```

## Key Components & Features

_(Describe the main components and their functionalities here. Based on the file structure, you might detail `camera.tsx`, `index.tsx`, and the purpose of `media.ts`)_

- **`src/app/camera.tsx`**: Handles camera preview, capturing photos/videos.
- **`src/app/index.tsx`**: The main entry point or home screen of the app.
- **`src/utils/media.ts`**: Contains helper functions for saving or managing media files using `expo-media-library` and `expo-file-system`.

_(Add more details about specific features, navigation, state management, etc.)_

## Contributing

_(Add guidelines for contributing to the project, if applicable)_

## License

_(Specify the license for your project, e.g., MIT)_
