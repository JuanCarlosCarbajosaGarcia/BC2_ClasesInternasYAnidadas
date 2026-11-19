9. Clases internas y anidadas Parte A. Crea la clase Casa con el atributo privado direccion. • Clase interna no estática Habitacion, con nombre y un método imprimir() que muestre el nombre de la habitación y la dirección de la casa.• Clase anidada estática pública Constructora, con nombre.
   • En Main, crea una habitación con casa.new Habitacion("Salón") y una
   constructora con new Casa.Constructora("Obras Sur"), esta última sin crear
   ninguna casa.
   • Anota en un comentario por qué Habitacion puede leer direccion aunque
   sea privada y por qué Constructora no necesita una casa.
   Parte B. Crea la clase Pila de String, con una clase anidada estática y privada
   Nodo (dato y siguiente).
   • Métodos apilar(String), desapilar() (devuelve el dato de arriba y lo
   elimina; devuelve null si la pila está vacía), cima() (devuelve el dato de
   arriba sin eliminarlo), estaVacia() y getTamano().
   • En Main, apila tres cadenas, muestra la cima y el tamaño, y desapila hasta
   vaciarla comprobando que salen en orden inverso al de entrada.