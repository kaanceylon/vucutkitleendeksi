# vucutkitleendeksi
Java ile kullanıcıdan boy ve kilo değerlerini alıp bir değişkene atayın. Aşağıdaki formüle göre kullanıcının "Vücut Kitle İndeks" değerini hesaplayıp ekrana yazdırın.


import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

      double boy, kilo, vke;

      Scanner input = new Scanner(System.in);
      System.out.println("Boy: ");  
      boy = input.nextDouble();

      System.out.println("Kilo: ");
      kilo = input.nextDouble();

      vke = (kilo / boy * boy);
      System.out.println("Vücut Kitle Endeksiniz : " + vke );
    }
}
