NAME:ISHIMWE MWIZA Grace
ID:25192
                                   HELLO WORLD
    This Flutter code demonstrates a simple application that displays a "Hello World" message in the center of the screen.
    1. Import Flutter Package
    -> import 'package:flutter/material.dart';
* This line imports the Flutter material package, which provides the necessary widgets and classes to build a material design application.


    2. Main Function
    -> void main() {
  runApp(const MyApp());
}
* The main function is the entry point of the Flutter application. It calls the runApp function with the MyApp widget as its argument, which initializes the app and starts the rendering process.

  3. MyApp Class
  -> class MyApp extends StatelessWidget {

  const MyApp({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: const Text('Assignment 1'),
          backgroundColor: Colors.black,
          foregroundColor: Colors.white,
        ),
        body: const Center(
          child: const Text(
            'Hello World',
            style: TextStyle(fontSize: 50, fontStyle: FontStyle.italic ),
          ),
        ),
      ),
    );
  }
}
* Class Definition: MyApp extends StatelessWidget, indicating that this widget does not maintain any state.
Constructor: The const MyApp constructor is defined to create an instance of MyApp with an optional key parameter.
build Method: The build method describes the part of the user interface represented by this widget.

  4. MaterialApp Widget
  -> return MaterialApp(
  home: Scaffold(
* MaterialApp is a convenience widget that wraps a number of widgets commonly required for material design applications. It sets up the app-wide configurations such as themes, routes, and more.
The home property defines the default route of the app, which is the Scaffold widget in this case.

  5.Scaffold Widget
  -> home: Scaffold(
  appBar: AppBar(
    title: const Text('Assignment 1'),
    backgroundColor: Colors.black,
    foregroundColor: Colors.white,
  ),
  body: const Center(
    child: const Text(
      'Hello World',
      style: TextStyle(fontSize: 50, fontStyle: FontStyle.italic ),
    ),
  ),
),
* Scaffold is a layout structure for the material design, providing a default app bar, body, and other elements.
AppBar: The AppBar widget creates a material design app bar.
title: Sets the title of the app bar to 'Assignment 1'.
backgroundColor: Sets the background color of the app bar to black.
foregroundColor: Sets the color of the app bar text to white.
Body: The body property is set to a Center widget, which centers its child within itself.
Text: The Center widget contains a Text widget that displays 'Hello World'.
style: The text style is set using the TextStyle class, with a font size of 50 and italic font style.
  


   
