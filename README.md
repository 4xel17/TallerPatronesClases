## Especificaciones Taller Patrones Creacionales 

### 🍕 Pizza Factory
El programa funciona mediante un menú.  
Al ejecutarse, te pedirá que elijas el tipo de masa que deseas: **gruesa**, **integral** o **delgada**.  

👉 Toda la lógica se encuentra en:  
[`PreparadorPizza.java`](DYAS-GoF-CreationalPatterns-PizzaFactory/src/main/java/PreparadorPizza.java)

---

### 🎮 Game Refactoring
Este programa funciona mediante un archivo de configuración ubicado en:  
[`config.properties`](DYAS-GoF-CreationalPatterns-GameRefactoring/src/main/resources/config.properties)

En este archivo debes especificar una de las siguientes opciones para cambiar el modo de juego:

- **SPRITE**  
  ```properties
  factory.class=com.balitechy.spacewar.main.SpriteGameFactory
