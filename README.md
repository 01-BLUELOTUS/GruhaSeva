<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GruhaSeva React Native App</title>
</head>

<body>
    <h1>GruhaSeva React Native App</h1>

    <p>Welcome to GruhaSeva, a home service application built with React Native and Expo.</p>

    <h2>Prerequisites</h2>

    <p>Before you begin, ensure you have met the following requirements:</p>

    <ul>
        <li><strong>Node.js</strong>: Install the latest version of Node.js from <a href="https://nodejs.org/">nodejs.org</a>.</li>
        <li><strong>Expo CLI</strong>: Install Expo CLI globally using npm:</li>
    </ul>

    <pre><code>npm install -g expo-cli
    </code></pre>

    <p><strong>Android Studio/Xcode</strong>: For running the app on an Android emulator or iOS simulator, ensure you have Android Studio or Xcode installed.</p>

    <h2>Installation</h2>

    <p>To set up the project locally, follow these steps:</p>

    <ol>
        <li><strong>Clone the repository</strong>:</li>
    </ol>

    <pre><code>git clone https://github.com/01-BLUELOTUS/GruhaSeva.git
    cd GruhaSeva
    </code></pre>

    <ol start="2">
        <li><strong>Install dependencies</strong>:</li>
    </ol>

    <pre><code>npm install
    </code></pre>

    <h2>Running the App</h2>

    <p>To run the app, you can use one of the following commands:</p>

    <ul>
        <li><strong>Start the development server</strong>:</li>
    </ul>

    <pre><code>npm start
    </code></pre>

    <ul>
        <li><strong>Run on Android emulator/device</strong>:</li>
    </ul>

    <pre><code>npm run android
    </code></pre>

    <ul>
        <li><strong>Run on iOS simulator/device</strong>:</li>
    </ul>

    <pre><code>npm run ios
    </code></pre>

    <ul>
        <li><strong>Run on web</strong>:</li>
    </ul>

    <pre><code>npm run web
    </code></pre>

    <h2>Project Structure</h2>

    <p>Here's a brief overview of the project structure:</p>

    <pre><code>home-service-app/
├── assets/                # Asset files (images, fonts, etc.)
├── node_modules/          # Node.js modules
├── App.js                 # Main application component
├── app.json               # Expo configuration
├── babel.config.js        # Babel configuration
├── package.json           # Project metadata and dependencies
└── README.md              # Project documentation
    </code></pre>

    <h2>Troubleshooting</h2>

    <p>If you encounter any issues, try the following:</p>

    <ul>
        <li><strong>Clear cache</strong>:</li>
    </ul>

    <pre><code>expo start -c
    </code></pre>

    <ul>
        <li><strong>Reinstall dependencies</strong>:</li>
    </ul>

    <pre><code>rm -rf node_modules
npm install
    </code></pre>

    <ul>
        <li><strong>Ensure correct Expo CLI version</strong>:</li>
    </ul>

    <pre><code>npm install -g expo-cli
    </code></pre>

    <h2>Contributing</h2>

    <p>If you want to contribute to this project, please follow these steps:</p>

    <ol>
        <li><strong>Fork the project</strong></li>
        <li><strong>Create a new branch</strong> (e.g., `git checkout -b feature/YourFeature`)</li>
        <li><strong>Commit your changes</strong> (`git commit -m 'Add some feature'`)</li>
        <li><strong>Push to the branch</strong> (`git push origin feature/YourFeature`)</li>
        <li><strong>Open a Pull Request</strong></li>
    </ol>

    <h2>License</h2>

    <p>This project is licensed under the MIT License.</p>
</body>

</html>
