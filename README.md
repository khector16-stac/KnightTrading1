# KnightTrading1
1. Create a program that will take an input on the number of shares of a stock (called the Parent order) and then it will split that number into equal number of Buy purchase orders (Child orders). Minimum order is 1000. Minimum number of child orders is 10 . 
Example ; Your program takes an input of 1000 shares of Apple, and there are 10 orders of 100 shares each. I would like to see output of of the Parent order and the child orders. you must make sure that your child orders equal the parent order.
Input :
number of Shares ? [ 1000 Apple ]
number of child orders ? : [ 10 ]

Output should show :
Parent order : 1000 shares of Apple
Child #1 : 10 shares of Apple
...
Child #10: 10 shares of Apple.




import junit.framework.TestCase;

public class KnightTradingTest extends TestCase {
	private static final int parentOrder = 0;
	private static final boolean childOrder = false;
	private Orders o;

	protected void setUp() throws Exception {
	    o = new Orders();
	}
	
	private void currentChildOrder(int i) {
		int currentChildOrder = 0;
		
	}
	
	protected void testParentOrder() throws Exception{
		
		int chlidOrder []= new int [10];
		Object[] childOrder = null;
		int currentChildOrder = 0;
		int parentOrder = 1000;
		childOrder[currentChildOrder++] = parentOrder /10;
		
	}
	
	protected void testChildOrder() throws Exception{	
		currentChildOrder (parentOrder /10); {
			  if(!(childOrder)) {
			    return;
			  }
			}
	}	
}
