# ilkProje-main
import java.util.Scanner;

public class Main {
    public static void main (String []args){
        int mat,fizik,kimya,turkce,tarih,muzik;

        Scanner inp= new Scanner(System.in);

        System.out.print("Matematik Notunu Giriniz: ");
        mat= inp.nextInt();

        System.out.print("Fizik Notunu Giriniz: ");
        fizik =inp.nextInt();

        System.out.print("Kimya Notunu Giriniz: ");
        kimya =inp.nextInt();

        System.out.print("Türkçe Notunu Giriniz: ");
        turkce = inp.nextInt();

        System.out.print("Tarih Notunu Giriniz: ");
        tarih= inp.nextInt();

        System.out.print("Müzik Notunu Giriniz: ");
        muzik= inp.nextInt();

        int toplam = (mat+fizik+kimya+turkce+tarih+muzik);
        double sonuc = toplam/6;


        System.out.println("Not Ortalamanız: "+ sonuc);

        String durum= sonuc>= 60? "Geçti" : "Kaldı";

        System.out.println(durum);
