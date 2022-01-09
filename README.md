# -RNEK-JAVA-KODLARI
10 ADET ÖRNEK JAVA ÇÖZÜMÜ
https://www.youtube.com/watch?v=8I1XrgEi-vc&t=1978s
1.soru)Bir ücretlinin sicil numarası,çalışma saati ve saatlik ücreti bilgisayara giriş olarak veriliyor.ücretlinin bu bilgilerle maaşını hesaplayan  algoritmayı bulup java kodunu yazınız.                                                                                                                                                         1.SORUNUN JAVA KODU
package ornek1;
import java.util.Scanner;
public class ORNEK1 {

    public static void main(String[] args) {
        Scanner input=new Scanner(System.in);
        int sicilno,saatüc,çasa,maaş;
        System.out.println("sicil no giriniz:");
        sicilno=input.nextInt();
        System.out.println("saatüc giriniz:");
        saatüc=input.nextInt();
        System.out.println("çasa giriniz");
        çasa=input.nextInt();
        maaş=(saatüc*çasa);
        System.out.println("maaş:"+maaş);
2.SORU)Klavyeden girilen iki sayının çarpımını veren algoritmayı bulup java kodunu yazınız.                                                                                  2.SORUNUN JAVA KODU                                                      
package ornek2;
import java.util.Scanner;
public class ORNEK2 {

    public static void main(String[] args) {
        Scanner input=new Scanner(System.in);
        int a,b,çarpım;
        System.out.println(" bir a sayısı griniz:");
        a=input.nextInt();
        System.out.println("bir b sayısı giriniz:");
        b=input.nextInt();
        çarpım=(a*b);
        System.out.println("çarpım:"+çarpım);
3.SORU)Klavyeden girilen iki sayıdan büyük olanı bulup ekrana yazdıran algoritmayı bulup java kodunu yazınız.                                                                3.SORUNUN JAVA KODU
package ornek3;
import java.util.Scanner;
public class ORNEK3 {

    public static void main(String[] args) {
        Scanner input=new Scanner(System.in);
        int a,b,;
        System.out.println(" bir a sayısı griniz:");
        a=input.nextInt();
        System.out.println("bir b sayısı giriniz:");
        b=input.nextInt();
        if (a<b){
            System.out.println("b sayısı a sayısından büyüktür");
        }else{
            System.out.println("a sayısı b sayısından büyüktür");
4.SORU)Klavyeden girilen herhangi bir sayının negatif veya pozitif olduğu bulup ekrana yazdıran algoritmanın java kodunu yazınız.                                         4.SORUNUN JAVA KODU
package ornek4;
import java.util.Scanner;
public class ORNEK7 {

    public static void main(String[] args) {
        Scanner input=new Scanner(System.in);
        int sayı;
        System.out.println("bir sayı giriniz");
        sayı=input.nextInt();
        if (sayı<0){
            System.out.println("sayı negatiftir");
        }else{
            System.out.println("sayı pozitiftir");
5.SORU)Klavyeden girilen yaş kriterindeki şahsın reşit olup olmadığını ekrana yazdıran algoritmayı bulup java kodunu yazınız.                                           5.SORUNUN JAVA KODU
package ornek4;
import java.util.Scanner;
public class ORNEK4 {

    public static void main(String[] args) {
        Scanner input=new Scanner(System.in);
        byte yaş;
        System.out.println("yaş giriniz");
        yaş = input.nextByte();
        if (yaş<18){
        System.out.println("reşit değilsiniz");
        }else{
            System.out.println("reşitsiniz");
6.SORU)Klavyeden girilen vize ve final notlarından yıl sonu ortalamasını hesaplayan algoritmayı bulup java kodunu yazınız.                                               6.SORUNUN JAVA KODU
         package ornek5;
import java.util.Scanner;
public class ORNEK5 {

    public static void main(String[] args) {
        Scanner input=new Scanner(System.in);
      double vizenotu,finalnotu,ort;
      System.out.println("vizenotu gir:");
      vizenotu=input.nextDouble();
      System.out.println("finalnotu gir:");
      finalnotu=input.nextDouble();
      ort=(vizenotu*0.4+finalnotu*0.6);
      System.out.println("ort:"+ort);
7.SORU)Klavyeden girilen vize ve final notlarından ortalamayı hesaplayıp,öğrencinin dersi geçip geçmediğini ekrana yazdıran algoritmayı bulup java kodunu yazınız.             7.SORUNUN JAVA KODU
package ornek6;
import java.util.Scanner;
public class ORNEK6 {

    public static void main(String[] args) {
        Scanner input=new Scanner(System.in);
      double vizenotu,finalnotu,ort;
      System.out.println("vizenotu gir:");
      vizenotu=input.nextDouble();
      System.out.println("finalnotu gir:");
      finalnotu=input.nextDouble();
      ort=(vizenotu*0.4+finalnotu*0.6);
      System.out.println("ort:"+ort);
          if (ort<50);
          System.out.println("kaldınız");
            } else {
    System.out.println("geçtiniz");
8.SORU)1’den 10’a kadar olan sayıları sırasıyla ekrana yazdıran algoritmayı bulup java kodunu yazınız.                                                                 8.SORUNUN JAVA KODU
package ornek8;

public class ORNEK8 {

    public static void main(String[] args) {
     int sayı=0;
     int toplam=0;
     for (sayı=1; sayı<11; sayı++)
         System.out.println("toplam:"+sayı);
9.SORU)Klavyeden girilen bir sayının 10’dan küçük olup olmadığını ekrana yazan algoritmayı bulup java kodunu yazınız.                                                   9.SORUNUN JAVA KODU
package ornek9;
import java.util.Scanner;
public class ORNEK9 {

    public static void main(String[] args) {
           Scanner input=new Scanner(System.in);
           int sayı;
           System.out.println("bir sayı giriniz");
           sayı=input.nextInt();
           String a=(sayı<11)? "sayı<10":"sayı>11";
           System.out.println(a);
10.SORU)Bir cümlede geçen bir anahtar kelimenin ilk geçtiği sırayı bulan algoritmayı bulup java kodunu yazınız.                                                                10.SORUNUN JAVA KODU
Package ornek10;

public class ORNEK10 {

    public static void main(String[] args) {
       String B="oryantasyon ödevi için java kodları yazıyoruz";
       System.out.println(B.indexOf("java"));
