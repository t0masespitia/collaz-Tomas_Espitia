# collaz-Tomas_Espitia
# Paso a paso de como se fue solucionando el parcial

## Primero creaamos el repositorio
https://github.com/t0masespitia/collaz-Tomas_Espitia.git
## Luego creamos dos carpeta la cual llamamos math-service y proxy-servise(En cada una hicimos un pom y un proyecto maven distinto para asi no confundirme con el funcionamiento de cada una)
![alt text](CapturasPantalla/image.png)
## Luego modificamos el  pom con el que el profesor nos proporciono
![alt text](CapturasPantalla/pom.png)
## Luego creamos las clases que nos da previamente como controllers
## Ahora vamos a crear la instancia en aws para poder seguir con el parcial
![alt text](CapturasPantalla/instancias.png)
Le abilitamos en puerto 22 y el puerto 8080 a cada una ya que son los que vamos a utilizar
## Nos conectamos por medio de ssh con el siguiente comando
### ssh -i "Parcial.pem" ec2-user@ec2-34-205-8-88.compute-1.amazonaws.com
![alt text](CapturasPantalla/ssh.png)
## Realizamos la instalacion de java 
![alt text](CapturasPantalla/java.png)
## Ahora vamos a desplegar nuestro repositorio dentro de la instacia de aws
![alt text](CapturasPantalla/git.png)
## Revisamos que haya quedado bien clonado
![alt text](CapturasPantalla/clonado.png)
## Instalamos maven 
![alt text](CapturasPantalla/mvn.png)
## Verificamo que en proxy podamos prender el servidos la cual esta por el puesto 8080
![alt text](CapturasPantalla/puertoproxy.png)
![alt text](CapturasPantalla/springproxy.png)