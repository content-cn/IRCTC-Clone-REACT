# IRCTC Clone - React Project


The objective of this project is to build a fully functional **IRCTC Clone** using **React**, simulating the Indian Railway Catering and Tourism Corporation (IRCTC) platform for **train ticket bookings**, **user registration and login**, and **train search functionality**. This project involves various key aspects of **React development**, including component management, state handling, hooks, **Firebase integration**, and **routing**.

## Features

### 1. **User Authentication**
- **Sign Up & Login**: Users can sign up and log in using **Firebase authentication**.
- **Email Verification**: Integrated **email verification** for user account activation.
- **User Profile Management**: After login, users can manage their profile and view their booking history.

### 2. **Train Booking System**
- **Search Trains**: Users can search for trains based on **departure and destination stations** and **travel dates**.
- **Train Listings**: View available trains with **departure time**, **arrival time**, and **ticket availability**.
- **Ticket Booking**: Users can book train tickets for their selected trains.

### 3. **Booking History**
- Users can view their **past bookings** and details of each booking in the **Booking History** page.

### 4. **Styling with CSS Modules & Styled-components**
- **HomePage**, **TrainCard**, **Login**, **Register**, and other pages are styled using **CSS Modules** and **styled-components** for better maintainability and modularity.

### 5. **Component Lifecycle & React Hooks**
- **Component Lifecycle**: Handled using **lifecycle methods** for class-based components and **useEffect** for functional components.
- **React Hooks**: Utilized **useState**, **useEffect**, **useMemo**, **useCallback**, and **custom hooks** for optimized state management and performance.

### 6. **API Integration and Real-Time Data**
- Integrated with external **APIs** for fetching train data.
- **Firebase Firestore** is used for storing user data, booking details, and for real-time data syncing.

### 7. **Routing with React Router**
- **React Router** is used to manage navigation between various pages such as **HomePage**, **LoginPage**, **RegisterPage**, **BookingPage**, and **BookingHistoryPage**.
- **Nested Routes**: Implemented for more complex routing (e.g., train details and booking history).

### 8. **Advanced React Features**
- **Higher-Order Components (HOCs)**: Used to enhance components with additional functionality.
- Advanced hooks like **useMemo** and **useCallback** are implemented to optimize the performance of list rendering and API calls.

## Technologies Used
- **React**: For building the user interface and handling components.
- **Firebase**: For authentication, email verification, and Firestore for real-time data storage.
- **Redux**: For state management across the app.
- **React Router**: For handling navigation and routing.
- **CSS Modules & Styled-Components**: For styling components.
- **React Hooks**: To manage state and side-effects.
- **useEffect & Lifecycle Methods**: To handle API calls and component updates.


