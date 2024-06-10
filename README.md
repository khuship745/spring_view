## Spring View
spring_view: A Flutter package that provides a delightful bounce effect for views, buttons, or widgets. Easily integrate it into your app to add a touch of playfulness!

<img src = "C:\flutter_workspace\git_repo\spring_view\assets\spring_view.gif">

## Features
Bounce Effect: Easily add a delightful bounce animation to any view, button, or widget in your Flutter app.


## Installing
To use this package, add `spring_view` as a dependency in your `pubspec.yaml` file.


## Usage

```dart
SpringView(
    child: Center(
    child: Container(
      padding: const EdgeInsets.all(8.0),
        decoration: BoxDecoration(
            color: Colors.cyan,
            borderRadius: BorderRadius.circular(8),
        ),
    child: const Text(
        "Spring view example"
      ),
    ),
  ),
  onPressed: (){}
),
```
