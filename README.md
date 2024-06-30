# InputTypeQuestions
Java Input Type Questions
This program demonstrates how to take input from the user using the Scanner class and ask simple questions.

java

Open In Editor
Edit
Copy code
import java.util.Scanner;

public class InputQuestions {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Ask the user for their name
        System.out.print("What is your name? ");
        String name = scanner.nextLine();
        System.out.println("Hello, " + name + "!");

        // Ask the user for their age
        System.out.print("How old are you? ");
        int age = scanner.nextInt();
        scanner.nextLine(); // Consume the newline character
        System.out.println("You are " + age + " years old.");

        // Ask the user for their favorite color
        System.out.print("What is your favorite color? ");
        String color = scanner.nextLine();
        System.out.println("Your favorite color is " + color + ".");
    }
}
GitHub README.md
Java Input Type Questions
This repository contains a simple Java program that demonstrates taking user input and asking simple questions.

Description
The program uses the Scanner class to read input from the user and asks for:

Name - String
Age - Integer
Favorite color - String
After receiving input, the program prints a personalized greeting and information about the user.

How to Run
Clone the repository:
bash

Open In Editor
Edit
Run
Copy code
git clone https://github.com/your-username/java-input-questions.git
Compile the program:
bash

Open In Editor
Edit
Run
Copy code
javac InputQuestions.java
Run the program:
bash

Open In Editor
Edit
Run
Copy code
java InputQuestions
The program will prompt you for the required information and then display the results.

Contributing
Feel free to fork this repository and improve the program. You can add more questions, different input types, or improve the user interface.

License
This project is licensed under the MIT License - see the LICENSE file for details.




