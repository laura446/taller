# taller
import java.util.*;

public class Main {
    public static void main(String[] args) throws Exception {
        
        int resultado;//variable para que se guarde el resultado de los parametros
   resultado=suma(10,8,67);//llamado de la funcion
      
        System.out.println(resultado);
        coche micoche = new coche();
         micoche.adicionar_puerta();
          micoche.adicionar_puerta();
           micoche.adicionar_puerta();
          System.out.println(micoche.adicionar_puerta);
    }
    
    public static int suma( int a, int b, int c){
        return a+b+c;
        
    }

    
}
 class coche{
     public int puertas= 0;
     public void adicionar_puerta(){
         this.puertas--;
     }
 }
