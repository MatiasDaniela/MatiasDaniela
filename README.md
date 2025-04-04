- 👋 Hi, I’m @MatiasDaniela
- 👀 I’m interested in em me tornar Dev
- 🌱 I’m currently learning java
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me email matiassdaniela@outlook.com.br
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
main() {
 // criar o objeto da minha primeira tela (tela inicial).
 runApp(new MyApp()); // executará o método build do objeto da classe MyApp.
}

class MyApp extends StatelessWidget { 

 @override
 Widget build(BuildContext context) { // desenhar a tela!
   // Text txt = new Text('Hello World');
   return MaterialApp(
     theme: ThemeData(useMaterial3: false),
     home: Scaffold(
       appBar: AppBar(),
       body: Text('Hello World', style: TextStyle(fontSize: 30, color: Colors.green)),
       floatingActionButton: Text('FAB'),
   	//bottomNavigationBar: Text('Bottom Navigation Bar'),
       drawer: Container(width: 200, color: Colors.red), // ~ div
     ),
   );
 }
}

<!---
MatiasDaniela/MatiasDaniela is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

