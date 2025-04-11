ChiliToGo.java
```
import java.util.Scanner;

public class ChiliToGo {
    public static void main(String[] args) {
        // Create a Scanner object to read input
        Scanner scanner = new Scanner(System.in);

        // Prompt user for number of adult meals
        System.out.print("Enter the number of adult meals: ");
        int adultMeals = scanner.nextInt();

        // Prompt user for number of child meals
        System.out.print("Enter the number of child meals: ");
        int childMeals = scanner.nextInt();

        // Calculate total money collected for adult meals
        double adultRevenue = adultMeals * 7.0;

        // Calculate total money collected for child meals
        double childRevenue = childMeals * 4.0;

        // Calculate total money collected for all meals
        double totalRevenue = adultRevenue + childRevenue;

        // Display results
        System.out.println("Total money collected for adult meals: $" + adultRevenue);
        System.out.println("Total money collected for child meals: $" + childRevenue);
        System.out.println("Total money collected for all meals: $" + totalRevenue);

        // Close the Scanner object
        scanner.close();
    }
}
