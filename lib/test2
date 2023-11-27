import 'package:flutter/material.dart';

void main() {
   runApp(const MaterialApp(
    home: SafeArea(
      child: Scaffold(
        body: MyWidget()
      )
    ),
    debugShowCheckedModeBanner: false,
  ));
}

class MyWidget extends StatelessWidget {
  const MyWidget({super.key});
  @override
  Widget build(BuildContext context) {
    return Container(
      color: Colors.blue,
      child: Card(
        shape: RoundedRectangleBorder(
          borderRadius: BorderRadius.circular(10),
        ),
        child: Padding(
          padding: const EdgeInsets.all(8.0),
          child: Row(
            children: [
              Container(
                width: 60,
                height: 40,
                color: Colors.red,
              ),
              SizedBox(width: 10,),
              Expanded(
                  child: Column(
                    mainAxisSize: MainAxisSize.min,
                    crossAxisAlignment: CrossAxisAlignment.start,
                    children: [
                      Text('Pham Thanh Dat', style: TextStyle(fontSize: 16, fontWeight: FontWeight.bold),),
                      Text('14 Doan Uan, Khue My, Ngu Hanh Son', style: TextStyle(fontSize: 14),),
                    ],
                  )
              ),
              Container(
                width: 20,
                height: 20,
                color: Colors.green,
              ),
              SizedBox(width: 10,),
              Column(
                mainAxisSize: MainAxisSize.min,
                children: [
                  Container(
                    width: 20,
                    height: 20,
                    color: Colors.black,
                  ),
                  SizedBox(height: 8,),
                  Text('20'),
                ],
              ),
            ],
          ),
        ),
      ),
    );
  }
}
