# codigo_45
import java.util.Scanner;
public class MaiorMenor {
    public static void main(String[] args) {
        Scanner tcl = new Scanner(System.in);
        int a = tcl.nextInt();
        int b = tcl.nextInt();
        if(a > b){
            System.out.println("a é maior que b");
        }else if(b > a){
        System.out.println("b é maior que a");
            }else{
             System.out.println("sao iguais");
                    }       
    }
}
