import 'package:flutter/material.dart';

void main() => runApp(MyApp());

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      // Application title (optional)
      title: 'Passionate Programmer',
      home: Scaffold(
        appBar: AppBar(
          title: Text('Home Page'),
        ),
        body: Center(
          // Show text in a right‑to‑left layout
          child: Directionality(
            textDirection: TextDirection.rtl,
            child: Text(
              'Passionate programmer facing coding challenges',
              style: TextStyle(fontSize: 24, fontWeight: FontWeight.bold),
            ),
          ),
        ),
      ),
    );
  }
}
✨Tech stack✨
JAVA(FRAMEWORK SpringBOOT)
PYTHON
FLUTTER
