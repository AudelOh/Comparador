# Comparador
Cree una aplicación que nos permita ingresar un nombre ya definido, pedir al usuario que ingrese ese nombre y confirmar si es el correcto de lo contrario decirle que se a equivocado.

package comparestrings;

import java.util.Scanner;
/**
 *
 * @author AudiGS
 */
public class CompareStrings{
    
    public static void main(String[] args){
        
        String aNombre = "Audel";
        
        String anotherNombre;
        
        Scanner input = new Scanner(System.in);
        
        System.out.print("Escribe tu nombre > ");
        
        anotherNombre = input.nextLine();
        
        if(aNombre.equals(anotherNombre))
            
        System.out.println(aNombre + " Ese es tu nombre " + anotherNombre);
        else
        System.out.println(aNombre + " Ese no es tu nombre ");
    }
}
