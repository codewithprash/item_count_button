<!--
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages).

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages).
-->

## item_count_number_button

TODO: Item Count Number Button is a Flutter package that allows you to easily implement a customizable item count widget with increment and decrement buttons. This widget is particularly useful in scenarios where you need to manage the quantity of items, such as in a shopping cart or inventory management system.

## features

- Increment and decrement buttons for adjusting the item count.
- Define the minimum and maximum values for the item count.
- Specify the number of decimal places for the displayed count.
- Customizable button colors, sizes, and text styles.
- Callback function to handle changes to the item count.
- Smooth animations for a visually appealing user experience.

TODO: With Item Count Number Button, you can effortlessly integrate an intuitive item count functionality into your Flutter application, enhancing the user experience and making it easier for users to manage quantities.

## Installation

TODO: Add item_count_number_button as a dependency in your pubspec.yaml file:

```yaml
dependencies:
  item_count_number_button: ^1.0.0

```

## Usage

TODO: Import the package in your Dart file:

```dart
import 'package:item_count_number_button/item_count_number_button.dart';
```

TODO: Use the ItemCount widget in your Flutter app:

```dart
ItemCount(
  initialValue: 0,
  minValue: 0,
  maxValue: 10,
  decimalPlaces: 0,
  onChanged: (value) {
    // Handle counter value changes
    print('Selected value: $value');
  },
),
```
## Widget Properties

TODO: The ItemCount widget accepts the following properties:

- initialValue (required): The initial value of the counter.
- minValue (required): The minimum value the user can pick.
- maxValue (required): The maximum value the user can pick.
- decimalPlaces (required): The number of decimal places required by the counter.
- onChanged (required): A callback function that is called when the counter value changes. It takes a single parameter of type num.
- step: The step value used when incrementing or decrementing the counter. Defaults to 1.
- color: The color of the increment and decrement buttons. If not specified, it uses the primary color from the app's theme.
- textStyle: The text style for the counter value display.
- buttonSizeWidth: The width of the increment and decrement buttons. Defaults to 30.
- buttonSizeHeight: The height of the increment and decrement buttons. Defaults to 25.

## Example

TODO: You can find a complete example in the example directory of this package.

## License

TODO: This Flutter package is released under the MIT License.


## Additional information

TODO: Welcome contributions to Item Count Number Button! If you encounter any issues, have suggestions for improvements, or would like to add new features, please feel free to open an issue or submit a pull request. Your contributions can help make this package even better.
<!-- ## Features

TODO: List what your package can do. Maybe include images, gifs, or videos.

## Getting started

TODO: List prerequisites and provide or point to information on how to
start using the package.

## Usage

TODO: Include short and useful examples for package users. Add longer examples
to `/example` folder.

```dart
const like = 'sample';
```

## Additional information

TODO: Tell users more about the package: where to find more information, how to
contribute to the package, how to file issues, what response they can expect
from the package authors, and more. -->
