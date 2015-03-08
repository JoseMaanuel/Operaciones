# Operaciones

package operaciones;

import java.util.*;
public class Operaciones {

   
    public static void main(String[] args) {
       int a,b,op;
        Scanner lec=new Scanner(System.in);
       
        System.out.println("Escribe un numero");
        a=lec.nextInt();
        
        System.out.println("Escribe otro numero");
        b=lec.nextInt();
        do{
        System.out.println("seleccione la operacion a realizar");
        System.out.println("1)Suma \n 2)Resta \n 3)Multiplicacion \n 4)Division \n 5)Modular \n");
        op=lec.nextInt();
        /*
        if(op==1){
            // suma
        }else if(op==2){
            // resta
        }else if(op==3){
            // multiplicacion
        }else if(op==4){
            // division
        }else if(op==5){
            // modular
        }*/
        
        switch(op){
            case 1:
                System.out.println("Suma");
                System.out.println(a+b);
                break;
            case 2:
                System.out.println("Resta");
                System.out.println(a-b);
                break;
            case 3:
                System.out.println("Multiplicacion");
                System.out.println(a*b);
                break;
            case 4:
                System.out.println("Division");
                System.out.println(a/b);
                break;
            case 5:
                System.out.println("Modular");
                System.out.println(a%b);
                break;
            default:
                System.out.println("La opcion es incorrecta");
                break;
        }
    }while(op>5);
        
    }
}
