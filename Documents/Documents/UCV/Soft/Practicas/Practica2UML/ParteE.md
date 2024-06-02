E1

R: Que el paquete “top” tanga una dependencia con el paquete “controllers” significa que los cambios que se puedan realizar en el paquete top llegaran a afectar al paquete controllers, tambien el funcionamiento del paquete origen (top) depende de la presencia del paquete destino (controllers)


E2

a. Los paquetes que dependen de threads son: Utils - Controllers - Top
b. 
Dependencia entrada  = 4 (Threads-Utils-Controllers-Samplers)
Dependencia salida = 6 (Todos los paquetes)

c. 

R: Si se hace un cambio en alguna de las clases del paquete “Threads” puede suceder que se afecte el comportamiento y/o funcionalidad del paquete threads 


E3 

R: Este diagrama de paquetes muestra un código con alto acoplamiento entre los paquetes. La conveniencia de este alto acoplamiento depende del diseño específico. Si el acoplamiento es demasiado bajo, la comunicación entre paquetes se dificulta. Por el contrario, un acoplamiento excesivamente alto reduce la flexibilidad del código.