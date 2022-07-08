# Not Ortalama
İf else yok


         import java.util.Scanner;

         public class Main {
         public static void main(String[] args) {
         int mat,kim,tur,tar,muz;
         Scanner ma1= new Scanner(System.in);
         System.out.println("Matematik notunuzu giriniz:");
         mat = ma1.nextInt();
         System.out.println("Matematik Notunuz:"+mat);

         Scanner ki2 =new Scanner(System.in);
         System.out.println("Kimya notunuzu girinz:");
         kim=ki2.nextInt();
         System.out.println("Kimya notunuz:"+ kim);

        Scanner tu2 =new Scanner(System.in);
        System.out.println("Turkce notunuzu girinz:");
        tur=tu2.nextInt();
        System.out.println("Turkce notunuz:"+ tur);

        Scanner ta2 =new Scanner(System.in);
        System.out.println("Tarih notunuzu giriniz:");
        tar =ta2.nextInt();
        System.out.println("Tarih notunuz:"+ tar);

        Scanner mu2 =new Scanner(System.in);
        System.out.println("Muzik notunuzu giriniz:");
        muz =mu2.nextInt();
        System.out.println("Muzik notunuz:"+ muz);

        int sonuc= mat+kim+tur+tar+muz;
        sonuc/=5;
        System.out.println("Not Ortalamaniz:"+sonuc);

        boolean durum = sonuc>60;
        System.out.println(durum? "Gecti":"Kaldi");



    }
}
