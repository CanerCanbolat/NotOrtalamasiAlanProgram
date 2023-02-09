# NotOrtalamasiAlanProgram
Java ile Matematik, Fizik, Kimya, Türkçe, Tarih, Müzik derslerinin sınav puanlarını kullanıcıdan alan ve ortalamalarını hesaplayıp ekrana bastırılan programı yazın. Aynı program içerisinde koşullu ifadeler kullanılarak, eğer kullanıcının ortalaması 60'dan büyük ise ekrana "


import java.util.Scanner;
public class N {
    public static void main(String[] args) {
int mat, fizik,kimya,turkce,tarih,muzik ;
Scanner hsp = new Scanner(System.in);
System.out.print("Matematik notunu giriniz : ");
mat = hsp.nextInt();

        System.out.print("Fizik notunu giriniz : ");
        fizik = hsp.nextInt();
        System.out.print("Kimya notunu giriniz : ");
        kimya = hsp.nextInt();
        System.out.print("Türkçe notunu giriniz : ");
        turkce = hsp.nextInt();
        System.out.print("Tarih notunu giriniz : ");
        tarih = hsp.nextInt();
        System.out.print("Müzik notunu giriniz : ");
        muzik = hsp.nextInt();
        double ort = (mat+fizik+kimya+turkce+tarih+muzik)/6;
        System.out.println("Ortalamanız = "+ort);
        String str = ort >= 60 ? "Sınıfı Geçti" : "Sınıfta Kaldı";
        System.out.print(str);
