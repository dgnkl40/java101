import java.util.Scanner;
public class sayıSıralama {
    public static void main(String[] args) {
        Scanner girdi = new Scanner(System.in);
        int a, b, c;
        System.out.print("İlk Sayıyı Gir: ");
        a = girdi.nextInt();
        System.out.print("İkinci Sayıyı Gir: ");
        b = girdi.nextInt();
        System.out.print("Üçüncü Sayıyı Gir: ");
        c = girdi.nextInt();

        if ((a > b) && (a > c)) {
            if (b > c) {
                System.out.print("a > b > c");
            }
            else{
                System.out.print("a>c>b");
            }
        } else if ((b > c) && (b > a)){
           if (a > c) {
               System.out.print("b > a > c");
           }
           else {
               System.out.print("b > c > a");
           }
        }
        else if ((c > a) && (c > b)){
            if (a > b){
                System.out.print("c > a > b");
            }
            else {
                System.out.print("c > b >");
            }
        }
    }
}
