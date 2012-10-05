Hola-Mundo-Multi-Idiomas
========================
package botonaleatorio;

public class Botonaleatorio{
   public static void main(String[] args)throws Exception{
       String[] palabras1={"hola mundo","hello world","你好世界","Hallo Welt","helo byd", "γεια σας κόσμο", "हैलो दुनिया", "salve mundi", "こんにちは世界", "hello, világ","привет мир","Olá mundo","kumusta mundo"};
       String[] palabras2={"muere"};
           
           int aleatorio1=(int)(Math.random()*palabras1.length);
            int aleatorio2=(int)(Math.random()*palabras2.length);
           
           String frase=palabras1[aleatorio1] + palabras2[aleatorio2];
           System.out.println(frase);
   
   }
}

Es un programa básico que muestra una lista de como decir Hola mundo en diferentes idiomas aleatoria mente escojidos