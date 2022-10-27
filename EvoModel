import java.util.*;

public class EvoModel {
     public static void main(String[] args) {
        Scanner userInput = new Scanner(System.in);
    } // End of main

    class World {
        // ArrayList for Creatures
        ArrayList<List<String>> totalCreatures = new ArrayList<List<String>>();

        String region = new String();

        int temperature;

        public void createRegion(String name) {

            region = name;

            //Only two regions
            if(region.equals("Frostlands")){
                temperature = 0;
              }
            if(region.equals("The Vale")){
                temperature = 90;
              }

        } // End of region

        public void createCreature(String creatureName) {

            if(creatureName.equals("Human")){
              }
            else if(creatureName.equals("Not Human")){
              }
        } // End of create creature
    } // End of World

    interface Odds {
        public void chanceToReproduce();
        public void lifeSpanDecrease();
    } // End of interface

    class Creature {
        int lifeSpan;

        int remainingLifeSpan;

        int chanceToReproduce;

        public int getRemainingLifeSpan(String creature){
            return 1;
          }

        public void die(){
          }

        public void reproduce(){
          }

    } // End of creature

    class Human extends Creature implements Chances {
        public void chanceToReproduce(){
          }

        public void lifeSpanDecrease(){
          }
    } // End of Human

    class NotHuman extends Creature implements Chances {
        public void chanceToReproduce(){
          }

        public void lifeSpanDecrease(){
          }
    } // End of Not Human
} // End of program
