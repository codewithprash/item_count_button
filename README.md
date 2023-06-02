## item_count_number_button

![Screenshot_1685721699](https://github.com/codewithprash/item_count_number_button/assets/87913082/2a9112d2-0984-4a1c-a477-f226919f553d)

Item Count Number Button is a Flutter package that allows you to easily implement a customizable item count widget with increment and decrement buttons. This widget is particularly useful in scenarios where you need to manage the quantity of items, such as in a shopping cart or inventory management system.

## features

- Increment and decrement buttons for adjusting the item count.
- Define the minimum and maximum values for the item count.
- Specify the number of decimal places for the displayed count.
- Customizable button colors, sizes, and text styles.
- Callback function to handle changes to the item count.
- Smooth animations for a visually appealing user experience.


With Item Count Number Button, you can effortlessly integrate an intuitive item count functionality into your Flutter application, enhancing the user experience and making it easier for users to manage quantities.

## Installation

Add item_count_number_button as a dependency in your pubspec.yaml file:

```yaml
dependencies:
  item_count_number_button: ^1.0.0

```

## Getting started

Import the package in your Dart file:

```dart
import 'package:item_count_number_button/item_count_number_button.dart';
```

Use the ItemCount widget in your Flutter app:

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

The ItemCount widget accepts the following properties:

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

You can find a complete example in the example directory of this package.

## License

This Flutter package is released under the MIT License.


## Additional information

Welcome contributions to Item Count Number Button! If you encounter any issues, have suggestions for improvements, or would like to add new features, please feel free to open an issue or submit a pull request. Your contributions can help make this package even better.

