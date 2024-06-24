import 'package:flutter/material.dart';

class FirtsApp extends StatefulWidget {
  const FirtsApp({Key? key}) : super(key: key);

  @override
  State<FirtsApp> createState() => _FirtsAppState();
}

class _FirtsAppState extends State<FirtsApp> {
  int a = 0;
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: Text("First App"),
        backgroundColor: Colors.indigo,
        foregroundColor: Colors.white,
        centerTitle: true,
        elevation: 20,
        shadowColor: Colors.black,
      ),
      body: Container(
        height: double.infinity,
        width: double.infinity,
        decoration: BoxDecoration(
            gradient: LinearGradient(colors: [
          Colors.indigo.shade900,
          Colors.indigo.shade500,
          Colors.indigo.shade300
        ])),
        child: Center(
            child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: [
            Text(
              "Press The Button",
              style: TextStyle(
                color: Colors.white,
              ),
            ),
            SizedBox(
              height: 15,
            ),
            Container(
              height: 50,
              width: 50,
              decoration: BoxDecoration(
                  color: Colors.indigo.shade100,
                  borderRadius: BorderRadius.circular(10)),
              child: Center(
                child: Text(
                  a.toString(),
                  style: TextStyle(fontWeight: FontWeight.bold, fontSize: 20),
                ),
              ),
            )
          ],
        )),
      ),
      floatingActionButton: FloatingActionButton(
        backgroundColor: Colors.indigo,
        foregroundColor: Colors.white,
        child: Icon(Icons.add),
        onPressed: () {
          a++;
          setState(() {});
        },
      ),
    );
  }
}
