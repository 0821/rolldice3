rolldice3

public class Dicemain {
  public static void main (String [] args)
  {
  	
  	for (int counter =1; counter <=20; counter ++){
  		Dice RollDice1 = new Dice();
  		System.out.printf("%d ", RollDice1.RollDice(2));
  	
  }
  }}
import java.util.Random;
public class Dice {

  
  int RollDice(int DiceNumber){	
  	return (int) (1 + Math.random()*6 * (DiceNumber));
  }
  int Roll_1_Dice(){
  	return (int) (1 + Math.random()* 6);
  }
  
  
  
  public static void main (String [] args)
  {
  	
  	for (int counter =1; counter <=20; counter ++){
  		Dice RollDice1 = new Dice();
  		System.out.printf("%d ", RollDice1.RollDice(2));
  	
  }


}
}

=========
