# Simple Java Calculator

This project is a simple command-line calculator implemented in Java. It allows users to perform basic arithmetic operations including addition, subtraction, multiplication, and division. The program takes two user inputs and performs the desired operation based on the user's choice.

## Features

- Addition of two numbers
- Subtraction of two numbers
- Multiplication of two numbers
- Division of two numbers, with a check for division by zero

## Usage

The program runs in the command line and interacts with the user to perform calculations. Here is how the program works:

1. The user is prompted to enter two numbers.
2. The user selects an operation:
   - 1 for Addition
   - 2 for Subtraction
   - 3 for Multiplication
   - 4 for Division
3. The program performs the selected operation and displays the result.
4. If division by zero is attempted, the program will display an error message.

## How to Run

To run this project, you need to have Java installed on your computer. Follow these steps:

1. Save the `Main.java` file.
2. Open a terminal and navigate to the directory where the file is saved.
3. Compile the program using the following command:

   ```sh
   javac Main.java
   ```

4. Run the program using the following command:

   ```sh
   java Main
   ```

5. Follow the prompts to enter two numbers and select an operation.

## Example Output

```
Birinci sayıyı giriniz:
5
İkinci sayıyı giriniz:
3
İşlem seçiniz:
Toplama için -->1, Çıkartma için -->2, Çarpma için -->3, Bölme için -->4 seçiniz:
1
Sayıların toplamı: 8
```

## Code Overview

The main parts of the code include:

- **User Input**: The program takes two integers as input using the `Scanner` class.
- **Operation Selection**: The user selects an arithmetic operation from a menu.
- **Switch Statement**: A switch statement handles the different operations based on user input.
- **Division Check**: The code includes a check to prevent division by zero, ensuring the program handles errors gracefully.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- **Hekim Can Aktas** - [GitHub](https://github.com/hekimcanaktas)

