package JUnitTestingPackage;

import static org.junit.Assert.*;

import org.junit.Test;

public class testAddSting {

	@Test
	public void test() {
		JUnitFunction JUnitString = new JUnitFunction();
		String result = JUnitString.addString("Bob", "Marley");
		assertEquals("BobMarley",result);
	}

}
