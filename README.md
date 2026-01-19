# java-problems
We created the ATM simple function it's we first enter pin and required amount then it will check your balance then it  money out if balance over the balance this it will show the balance amount  
import java.util.Scanner;

public class ATM {
    static void main(String[] args) {
        Scanner atm = new Scanner(System.in);
        System.out.println("Plese enter your PIN");
        int pin = atm.nextInt();
        System.out.println(pin);
        System.out.println("Plese enter your reqered amound");
        int amount = atm.nextInt();
        System.out.println(amount);
        int Balance = 5000;
        int remain = Balance - amount;
        if (Balance > amount) {
            System.out.println("plese take your ammout"+" " +remain);
        } else if (Balance >= amount) {
            System.out.println("take ammount and you no have balaence" +" " +remain);
        } else {
            System.out.println("your balence is insuffecent"+"   " + remain);
        }
        }
        }
