# Java-Experiment-2

# Find the numbers of days in a month

## Aim:
  To write a Java program to find the number of days in a month
  
## Algorithm:

Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class and name it NumberDays.

Step 3 : Using Scanner, we can input numbers from the user.

Step 4 : Write the logic for the program using Switch cases.

Step 5 : Display the operations done the input in the terminal.

## Program:
```
Developed by: S.Sham Rathan
Register.no : 212221230093

import java.util.Scanner;
public class Main {
    public static void main(String[] strings) {

        Scanner input = new Scanner(System.in);

        int number_Of_DaysInMonth = 0;
        String month = input.next();

        switch (month) {
            case "January":
                number_Of_DaysInMonth = 31;
                break;
            case "February":
                number_Of_DaysInMonth = 28;
                break;
            case "March":
                number_Of_DaysInMonth = 31;
                break;
            case "April":
                number_Of_DaysInMonth = 30;
                break;
            case  "May":
                number_Of_DaysInMonth = 31;
                break;
            case "June":
                number_Of_DaysInMonth = 30;
                break;
            case "July":
                number_Of_DaysInMonth = 31;
                break;
            case "August":
                number_Of_DaysInMonth = 31;
                break;
            case  "September":
                number_Of_DaysInMonth = 30;
                break;
            case "October":
                number_Of_DaysInMonth = 31;
                break;
            case "November":
                number_Of_DaysInMonth = 30;
                break;
            case "December":
                number_Of_DaysInMonth = 31;
        }
        System.out.print(month + " has " + number_Of_DaysInMonth + " days\n");
    }
}
```




## Output:
![image](https://github.com/ShamRathan/Java-Experiment-3/assets/93587823/a6de80c1-8dac-4de4-9a07-f8576f891e76)




## Result 
  We have successfully created a Java program to display the numbers of days in a month
