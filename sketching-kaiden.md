# sketching ideas for tasks of Kaiden. 

## Materials
### essentials
#### to-do-list related
- projects
	- plans
		- tasks
		- daily tasks
- calendar and planner
	
- memories 
	- pictures
	- diaries

- financial
	- piggy bank
		- allowance 
			- for date or to go out
	- financial goal

- current status for both(What the other is doing right now: studying, eating, sleeping, etc)
#### nonessential
- private messaging 
- I miss you
- emergency 
- games(chess, checker, color war, etc)
- live location
- snap 

---

#### implementing
#### I need to learn the basic of dart first.

[[reading_dart_apprentice_sketch_note]]

looks like java. Let's skip dart for now. 

### Learning how to create ui in flutter from youtube. 

==The starting point of flutter app==

```dart
import 'package:flutter/material.dart';  
  
void main() {  
  runApp(const MyApp());  
}  
  
class MyApp extends StatelessWidget {  
  const MyApp({super.key});  
  
  @override  
  Widget build(BuildContext context) {  
    return MaterialApp(  
      debugShowCheckedModeBanner: false,  
    );  
  }  
}
```


```dart
List<int> name = ["one", "two"]

Map user = { // python dictionary လိုမျိုး
	"name": "Aung Myint Myat",
	"age": 21, // အဆုံးမှာလည်း comma ထည့်ပေးတယ်
}
```


#### start learning the UI

==scaffold==
- 