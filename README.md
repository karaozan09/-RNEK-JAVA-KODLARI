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
        ![image](https://user-images.githubusercontent.com/95549258/148679665-b6e679cb-b741-4174-a76e-c7b2aa754f02.png)

![image](https://user-images.githubusercontent.com/95549258/148679632-2fb6869f-7d51-4b68-be93-46ffcd24ebe7.png)
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
![image](https://user-images.githubusercontent.com/95549258/148679738-07f85d6b-62b7-4ef9-b51c-c2d8fe876151.png)
![image](https://user-images.githubusercontent.com/95549258/148679706-1ebdf86b-46f0-48b2-b9d2-95539a775cab.png)
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
![image](https://user-images.githubusercontent.com/95549258/148679827-72623734-6739-400a-944b-782264b92595.png)

![image](https://user-images.githubusercontent.com/95549258/148679795-8da70eca-5363-4c37-b341-a6cc964fd6ba.png)
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
![image](https://user-images.githubusercontent.com/95549258/148679866-01b78bf1-a309-414d-b0c2-ad0805ba968b.png)

![image](https://user-images.githubusercontent.com/95549258/148679841-14d31fcf-eeb2-4a6e-acc5-2d7927cedd6a.png)
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
![image](https://user-images.githubusercontent.com/95549258/148679909-11af470c-8490-466e-a9f3-20e27af1fdc0.png)

![image](https://user-images.githubusercontent.com/95549258/148679884-6be7b7a5-1574-4ce3-a1de-eab1051095b6.png)
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
![image](https://user-images.githubusercontent.com/95549258/148679935-b82d206d-7b20-45e9-bd93-20d166b0b3d8.png)

![image](https://user-images.githubusercontent.com/95549258/148679925-77ccb418-7a9b-42fc-be7a-529db9cef0c7.png)
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
![image](https://user-images.githubusercontent.com/95549258/148679964-c0efdfba-5969-4112-a9c7-b3be8ad44851.png)

![image](https://user-images.githubusercontent.com/95549258/148679947-b2d9880b-64e3-465c-a6f1-16bc24b9b90e.png)
8.SORU)1’den 10’a kadar olan sayıları sırasıyla ekrana yazdıran algoritmayı bulup java kodunu yazınız.                                                                 8.SORUNUN JAVA KODU
package ornek8;

public class ORNEK8 {

    public static void main(String[] args) {
     int sayı=0;
     int toplam=0;
     for (sayı=1; sayı<11; sayı++)
         System.out.println("toplam:"+sayı);
![image](https://user-images.githubusercontent.com/95549258/148679984-5f488648-fe58-4bbf-bb7d-ccb77e994189.png)

![image](https://user-images.githubusercontent.com/95549258/148679970-66adb206-2e72-4756-a38d-87268e64732f.png)
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
![image](https://user-images.githubusercontent.com/95549258/148680020-17f71183-3b11-4acd-abc5-af2a42810e02.png)

![image](https://user-images.githubusercontent.com/95549258/148679994-467abce5-d1a0-4675-9c5f-f52537fea416.png)
10.SORU)Bir cümlede geçen bir anahtar kelimenin ilk geçtiği sırayı bulan algoritmayı bulup java kodunu yazınız.                                                                10.SORUNUN JAVA KODU
Package ornek10;

public class ORNEK10 {

    public static void main(String[] args) {
       String B="oryantasyon ödevi için java kodları yazıyoruz";
       System.out.println(B.indexOf("java"));
![image](https://user-images.githubusercontent.com/95549258/148680057-3f368402-043a-4d55-87dc-7189e4a3f069.png)

![image](https://user-images.githubusercontent.com/95549258/148680038-54a6f210-b52b-4dec-9f59-392185b36434.png)

