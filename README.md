# flutter_responsive_portfolio_webapp
> The Flutter Responsive Portfolio Web App is a modern, visually appealing portfolio website designed to showcase skills, projects, and achievements. Built with Flutter, this app is fully responsive and adapts seamlessly to different screen sizes, offering an optimal user experience across devices.

> Features
Responsive Design: Automatically adjusts layout and content for desktop, tablet, and mobile devices.
Customizable Sections: Easily modify content to highlight personal or professional details.
Interactive UI: Engaging animations and intuitive navigation.
Dark Mode Support: Optional theme toggling for enhanced user experience.
Reusable Components: Modular widgets for easy scalability and maintenance.

> Technologies Used
Flutter: Framework for building cross-platform applications.
Dart: Programming language for Flutter development.
Flutter Web: Web rendering engine for running Flutter apps in the browser.

> Installation
Ensure you have Flutter SDK installed.
Clone the repository:
git clone https://github.com/dharmsachapara/flutter-portfolio-web-app.git

Navigate to the project directory:
cd flutter-portfolio-web-app

Get the required dependencies:
flutter pub get

Run the app in the web environment:
flutter run -d chrome

> Project Structure

lib/
├── main.dart          # Entry point of the application
├── screens/           # Contains all the screen widgets
├── widgets/           # Reusable UI components
├── constants/         # Theme colors, fonts, and other constants
└── assets/            # Static resources (images, icons, etc.)

> Customization

> Edit Personal Details:
Modify the constants/personal_info.dart file to include your name, contact details, and social media links.

> Add Projects:
Update the constants/projects.dart file with project titles, descriptions, and links.

> Change Theme:
Customize colors and fonts in the constants/theme.dart file.

> Contribution
Contributions are welcome! Follow these steps to contribute:
Fork the repository.

Create a new branch for your feature:
git checkout -b feature-name

Commit your changes:
git commit -m "Add feature-name"

Push to the branch:
git push origin feature-name

Open a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for details.
