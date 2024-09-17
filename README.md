# DealsDray App

This Flutter app was developed as part of an assignment for the Flutter Developer Intern position at **DealsDray, Bangalore**. The app demonstrates essential features such as OTP-based login, email registration with referral, and product listing.

## Features

- **OTP Authentication**: Users can log in via OTP, with options to resend and verify OTP.
- **Email Registration with Referral**: Users can register using their email and referral code.
- **Device Info Capture**: Automatically sends device information during the splash screen phase.
- **Product Listing**: Displays available products on the home screen.

## Tech Stack

- **Flutter**: Cross-platform mobile development framework.
- **Provider**: For state management.
- **Clean Architecture**: Ensures separation of concerns and scalability.
- **Dio**: For making HTTP requests.

## Project Structure

The app is structured using Clean Architecture principles, with clear separation between the presentation, domain, and data layers.

- **Data Layer**: Handles data sources and communication with remote services.
- **Domain Layer**: Contains business logic and application rules.
- **Presentation Layer**: Manages the UI and interaction logic.

## Installation & Setup

To run the app locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/makthakur28/DealsDray.git
   ```

2. **Install dependencies**:

   ```bash
   flutter pub get
   ```

3. **Run the app**:

   ```bash
   flutter run
   ```

## Future Improvements

- Improve error handling for a more seamless user experience.
- Add more robust UI/UX enhancements.
- Include unit and integration testing.

