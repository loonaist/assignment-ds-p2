# assignment-ds-p2
Part 2 of the assignment

import java.util.Random;
public class Q2 {
    public static void main(String[]args){
        Random rnd = new Random();
        int tickets;
        System.out.print("The number of tickets the customer has is: ");
        tickets = 1 + rnd.nextInt(10);
        System.out.println(tickets);
        
    }
}
