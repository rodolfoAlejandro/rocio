# Rocio
This app will be a cross-platform (Android, iOS, Windows, MacOS, Linux)

## Purpose
An app that helps users track their daily water intake and reminds them to stay hydrated thorughout
the day.

## Requirements
- [ ] The app should be able to allow users to set their daily water intake goals.
- [ ] The app should be able to track progress.
- [ ] The app should be able to send notifications to drink water regularly.
- [ ] The app should be able to provide insights into the benefits of staying hydrated.
- [ ] The app should be able to personalized recommendations based on th user's activity level.
- [ ] The app should be able to personalized recommendations based on th user's environment.

## Ideas to gather information
1. **Data collection**: Collect data from the user, such as their age, weight, height, activity level,
and any specific health conditions that may affect their hydration needs.

2. **Machine Learning Model**: Train a machine learning model using this data to predict the user's daily
water intake requirements. You can use algorithms like regression or neural networks to analyze the data
and make accurate predictions.

3. **User Input**: Allow user to input their daily activites, excercise routines, and enviromental factors
(like temperature and humidity) into the app. This additional information can help refine the AI's calculations.

4. **Real-time Monitoring**: Implement a feature that tracks the user's water consumption throughout the day. The AI
 can compare this data with the predicted intake requirements and provide real-time feedback to help the user stay
 hydrated.

5. **Personalized Recommendations**: Use the AI to provide persolaized recommendations on when and how much watyer the
user should drink based on their individual needs and habits.

## Programming language
- Python

## Frameworks
- Beeware: for cross-platform compatibility
- Tensorflow /w Keras: for machine learning model, and high-level neural netowrks.

## Design Patterns:
When designing a hydration tracker app, choosing the right design pattern can help you create a well-structured, maintainable, and scalable application. Here are a few design patterns that you may consider for your hydration tracker app:

1. **Model-View-Controller (MVC)**:
   - **Model**: Represents the data and business logic of the application, such as hydration goals, water intake records, and user information.
   - **View**: Represents the user interface components, such as the dashboard, input forms, and visualizations for hydration data.
   - **Controller**: Acts as an intermediary between the model and view, handling user input, updating the model, and updating the view accordingly.

2. **Model-View-ViewModel (MVVM)**:
   - **Model**: Represents the data and business logic, similar to MVC.
   - **View**: Represents the user interface components.
   - **ViewModel**: Acts as an intermediary between the model and view, but also exposes data and actions to the view in a way that is easy to bind to the user interface.

3. **Observer Pattern**:
   - Allows objects to subscribe and unsubscribe to events or changes in another object.
   - This pattern can be useful for updating the UI in real-time based on changes in hydration data or user input.

4. **Singleton Pattern**:
   - Ensures that a class has only one instance and provides a global point of access to it.
   - This pattern can be useful for managing a single source of truth for hydration data throughout the app.

5. **Decorator Pattern**:
   - Allows you to add new functionalities to objects dynamically.
   - This pattern can be useful for adding features like reminders, notifications, or gamification elements to encourage users to stay hydrated.

6. **Strategy Pattern**:
   - Defines a family of algorithms, encapsulates each one, and makes them interchangeable.
   - This pattern can be useful for implementing different strategies for calculating hydration goals based on user preferences or health factors.
