## Flutter Questions


### Stateless & Stateful Widgets

**Q.1** **[What is StatelessWidget?]**(https://medium.com/@milankathiriya/what-is-statelesswidget-in-flutter-4932bb11e498) <br>
**Ans.**
This is a kind of widget which is static and only created once in a memory (RAM). Using this widget we cannot update an UI. Since this widget did not created in memory frequently, this supplies rapid performance as compared to StatefulWidget. This widget contains only one lifecycle method, build() method.

Q.2 [What is StatefulWidget?](https://medium.com/@milankathiriya/what-is-statefulwidget-in-flutter-6e043c4cbda9)

Q.3 What are the differences between StatelessWidget & StatefulWidget?

Q.4 Explain the lifecycle methods of StatefulWidget.

Q.5 Explain differences between initState() & dispose() methods.

---

### Libraries

1. What is a library in Dart?
2. How to create a custom library in Dart?
3. How to use a custom library in Dart?
4. Explain as, show, and hide keywords.

---

### Material & Cupertino

1. What is Material design & Human interface design?
2. How to achieve Material & Human interface design in Flutter?
3. How to switch between MaterialApp & CupertinoApp manually without using any State Management approach?
4. What is an adaptive widget? How many adaptive widgets have come as pre-defined in Flutter?
5. What to do if a UI is not changing (state is not updating) in an AlertDialog or in a ModalBottomSheet?
6. What to do if an error is occurred of "Material widget not found" while working in the CupertinoApp parent widget?

---

### General

1. How many Flutter app lifecycle methods? Explain which state executed when?
2. What is Hot Reload & Hot Restart? Explain in detail.
3. What is a Model class? Why we should use it?
4. What is a Singleton class? When and why we should use it?
5. What is a Helper class?
6. What is a Future class? Explain with examples in detail.
7. What is a Timer class? Describe the use of it.
8. Difference between Future & Timer class.
9. What is Stream?
10. What is the FutureBuilder widget? When should we use it?
11. What is the StreamBuilder widget? When should we use it?

---

### OOP

1. What is OOP? Why we should always code with OOP?
2. What is Class & Object? Explain with examples in detail.
3. What are the principles of OOP?
4. What is Encapsulation? Explain with examples in detail.
5. What is Inheritance? Explain with examples in detail.
6. What is Polymorphism? Explain with examples in detail.
7. What is Abstraction? Explain with examples in detail.
8. What is Exception Handling? Explain with an example.
9. How to create a custom exception?
10. Explain try, on, catch, and finally keywords in detail.
11. Explain the use of constructors with their types.
12. Explain the factory constructor with its advantage.
13. How to create class attributes as public or private?

---

### Persistent Storage

1. What is Persistent Storage?
2. How many approaches are in Flutter for saving Persistent data?
3. What are Shared Preferences? Explain the pros & cons.
4. What is Hive DB? Explain the pros & cons.
5. What is SQLite DB? Explain the pros & cons.
6. What is Collection & Document? Explain in detail as No-SQL DB terms.
7. What is SQL? How it is important?
8. Explain CRUD operations in detail in an example.
9. Difference between Relation & Non-Relation DB.
10. List pros. & cons. of Relation & Non-Relation DB.
11. In which formats, data can be stored using Shared Preferences?
12. Explain a complete procedure for setup the sign_up & sign_in mechanism for multiple users in Flutter using Shared Preferences.
13. Explain a complete procedure for setup sign_up & sign_in mechanism for multiple users with different user_roles in Flutter using SQLite.
14. Explain a complete procedure for setup the sign_up & sign_in mechanism for multiple users with different user_roles in Flutter using Firebase Firestore Database. Do not use Firebase Authentication Service.
15. Explain how to achieve AUTOINCREMENT feature in the Firebase Firestore database manually?
16. Explain the FOREIGN KEY concept in SQL with examples in detail.
17. Explain one-time intro screen logic using Shared Preferences.
18. How to save an image in Relational DB & in Non-Relational DB.
19. How to save a color in Relational DB & in Non-Relational DB
20. How to save an icon in Relational DB & in Non-Relational DB.
21. Can we save a custom object in DB? If yes, then in which type of DB and how?
22. [List SQL queries for CRUD operations.](https://medium.com/@milankathiriya/sql-queries-for-sqlite-database-9729a841ba7d)

---

### JSON Parsing

1. [What is JSON?](https://medium.com/@milankathiriya/what-is-json-7e13f6cbfc57)
2. What is JSON Parsing?
3. What is JSON Encoding?
4. What is JSON Decoding?
5. What is Local JSON Bank? How to load it in Flutter?

---

### API

1. [What is API?](https://medium.com/@milankathiriya/what-is-api-f80bbd78f771)
2. [Which kind of data can be used while API calling?](https://medium.com/@milankathiriya/what-is-api-f80bbd78f771#6157)
3. [Explain types of APIs.](https://medium.com/@milankathiriya/what-is-api-f80bbd78f771#2402)
4. [Explain types of HTTP requests.](https://medium.com/@milankathiriya/what-is-api-f80bbd78f771#e3db)
5. [How to call an API?](https://medium.com/@milankathiriya/what-is-api-f80bbd78f771#024f)
6. [By which packages we can call an API in Flutter and how?](https://medium.com/@milankathiriya/api-calling-in-flutter-5b118d9e25c2)
7. [For a successfully arrived response after an API call, what response code did we should achieve?](https://medium.com/@milankathiriya/what-is-api-f80bbd78f771#3027)
8. [What is API Key?](https://medium.com/@milankathiriya/what-is-api-f80bbd78f771#473c)

---

### Advance UI

1. What is Sliver? Where it can be used?
2. Difference between CustomScrollView & NestedScrollView widgets?
3. How many types of Sliver widgets can be used in Flutter? List them.

---

### Animation

1. How many types of Animation we can do in Flutter?
2. What is Tween Chaining? How to create it?
3. What is Staggered Animation? How to create it?
4. Explain any three Implicit animation widgets.
5. Explain any three Explicit animation widgets.
6. Difference between CustomPainter and CustomClipper.

---

### Push Notifications

1. How many types of Push Notifications in Flutter?
2. How many types of Local Push Notifications in Flutter?
3. How many types of FCM (Firebase Cloud Messaging) Push Notifications in Flutter?
4. How to send FCM Push Notifications? Explain all possibilities.

---

### State Management System

1. [What is State? Describe types of states in detail.](https://medium.com/@milankathiriya/what-is-state-in-flutter-describe-types-of-states-in-detail-22af620ba7d5)
2. What is State Management System? List some popular approaches.
3. Explain the working flow of the Provider state management system.
4. Explain the working flow of the GetX state management system.
5. Explain difference between Consumer widget & Provider.of(context) constructor.
6. Describe the difference between GetX state management approaches.
7. Explain the logic of changing the app theme using Provider.
