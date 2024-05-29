# Vehículo POO Ejercicio
Este proyecto de ejemplo ilustra los conceptos fundamentales de la programación orientada a objetos (POO) en C#. Cubre temas como herencia, polimorfismo, abstracción, clases abstractas, interfaces, métodos getter y setter, uso de constructores, entre otros.
## Estructura del Proyecto
El proyecto consta de tres clases principales:
1. **Vehiculo:** Una clase abstracta que representa un vehículo genérico.
2. **Avion:** Una clase que hereda de Vehiculo e implementa la interfaz IVolador.
3. **Coche:** Una clase que hereda de Vehiculo.

## Ejemplo de Arquitectura de Carpetas en nuestro IDE

![Arquitectura Carpetas](https://github.com/adrilerna94/pildoraPOOCSharp/assets/129441318/9f608d90-e669-477c-8fe1-2854adb22470)

## Funcionalidades Principales
### Herencia
- La clase *Avion* y *Coche* heredan de la clase abstracta *Vehiculo*, lo que les permite compartir comportamientos y propiedades comunes.
### Polimorfismo
- Los métodos *Arrancar* se sobrescriben en las clases derivadas *Avion* y *Coche*, permitiendo que cada clase tenga su propia implementación del método.
- El método *Volar* en la clase *Avion* demuestra el polimorfismo al implementar la interfaz *IVolador*.
### Abstracción
- La clase *Vehiculo* es abstracta, lo que significa que no se puede crear una instancia directa de ella, sino que se utiliza como una plantilla para definir comportamientos comunes a todos los vehículos.
### Interfaces
- La interfaz *IVolador* define un contrato para los objetos que pueden volar. La clase *Avion* implementa esta interfaz.
### Constructor
- Se utiliza un constructor en cada clase para inicializar propiedades específicas al crear instancias de objetos.
## SET UP
### 1. Clona el Repositorio
```
git clone https://github.com/adrilerna94/pildoraPOOCSharp
```
### 2. Crea el Proyecto

2.1 **Creamos el Solution File**: contenedor que agrupa 1 o + proyectos
```
dotnet new sln -n NameSolution
```
2.2 **Creamos nuestro proyecto de Consola**
```
dotnet new console -n MiProyecto
```
### 3. Compila y Ejecuta
Para compilar y ejecutar tu proyecto en Visual Studio Code, puedes usar la terminal integrada o el terminal de tu sistema operativo. Aquí hay algunos comandos comunes que podrías usar:
- **Compila el proyecto:**
  ```
  dotnet build
  ```
- **Compila y ejecuta la aplicación:**
  ```
  dotnet run
  ```
### Explorar el Código
Explore las clases y métodos para comprender cómo se implementan los conceptos de programación orientada a objetos en C#.
## SUGERENCIAS
**KEEP CALM & ENJOY**

*Cuando acabes recuerda hacer un git pushito finas hierbas*




