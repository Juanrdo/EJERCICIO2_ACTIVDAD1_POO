# EJERCICIO2_ACTIVDAD1_POO
EJERCICIO2_ACTIVDAD1_POO

package salariotrabaj;
import java.util.Scanner;
public class Salariotrabaj {

    public static void main(String[] args) {
        double  horastraba,valorhora,salnet,salbrut,retefu;
        Scanner ingresotecl = new Scanner (System.in);
        
        System.out.println("Ingrese las horas trabajadas:  ");
        horastraba = ingresotecl.nextDouble();
        
        System.out.println("Ingrese el valor de la hora:  ");
        valorhora = ingresotecl.nextDouble();
        
        salbrut= horastraba*valorhora;
        retefu= salbrut*0.125;
        salnet=salbrut-retefu;
        
        System.out.println("el salario bruto es: "+ salbrut);
        System.out.println("el salario neto es :  "+ salnet);
        System.out.println("la retencion es :  "+ retefu);
        
    }
    
}
