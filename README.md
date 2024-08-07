# Travel_app

A new Flutter project.

## Summary

This project aims to provide travelers with comprehensive and easily accessible information about their destination country, ensuring they are well-informed and prepared for their journey.

## Features

- Detailed information about various countries.
- User-friendly interface for easy navigation.
- Real-time updates and notifications.
- Offline access to saved information.
- Integration with maps and local attractions.

## Installation

### Prerequisites

- Flutter SDK: [Installation Guide](https://flutter.dev/docs/get-started/install)
- Laravel: [Installation Guide](https://laravel.com/docs/8.x/installation)
- PHP: Version 7.3 or higher
- Composer: [Installation Guide](https://getcomposer.org/download/)

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/nadaeltorgoman/Travel_app.git
   cd Travel_app
   ```

2. **Install Flutter dependencies:**

   ```bash
   flutter pub get
   ```

3. **Navigate to the backend folder:**

   ```bash
   cd backend
   ```

4. **Install PHP dependencies:**

   ```bash
   composer install
   ```

5. **Set up environment variables:**

   Copy the `.env.example` file to `.env` and update the necessary environment variables.

   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

6. **Run database migrations:**

   Ensure your database is configured correctly in the `.env` file, then run:

   ```bash
   php artisan migrate
   ```

7. **Serve the backend:**

   ```bash
   php artisan serve
   ```

8. **Run the Flutter app:**

   ```bash
   cd ..
   flutter run
   ```

## Back-End

This project utilizes Laravel, a PHP framework, for the backend development. The backend handles data management, user authentication, and communication with external APIs.

[Link to backend folder](https://github.com/nadaeltorgoman/Travel_App_Back_End.git)

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any changes you'd like to make.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or suggestions, please contact:

- Your Name: [Nada El-Torgoman](mailto:nada.khalid.eltorgoman@gmail.com)
- GitHub: [Nada Eltorgoman](https://github.com/nadaeltorgoman)

---

Thank you for using Travel_app! Safe travels!
