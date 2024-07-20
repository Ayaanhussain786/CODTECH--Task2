
# Temperature Conversion Tool

## Objective
The objective of this program is to convert temperatures between Celsius, Fahrenheit, and Kelvin. Users can input a temperature value and choose the conversion type.

## Key Components
1. **User Input:**
   - The program prompts the user to select a conversion type (Celsius to Fahrenheit/Kelvin, Fahrenheit to Celsius/Kelvin, or Kelvin to Celsius/Fahrenheit).
   - The user also inputs the temperature value.

2. **Conversion Functions:**
   - The program provides six conversion functions:
     - `celsiusToFahrenheit`: Converts Celsius to Fahrenheit.
     - `celsiusToKelvin`: Converts Celsius to Kelvin.
     - `fahrenheitToCelsius`: Converts Fahrenheit to Celsius.
     - `fahrenheitToKelvin`: Converts Fahrenheit to Kelvin.
     - `kelvinToCelsius`: Converts Kelvin to Celsius.
     - `kelvinToFahrenheit`: Converts Kelvin to Fahrenheit.

3. **Switch Statement:**
   - Based on the user's choice, the program calls the appropriate conversion functions.
   - It displays the converted values for both Fahrenheit and Kelvin (if applicable).

4. **Error Handling:**
   - If the user enters an invalid choice, the program displays an error message.

## Example Usage
1. User selects option 1 (Celsius to Fahrenheit and Kelvin).
   - Input temperature: 25°C
   - Output:
     - 25°C = 77°F
     - 25°C = 298.15K

2. User selects option 2 (Fahrenheit to Celsius and Kelvin).
   - Input temperature: 68°F
   - Output:
     - 68°F = 20°C
     - 68°F = 293.15K

3. User selects option 3 (Kelvin to Celsius and Fahrenheit).
   - Input temperature: 300K
   - Output:
     - 300K = 26.85°C
     - 300K = 80.33°F
