# Project1
Project 1 for 554
import org.junit.Test;
import static org.junit.Assert.assertEquals;

public class File {
	
   String message = "Hello World";	
   MessageUtil messageUtil = new MessageUtil(message);

   @Test
   public void testPrintMessage() {	  
      assertEquals(message,messageUtil.printMessage());
   }
}
