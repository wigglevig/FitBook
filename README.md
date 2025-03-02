FitBook
Graph your eating habits with ease!


FitBook is a Flutter-based, privacy-focused calorie tracking application that works entirely offline. With its built-in food database, chart visualizations, and intuitive interface, you can seamlessly log your daily meals and snacks—even without an internet connection.

Features
Graphs: Visualize your macronutrient intake over time.
Foods: Ships with an extensive food database (sourced from local data or an API of your choice).
Offline: Log meals and snacks offline; no sign-ups or data syncing required.
Barcode Scanning (optional): Quickly scan barcodes to search for food items in your local database or third-party APIs.
Daily/Weekly Goals: Set calorie and macronutrient targets and track your progress.
Custom Foods: Create and manage your own custom entries.

Getting Started
Prerequisites
Flutter SDK (version 2.10.0 or higher recommended)
A suitable IDE such as Visual Studio Code or Android Studio
Installation
Clone the repository:
bash
Copy
Edit
git clone https://github.com/yourusername/FitBook.git
Navigate to the project directory:
bash
Copy
Edit
cd FitBook
Install dependencies:
bash
Copy
Edit
flutter pub get
Run the app on your preferred device or emulator:
bash
Copy
Edit
flutter run
Usage
Log Food Entries:

Tap on the Add Entry button to search for foods or create new items.
Adjust serving size and portions to accurately log your calorie and macronutrient intake.
View Analytics:

Switch to the Dashboard to see charts of your daily/weekly consumption.
Track macronutrient ratios (proteins, fats, carbs) and spot trends over time.
Manage Weight:

Record your weight periodically in the Weight section to see progress graphs.
Set goals and monitor your achievements.
Customize Settings:

Toggle dark mode, update daily calorie targets, and manage custom foods in Settings.
If you enable barcode scanning (optional), ensure you have the necessary permissions on mobile devices.
Project Structure
css
Copy
Edit
FitBook/  
├── android/  
├── ios/  
├── lib/  
│   ├── main.dart  
│   ├── screens/  
│   ├── widgets/  
│   ├── services/  
│   └── models/  
├── assets/  
│   └── images/  
├── pubspec.yaml  
└── README.md  
lib/: Contains all the Dart code for the application.
screens/: Houses the different UI screens (dashboard, food list, settings, etc.).
widgets/: Reusable UI components (buttons, cards, etc.).
services/: Classes handling data retrieval and storage, including local database operations.
models/: Data models representing food items, user settings, etc.
Contributing
Contributions are welcome! If you have ideas for improvements or spot any bugs, please:

Fork this repository.
Create a new branch for your feature or fix:
bash
Copy
Edit
git checkout -b feature/amazing-improvement
Commit your changes:
bash
Copy
Edit
git commit -m "Add amazing-improvement"
Push to the branch:
bash
Copy
Edit
git push origin feature/amazing-improvement
Create a new Pull Request describing your changes.
License
This project is licensed under the MIT License. You’re free to use and modify this software for both commercial and non-commercial purposes.

