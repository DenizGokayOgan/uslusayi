# uslusayi

    import java.util.Scanner;

    public class Main {
    public static void main(String[] args) {
        int n,r,total= 1;
        int i;
        Scanner input = new Scanner(System.in);
        System.out.print("Bir sayı girin: ");
        n = input.nextInt();
        System.out.print("Bir üs girin: ");
        r = input.nextInt();
        for(i=1 ; i<=r; i++){
        total = total*n;
        }

        System.out.println("Sonuç: " +total);
    }
    }
