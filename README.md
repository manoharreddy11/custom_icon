import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text('Custom Icon Example'),
        ),
        body: Center(
          child: Icon(
            Icons.star,
            size: 150,
            color: Colors.amber,
          ),
        ),
      ),
    );
  }
}
