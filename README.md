# Temperature-Converter

The Temperature Converter is a simple utility that allows you to convert temperatures between Celsius, Fahrenheit. This tool comes in handy when you need to quickly convert temperatures for various applications or calculations.

## Features

- Converts temperatures between Celsius, Fahrenheit, and Kelvin scales
- Easy-to-use command-line interface
- Accurate and reliable temperature conversions
- Supports positive and negative temperature values

## Installation

To use the Temperature Converter, follow these steps:

1. Clone this repository to your local machine by running the following command:

   ```
   (https://github.com/Anusha-2003/Temperature-Converter)
   ```

2. Navigate to the project directory:

   ```
   cd temperature-converter
   ```

3. Install the required dependencies:

   ```
   npm install
   ```

## Usage

To convert a temperature, run the following command:

```
node convert.js <value> <input-scale> <output-scale>
```

Replace `<value>` with the temperature value you want to convert, `<input-scale>` with the scale of the input temperature (celsius, fahrenheit, or kelvin), and `<output-scale>` with the desired output scale.

For example, to convert 25 degrees Celsius to Fahrenheit, you would run:

```
node convert.js 25 celsius fahrenheit
```

The converted temperature will be displayed on the console.

## Examples

Here are some examples of using the Temperature Converter:

- Convert 32 degrees Fahrenheit to Celsius:

  ```
  node convert.js 32 fahrenheit celsius
  ```

- Convert -10 degrees Celsius to Kelvin:

  ```
  node convert.js -10 celsius kelvin
  ```

- Convert 0 Kelvin to Fahrenheit:

  ```
  node convert.js 0 kelvin fahrenheit
  ```

## Contributing

Contributions to the Temperature Converter are welcome! If you find any issues or have suggestions for improvement, please open an issue on the [GitHub repository](https://github.com/Anusha-2003/Temperature-Converter) or submit a pull request.

When contributing, please ensure that your code follows the established coding style and conventions. Additionally, make sure to update the README with any necessary changes.

## License

The Temperature Converter is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT). Feel free to use and modify the code as per the terms of the license.

## Acknowledgements

The Temperature Converter was developed by [BHUKYA ANUSHA] and is inspired by the need for a simple and efficient temperature conversion tool.
