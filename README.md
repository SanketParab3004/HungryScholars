# HungryScholars

**HungryScholars** is a mobile application developed as a group project during the **Mobile Application Development (MDEV)** course at Georgian College. The app addresses the common problem of long wait times for food orders at campus food stores by providing a unified platform for pre-ordering or ordering food for pickup from multiple in-campus food outlets.

---

## Concept and Purpose

The primary goal of HungryScholars is to streamline the process of ordering food for students on college campuses. Many students face delays due to long lines, and while some food outlets have their own apps, not all do. HungryScholars solves this problem by:

1. Offering a single, unified platform for all campus food stores.
2. Allowing students to order food in advance for pickup, reducing wait times.
3. Supporting multiple campuses, enabling students to select their campus and access the relevant food outlets.

This app is designed to work across all campuses of a particular college. For instance, students at Georgian College can select their campus (e.g., Barrie, Orillia, Owen Sound) and view the available food stores in that location.

---

## Features

### User Features:
1. **Campus Selection**:
   - Choose from different campuses of the college.
   - View food stores specific to the selected campus.

2. **Food Ordering**:
   - Browse menus and place orders from in-campus food stores.
   - Option to pre-order food for a specific pickup time.

3. **Order Tracking**:
   - View order status in real-time.
   - Receive notifications when the order is ready for pickup.

4. **Unified Platform**:
   - Access all campus food outlets in one app, eliminating the need for multiple apps.

### Admin Features:
1. **Store Management**:
   - Add, update, or remove food stores available in specific campuses.

2. **Order Management**:
   - Process and update order statuses.
   - View analytics on order trends and peak times.

---

## Technologies Used

### Development Tools:
- **React Native**: For building a cross-platform mobile application.
- **Firebase**: For real-time database, authentication, and notifications.

### Other Libraries and Tools:
- **Redux**: For state management.
- **React Navigation**: For seamless navigation within the app.
- **Expo**: For easy testing and deployment.

---

## Installation and Setup

### 1. Clone the Repository:
```bash
git clone https://github.com/SanketParab3004/HungryScholars.git
```

### 2. Navigate to the Project Directory:
```bash
cd HungryScholars
```

### 3. Install Dependencies:
```bash
npm install
```

### 4. Configure Firebase:
1. Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
2. Add your app's package name to the Firebase project.
3. Download the `google-services.json` file and place it in the `app/` directory.
4. Set up Firestore for database operations.

### 5. Run the Application:
- **For Android**:
  ```bash
  npm run android
  ```
- **For iOS**:
  ```bash
  npm run ios
  ```

---

## Usage

### For Students:
1. **Select Your Campus**:
   - Choose from the list of campuses to view available food outlets.
2. **Browse Menus**:
   - Explore menus from various in-campus food stores.
3. **Place Orders**:
   - Add items to the cart and place your order.
   - Specify a pickup time if pre-ordering.
4. **Pick Up Your Order**:
   - Receive notifications when your order is ready.
   - Avoid long lines by heading straight to the pickup counter.

### For Food Store Admins:
1. **Manage Menus**:
   - Update food items, prices, and availability.
2. **Process Orders**:
   - View and update order statuses in real-time.
3. **Analyze Trends**:
   - Use analytics to track peak order times and popular items.

---

## Contribution Guidelines

Contributions to HungryScholars are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request and provide a detailed description of your changes.

---

## Acknowledgements

HungryScholars was developed as a group project for the **Mobile Application Development (MDEV)** course at Georgian College. Special thanks to the instructors and peers who provided guidance and support throughout the project.

---

## Contact

For inquiries or feedback, please reach out via:
- **Email**: sanket3004@gmail.com
- **GitHub**: [SanketParab3004](https://github.com/SanketParab3004)