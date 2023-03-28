# investigacion_semaforos

## Concepto básico de semáforo

Un semáforo es un mecanismo de sincronización que se utiliza   
en sistemas operativos para controlar el acceso a recursos   
compartidos entre procesos o hilos de ejecución. 

De esta manera un semaforo S es una variable que, aparte de   
la inicializacion, solo puede acceder por medio de 2   
operaciones atomicas y mutuamente exclusivas:

* Wait(S): que significa "Espera".  
* Signal(S): que significa que se "Retire".  

Para evitar la espera ocupada: cuando un proceso tiene que   
esperar, se pondra en una cola de procesos bloqueados   
esperando un evento.

## Tipos de Semaforos

### Semaforos binarios

* Solo puede tener dos valores, 0 y 1.

* En windows se llama mutex.

### Semaforos generales o enteros

* Pueden tomar muchos valores positivos.

## Relacion entre los semáforos y la sincronización 

Los semáforos son un mecanismo fundamental de sincronización   
en sistemas operativos, ya que permiten a los procesos o hilos   
de ejecución coordinar su acceso a recursos compartidos y evitar   
condiciones de carrera.

Explicado mas a detalle los semaforos proporcionan un mecanismo para que   
los procesos o hilos de ejecución se sincronicen y se aseguren de que   
solo un proceso acceda al recurso compartido en un momento dado.   
Los semáforos permiten a los procesos bloquearse y esperar a que el   
recurso esté disponible, en lugar de intentar acceder al recurso al   
mismo tiempo.

## Conclucion 

Los semáforos son una herramienta de sincronización esencial en sistemas   
operativos, ya que permiten que los procesos o hilos de ejecución coordinen   
su acceso a recursos compartidos y eviten condiciones de carrera, lo que   
garantiza la estabilidad y consistencia del sistema.
