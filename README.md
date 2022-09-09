# weatherTempratureProgram

import java.util.Scanner;
class Main {
    public static void main(String[] args) {
        Scanner inp= new Scanner(System.in);
        int hava;

        System.out.println("Lütfen Hava Sıcaklığını Giriniz: " );
        hava=inp.nextInt();
        System.out.print((hava <5) ? "Kayak yapabilisin" :"");
        System.out.print((hava >= 5 && hava<=15) ? "Sinema yapabilisin" :"");
        System.out.print((hava > 15 && hava<=25) ? "Piknik yapabilisin" :"");
        System.out.print((hava > 25) ? "Yüzme yapabilisin" :"");

    }
}
