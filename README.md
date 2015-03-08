# Operaciones

package operaciones;
import java.util.*;
public class Operaciones {

   
    public static void main(String[] args) {
        Scanner lec=new Scanner(System.in);
        int A,B,C,D,OP;
        
        System.out.println("Introduzca dos numeros");
        System.out.println("");
        System.out.println("Introduzca el primer nuemro");
        A=lec.nextInt();
        System.out.println("Introduzca el segundo nuemro");
        B=lec.nextInt();
        
        System.out.println("Operacion a realizar");
        System.out.println("1)Sumar");
        System.out.println("2)Restar");
        System.out.println("3)Multiplicar");
        System.out.println("4)Dividir");
        System.out.println("5)Modular");
        System.out.println("que operacion desea realizar");
        OP=lec.nextInt();
        C=A+B;
        D=A-B;
        if(OP==1){
            System.out.println(A+" + "+B+" = "+C);    
        }
        if(OP==2){
            System.out.println(A+" - "+B+" = "+D);   
        }
        if(OP==3){
            System.out.println(A+" * "+B+" = "+A*B);
        }
        if(OP==4){
            System.out.println(A+" / "+B+" = "+A/B);
        }   
        if(OP==5){
            System.out.println(A+" % "+B+" = "+A%B);
        }
        
        
    }
    
}

