# Ejercicio-Tema8

class Persona{

private int edad;

private String nombre;

private String telefono;







public int getEdad(){

         return this.edad; 
  
 }
 
 
 public int setEdad(edad){
 
        this.edad = edad;
 
 }
 
 
 public String getNombre(){
 
       return this.nombre;
       
}

public String setNombre(nombre){

       this.nombre = nombre;
       
}

public String getTelefono(){

       return this.nombre;
       
}

public String setTelefono(telefono){

       this.telefono = telefono;
       
   }
  
}


class Main{


     public static void main(String[] args){
     
     Persona persona = new Persona();
     
     persona.setEdad(35);
     
     persona.setNombre("Juan");
     
     persona.setTelefono("654834593");
     
     System.out.println(persona.getEdad());
     
     System.out.println(persona.getNombre());
     
     System.out.println(persona.getTelefono());
     
 }
    
   
     
