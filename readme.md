#mario bross
@startuml diagrama

class usuario
class mascota 
 -felicd        
 
class juego 
class felicidad
class porcentaje

usuario o-- mascota
Mascota +-- Felicidad
Juego *-- usuario
Juego *-- Mascota 
Felicidad -- porcentaje
@end