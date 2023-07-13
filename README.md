# Stopp

## Overview

Stopp is a personal safety application designed as an additional layer of protection for the user. The app leverages Apple's CMHeadphoneMotionManager and Speech frameworks to detect potential danger situations based on the abrupt removal of AirPods from the user's ears and the utterance of a predetermined distress word, "Stopp".

## How It Works

Upon the occurrence of these triggers, Stopp initiates a safety protocol. This protocol may include actions such as sending the user's current GPS location to a previously selected emergency contact and/or automatically dialing local emergency services with an automated distress message.

## Development

### Frontend

Stopp is built using React Native, a popular framework for building native apps using React and JavaScript. The app utilizes a native bridge to access iOS-specific functionalities, specifically the Core Motion and Speech data.

React Native allows us to write reusable components, manage the state of the app, and utilize a one-way data flow for better consistency and predictability of the app's behavior.

### Backend

The backend server is developed using Node.js and Express.js. Node.js is a runtime environment that executes JavaScript outside a web browser, and Express.js is a minimal web application framework for Node.js.

The backend manages the distress protocol, including receiving signals from the client app, processing these signals, and then performing actions such as sending the user's location or dialing emergency services.

### Database

User data, including emergency contact details, are stored in MongoDB, a source-available cross-platform document-oriented database program. MongoDB uses JSON-like documents with optional schemas, providing flexibility and scalability.

## Disclaimer

Please note, Stopp is designed to be a supplementary safety measure and should not replace standard safety protocols or tools. Users are encouraged to follow all necessary precautions for their personal safety.

## Compliance and Testing

The development and deployment of Stopp will comply with all regional safety, software, and privacy laws. The app will be thoroughly tested in various real-world scenarios to ensure reliability and to minimize both false positives and negatives.

## Contribution

Please read [CONTRIBUTING.md](link to your contributing guidelines) for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the [Insert license] - see the [LICENSE.md](link to your license) file for details
