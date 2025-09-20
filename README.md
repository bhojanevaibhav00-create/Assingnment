# Flutter Developer Machine Test

This project is a **mobile application developed in Flutter** as a machine test for the Flutter Developer role at **C S Tech Infosolutions Private Limited**.  
The app is a single-file solution that demonstrates **UI replication**, **state management**, and **API integration** based on the provided **Figma** and **Postman** links.

---

## 🚀 Features

The application implements the following core functionalities as per the test requirements:

- **Language Selection**:  
  The app's initial screen allows users to select their preferred language.

- **User Authentication**:
  - **Registration**: Users can register with their name, email, password, and mobile number.  
  - **OTP Verification**: After registration, an OTP is sent to the provided email, which can be verified to proceed.  
  - **Sign-In**: An alternative sign-in page is provided for returning users.

- **Dashboard**:  
  A dynamic dashboard displays mock call statistics using a pie chart to visualize **Pending**, **Done**, and **Scheduled** calls.

- **Navigation Flow**:  
  The app follows the specific page-to-page navigation as outlined in the test video and Figma design, including transitions to a **“2 Minute Challenge”** page and a **“Test List”** page.

- **API Integration**:  
  The app integrates with the provided mock REST APIs for **user registration** and **OTP verification**.

---

## 🛠 Technical Details

- **Language**: Dart  
- **Framework**: Flutter  
- **State Management**: StatefulWidget  
- **Networking**: `http` package for API calls  
- **Charting**: `fl_chart` package for the pie chart visualization  

---

## ⚙️ Getting Started

To run this project, ensure you have the **Flutter SDK** installed and configured on your machine.

### 1. Clone the Repository
```bash
git clone https://github.com/bhojanevaibhav00-create/Assingnment
cd Assingnment
cd test1
```
## ⚙️ Getting Started

### 2. Install Dependencies

Run the following command to install the required packages, including **http** and **fl_chart**:

```bash
flutter pub get
```
### 3. Run the App

Connect a device or start an emulator and run the app from your terminal or IDE:

```bash
flutter run
```
