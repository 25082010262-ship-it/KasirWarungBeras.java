import java.util.Scanner;

public class MyClass {
  public static void main(String[] args) {
    double total = 0.0;
      Scanner scanner = new Scanner(System.in);
    
    System.out.println("### Kasir Warung Beras ###");
        System.out.print("Jumlah Beras: ");
        double jumlah = scanner.nextInt(); 
        System.out.print("Harga Beras: ");
        double harga = scanner.nextInt(); 
        System.out.print("Uang Diterima: ");
        double uang = scanner.nextInt(); 

    total=(jumlah*harga)-(jumlah*harga*0.05);
    uang=uang-total;
    System.out.println(uang);
    }
    }

    
