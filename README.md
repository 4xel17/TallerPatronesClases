## Especificaciones Taller Patrones Creacionales 
- Pizza Factory
  Funciona mediante un menu, a la hora de ejecutarse el programa te pide que eligas que tipo de maza quieres gruesa integral o  delgada todo desde el PreparadorPizza.java
- Game Refactoring
  Funciona mediante una de hoja configuracion la cual es esta  (DYAS-GoF-CreationalPatterns-GameRefactoring/src/main/resources/config.properties) en la cual tendras que poner algunas de estas 3 opciones para que cambie el modo de juego
           Para el modo SPRITE
          - factory.class=com.balitechy.spacewar.main.SpriteGameFactor
          Para el modo VECTOR
          - factory.class=com.balitechy.spacewar.main.VectorGameFactory
          Para el modo Colorful
          - factory.class=com.balitechy.spacewar.main.ColorfulVectorGameFactory

  Luego ejecutas el game.java (DYAS-GoF-CreationalPatterns-GameRefactoring/src/main/java/com/balitechy/spacewar/main/Game.java)
  y automaticamente cambiara el estilo del jeugo
