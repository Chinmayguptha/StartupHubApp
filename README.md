# StartupHub

A Flutter application for discovering startups, tracking funding rounds, and staying updated with startup news and trends.

## Features

- 🔐 Local Authentication
- 🏠 Home Dashboard with Featured Companies
- 🔍 Company Search and Filtering
- 📚 Startup News and Posts
- 📈 Funding Trends and Analytics
- 💰 Funding Tracker
- 🔖 Bookmarks
- 👤 User Profile
- 🌓 Dark/Light Theme

## Getting Started

### Prerequisites

- Flutter SDK (>=3.0.0)
- Dart SDK (>=3.0.0)
- Android Studio / VS Code
- Android/iOS emulator or physical device

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/startup_hub.git
cd startup_hub
```

2. Install dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

## Project Structure

```
/lib
  /screens
    - login_screen.dart
    - signup_screen.dart
    - home_screen.dart
    - search_screen.dart
    - trends_screen.dart
    - funds_screen.dart
    - profile_screen.dart
    - company_details_screen.dart
  /models
    - company_model.dart
    - post_model.dart
    - fund_model.dart
    - user_model.dart
  /widgets
    - post_carousel.dart
    - search_tile.dart
    - fund_card.dart
    - bottom_nav.dart
  /data
    - dummy_companies.dart
    - dummy_posts.dart
    - dummy_funds.dart
  main.dart
```

## Dependencies

- provider: State management
- shared_preferences: Local storage
- share_plus: Content sharing
- fl_chart: Charts and graphs
- image_picker: Profile image selection

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Flutter team for the amazing framework
- All contributors and maintainers 