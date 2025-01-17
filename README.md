# Employee Data Handling Task 1

This project is a Flutter application that fetches employee data from a remote API, caches it locally using `SharedPreferences`, and displays it in a visually appealing list. The app also includes a shimmer effect for loading states and a pull-to-refresh feature to fetch updated data from the server.

---

## Features

- **Fetch Employee Data**: Fetches employee data from a remote API (`https://mocki.io/v1/c2688074-6ee3-4ea6-b60f-a57bcbc3253e`).
- **Local Caching**: Uses `SharedPreferences` to cache employee data locally for offline access.
- **Shimmer Effect**: Displays a shimmer loading effect while fetching data.
- **Pull-to-Refresh**: Allows users to refresh the employee list by pulling down.
- **Error Handling**: Gracefully handles errors and displays cached data if available.
- **Responsive UI**: Built with a responsive and visually appealing UI using gradients and custom widgets.
- **Employee Details View**: Displays detailed information about an employee in a modern and creative design.

---

## App Demo Video 🎥

[Watch the localization demo video here](https://github.com/user-attachments/assets/5272b446-3401-4aa6-8231-dfba7ab87bbb)

## Screenshots

| Loading State                                                                                     | Employee List                                                                                     | Employee Details      |
| ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | --------------------- |
| ![Loading State](https://github.com/user-attachments/assets/2be2ee42-1d5d-4daf-ac8d-ea71e049bafe) | ![Employee List](https://github.com/user-attachments/assets/7d199b2f-3642-4f9a-8d72-08f7916efd18) | ![Employee Details](https://github.com/user-attachments/assets/eb861c4b-da1b-4a2e-a557-444fc1fa086e) |

---

## Technologies Used

- **Flutter**: The framework used to build the application.
- **Dio**: For making HTTP requests to the API.
- **SharedPreferences**: For local caching of employee data.
- **Shimmer**: For displaying a shimmer effect during loading.
- **Retrofit**: For generating API client code (not used in this project but included in dependencies).
- **Freezed**: For generating immutable data classes (not used in this project but included in dependencies).

---

## Setup Instructions

### Prerequisites

- Flutter SDK installed on your machine.
- A code editor (e.g., Visual Studio Code, Android Studio).

### Steps

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/OmarAmeer96/Sprints-Data-Handling-Task-2.git
   cd Sprints-Data-Handling-Task-1
   ```

2. **Install Dependencies**:

   ```bash
   flutter pub get
   ```

3. **Run the App**:

   ```bash
   flutter run
   ```

## Usage

1. **Fetching Data**:

   - The app fetches employee data from the API when launched.
   - If the API call fails, it falls back to cached data (if available).

2. **Pull-to-Refresh**:

   - Pull down on the employee list to refresh the data from the server.

3. **Error Handling**:

   - If both the API call and cached data fail, an error message is displayed.

4. **Employee Details View**:

   - Tap on an employee card to view detailed information about the employee, including their name, age, salary and profile image.

   - The details view features a modern design with gradients, glassmorphism effects, and smooth animations.
