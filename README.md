# first_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Method to Run

In order to run your application from terminal, type:

```bash
  $flutter emulators
```

Shows available emulators.

- To run an emulator, run 'flutter emulators --launch <emulator id>'.
- To create a new emulator, run 'flutter emulators --create [--name xyz]'.

```bash
  $flutter emulators --launch iOS Simulator
```

```bash
  $cd first_app
  $flutter run
```

# DART

Everything in dart is object. Programming language is strongly typed.
Type inference.

Sample code:

```dart
class person {

  String name;
  var age;
  String gender;

  person(String name, var age, String gender){
    this.name = name;
    this.age = age;
    this.gender = gender;
  }
}
String addNum(var num1, String num2){
  return (num1 + num2);
}

void main() {
//   var value11 = addNum(2.0 , '6');
//   var value12 = addNum(2.0, '7');
//   double ans1 = value11 + value12;
//   print(ans1);

//   var value21 = addNum("2.0" , '6');
//   var value22 = addNum("2.0", '7');
//   var ans2 = value21 + value22;
//   print(ans2);
//   print("Hello World in DART");

  var v1 = person("Hashir", 21, "male");
  print(v1.age);
  print(v1.name);
  v1.age = "200.1";
  print(v1.age);
}
```

Two types of widgets:

- Stateless - which does not save the state
- Statefull - which maintains the state - like cookies, login sessions