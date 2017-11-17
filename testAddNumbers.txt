package JUnitTestingPackage;

import static org.junit.Assert.*;

import org.junit.Test;

public class testAddNumbers {

	@Test
	public void test() {
		JUnitFunction JUnit = new JUnitFunction();
		int result = JUnit.addNumbers(100, 200);
		assertEquals(300,result);
		
		
	}

}
