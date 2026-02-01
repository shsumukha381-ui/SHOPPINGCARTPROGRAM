# SHOPPINGCARTPROGRAM
Simple Java console-based shopping cart program to practice core programming fundamentals
import java.util.Scanner;





public class shoppin {
    public static void main(String[] args) {
        ///SHOPPING CART PROGRAM
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter item you would like to buy :   ");
        String item = scanner.nextLine();
        System.out.print("Enter the price of the item :  ");
        double price = scanner.nextDouble();
        scanner.nextLine();
        System.out.print("How many you would like :  ");
        double number = scanner.nextInt();
        System.out.println("you have bought  " + number + " " + item);
        double total_price = number*price;
        System.out.println("the total is" +  " " + total_price + "INR");
        scanner.close();
        
        
        

    }
}
