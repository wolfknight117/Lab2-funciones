# Lab2-funciones
package javaapplication1;

public class JavaApplication1 {

    public static void main(String[] args) {
        // TODO code application logic here
    }
    
    public void llenarMatriz(int a){
        int M[][]= new int[a][a];
        for (int i = 0; i < a; i++) {
            for (int j = 0; j < a; j++) {
                M[i][j]=0;
            }
        }
}
    public void AsiganrTurno(String nom1, String nom2){
        int a= (int) Math.floor(Math.random()*(100-1+1)+1);
        System.out.println("su numero es:"+a);
        if ((a%2)==0) {
            System.out.println(nom1+"juega primero");
        }else{
            System.out.println(nom2+"juega segundo");
        }
    
    
    
    }
            
    
}
