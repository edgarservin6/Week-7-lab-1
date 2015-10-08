import javax.swing.JOptionPane
  
  public class GUI 
{
  public static void main( String[] args )
  {
   int userNum ;
   String big = " Sorry, number too big";
   String small = " Soory, number too small " ;
   String message = String.format( " You are correct" );
   String sinput
   
   int rand = int random = 0 + (int) ( Math.random() * 10 );
   String name = JOptionPane.showInputDialog( " Guess a number between 1 and 10 ");
   userNum = Interger.parseInt(sinput);
   
   
   if (userNum > rand) || userNum < rand) 
     message =String.format(" the number %s is wrong", userNum);
     
    else (userNum == rand )
      message = String.format(" the number is correct"); 
    
  }
  
}
