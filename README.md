# Unit Converter App

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) <!-- Opsional: Tambahkan badge lisensi jika ada -->

A simple and intuitive Android application for converting units, currently supporting temperature conversions between Celsius and Fahrenheit. This project demonstrates fundamental Android development concepts including UI design with XML, ViewModel for UI logic, LiveData for reactive UI updates, and basic animations.

## ✨ Features

*   **Temperature Conversion:** Convert values between Celsius and Fahrenheit.
*   **Intuitive Interface:** Easy-to-use numeric keypad for input.
*   **Swap Units:** Quickly swap between input and output units with a button.
*   **Clear Input:** Easily clear the current input.
*   **Real-time Updates:** Input and output values are updated reactively.
*   **Visual Feedback:** Animations provide a smoother user experience when swapping units.

## 📸 Screenshots

<!-- Tambahkan screenshot aplikasi Anda di sini. Anda bisa mengunggah gambar ke repositori GitHub Anda (misalnya dalam folder /screenshots) dan menautkannya. -->
<!-- Contoh: -->
<!-- ![App Screenshot 1](screenshots/screenshot1.png) -->
<!-- ![App Screenshot 2](screenshots/screenshot2.png) -->

**Tampilan Utama:**
*(Deskripsikan apa yang terlihat di screenshot ini)*

**Proses Konversi:**
*(Deskripsikan apa yang terlihat di screenshot ini)*

## 🛠️ Technologies Used

*   **Kotlin:** Primary programming language.
*   **Android SDK:** Core Android development tools.
*   **XML:** For UI layout design.
*   **Android Jetpack:**
    *   **ViewModel:** To store and manage UI-related data in a lifecycle-conscious way.
    *   **LiveData:** To build data objects that notify views when underlying data changes.
    *   **AppCompat:** For backward compatibility of Material Design components.
*   **View Binding (atau findViewById seperti dalam kode Anda):** For accessing UI elements.
*   **Basic View Animations:** For enhancing user experience.

## 🚀 How to Use

1.  **Input a Number:** Use the on-screen numeric keypad to enter the value you want to convert.
2.  **Select Units (Default):**
    *   The top unit (e.g., Celsius) is the input unit.
    *   The bottom unit (e.g., Fahrenheit) is the output unit.
3.  **Swap Units (Optional):** Click the "SWAP" button (ikon panah) to switch the input and output units.
4.  **Convert:** Click the "=" (COUNT) button to see the converted result in the output field.
5.  **Clear:** Click the "C" (CLEAR) button to reset the input field.

## 🏗️ Setup and Installation (For Developers)

1.  **Clone the repository:**   
    ```bash
    git clone https://github.com/afdaliable/UnitConverter-Android-App
    ```
    2.  **Open in Android Studio:**
    *   Open Android Studio.
    *   Select "Open an Existing Project".
    *   Navigate to the cloned directory and select it.
3.  **Build the project:**
    *   Android Studio should automatically sync and build the project. If not, go to `Build > Make Project`.
4.  **Run the application:**
    *   Select an emulator or connect a physical device.
    *   Click the "Run" button (ikon play hijau).

## 💡 Potential Future Enhancements

*   Add more unit types (e.g., length, weight, volume).
*   Implement input validation.
*   Improve UI/UX with Material Design 3 components.
*   Add unit tests.
*   Support for different themes (dark/light mode).

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details (jika Anda menambahkan file lisensi).

---

*This README was created to showcase the Unit Converter application as part of my developer portfolio.*