# RickyAndMortyApp

RickyAndMortyApp is a simple iOS application that showcases a list of characters from the popular Rick and Morty series. The app demonstrates the use of SwiftUI, UIKit, Combine, MVVM architecture, and modularized components. It also includes a custom module for asynchronous image loading.

---

## **Features**
- List of characters with names and images.
- Character details screen with additional information.
- Modularized `ImageLoader` for asynchronous image fetching and caching.
- Combine framework for reactive programming.
- Unit tests for logic and data fetching.

---

## **Requirements**

- Xcode 14.0 or later
- macOS Monterey (12.0) or later
- Swift 5.7 or later

---

## **Modules**
The app includes a custom module:

### **ImageLoader**
- The `ImageLoader` module is a reusable component for downloading and caching images asynchronously.
- It is included as a separate Swift package for modularity and reusability.

---

## **Setup Instructions**

### **1. Clone the Repository**
Clone the repository to your local machine:
```bash
git clone https://github.com/ugozeal/RickyAndMortyApp.git
cd RickyAndMortyApp
```

### **2. Open the Project**
Open the `RickyAndMortyApp.xcodeproj` file in Xcode:
```bash
open RickyAndMortyApp/RickyAndMortyApp.xcodeproj
```

### **3. Build and Run**
1. Select the `RickyAndMortyApp` scheme.
2. Choose an iOS simulator (e.g., iPhone 14).
3. Build and run the app using `Cmd + R`.

---

## **Running Tests**

The project includes unit tests to validate functionality.

1. Select the `RickyAndMortyApp` scheme.
2. Run the tests using `Cmd + U` or the test navigator in Xcode.

### **Testing Highlights**
- Tests for `ListViewModel` and `DetailViewModel`.
- Mocked `APIService` for isolated testing.
- 100% coverage for the logic layer.

---

## **How to Use**
1. Launch the app.
2. Browse the list of characters.
3. Tap on a character to view their details.

---

## **Troubleshooting**

### Simulator Issues
- If the simulator doesn't appear, ensure the iOS version matches your deployment target (e.g., iOS 15.0).
- Run `xcrun simctl list` in the terminal to verify available simulators.

### Module Import Issues
- Ensure the `ImageLoader` module is correctly linked.
- Clean the build folder: `Cmd + Shift + K`.
- Rebuild the project: `Cmd + B`.

---

## **Acknowledgements**
- [Rick and Morty API](https://rickandmortyapi.com/documentation) for providing character data.

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

