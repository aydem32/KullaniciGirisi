import java.util.Scanner;

public class KullaniciGiris {
    public static void main(String[] args){

        String kullaniciAdi,password;

        Scanner input = new Scanner(System.in);

        System.out.print("Kullanıcı Adınız Giriniz : ");
        kullaniciAdi = input.nextLine();
        System.out.print("Şifrenizi Giriniz : ");
        password = input.nextLine();

        if ((kullaniciAdi.equals("patika")) && (password.equals("java123"))){
            System.out.println("Giriş Başarılı");
        } else {
            System.out.println("Giriş Başarısız");
        }

    }



}
