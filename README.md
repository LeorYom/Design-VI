# Engineering Design VI
**Welcome**

*By Leor Yomtobian*
>  ```Always turn a negative situation into a positive situation```
## Favorite foods
1. Pasta
2. Steak
3. Pizza
## Things I like to do
- Play sports
- Meet new people
- Play piano
## Java code 
`	import java.util.Scanner;`

`public class Year {`

`/** Calls isLeapYear to print correct statement.`

`     *  @param  year to be analyzed`

`     */`

`    private static void checkLeapYear(int year) {`

`        if (isLeapYear(year)) {`

`            System.out.printf("%d is a leap year.\n", year);`

`        } else {`

`            System.out.printf("%d is not a leap year.\n", year);`

`        }`

`    }`

`    /** Return true if YEAR is a leap year.  */`

`    static boolean isLeapYear(int year) {`

`        // return (year % 400 == 0) || (year % 4 == 0) && (year % 100 == 0);`

`        if (year % 4 == 0) {`

`            if (year % 100 != 0){`

`                return true;`

`        }`

`            return true;`

`            }`

`        if (year % 400 == 0){`

`            return true;`

`        }`

`        else {`

`            return false;`

`        }`

`    }`

` /** Must be provided an integer as a command line argument ARGS. */`

`    public static void main(String[] args) {`

`        if (args.length < 1) {`

`            System.out.println("Please enter command line arguments.");`

`            System.out.println("e.g. java Year 2000");`

`            Scanner reader = new Scanner(System.in);  // Reading from System.in`

`            System.out.println("Enter a number: ");`

`            int n = reader.nextInt(); // Scans the next token of the input as an int.`

`//once finished`

`            reader.close();`

`            checkLeapYear(n);`

`        }`

`        for (int i = 0; i < args.length; i++) {`

`            try {`

`                int year = Integer.parseInt(args[i]);`

`                checkLeapYear(year);`

`            } catch (NumberFormatException e) {`

`                System.out.printf("%s is not a valid number.\n", args[i]);`

`            }`

`        }`

`    }`

`}`

---
## Link 
[ServantsOfRuin](https://www.servantsofruin.com)

## Image
![StevensLogo](https://github.com/LeorYom/Design-VI/assets/117100347/f84da33b-23ad-4f8b-9ea4-5bbbe9bed1bc)
















