# TESTSUITE
Multiple Test Cases 

package DEMO;

import org.testng.Assert;
import org.testng.annotations.Test;

public class Test1 {
	
	@Test
	public void tc_1(){
	System.out.println("Test Case1");
	Assert.assertTrue(true);
	}
	
	@Test
	public void tc_2(){
	System.out.println("Test Case2");
	Assert.assertTrue(true);  
	}
	
	@Test
	public void tc_3(){
	System.out.println("Test Case3");
	Assert.assertTrue(true);
	}
	
	@Test
	public void tc_4(){
	System.out.println("Tes Case4");   
	Assert.assertTrue(true);  
	}
    }
    
    package DEMO;

import org.testng.Assert;
import org.testng.annotations.Test;

public class Test2 {

	@Test
	public void tc_5(){
	System.out.println("Test Case5");  
	Assert.assertTrue(true);  
	}
	
	@Test
	public void tc_6(){
	System.out.println("Test Case6");
	Assert.assertTrue(true);
	}
	
	@Test
	public void tc_7(){
	System.out.println("Test Case7");
	Assert.assertTrue(true);
	}
	
	@Test
	public void tc_8(){
	System.out.println("Test Case8");
	Assert.assertTrue(true);   
	}
	
	@Test
	public void tc_9(){
	System.out.println("Test Case9");
	Assert.assertTrue(true);
	}
	
	@Test
	public void tc_10(){
	System.out.println("Test Caes10");
	Assert.assertTrue(true);
	}
    }

package DEMO;

import org.junit.Assert;
import org.testng.annotations.Test;

public class Test3 {
	
	
  @Test
  public void tc_11() {
  System.out.println("Test Case11");
  Assert.assertTrue(true);
  }
  
  @Test
  public void tc_12() {
  System.out.println("Test Case12");
  Assert.assertTrue(true);
  }
  
  @Test
  public void tc_13() {
  System.out.println("Test Case13");
  Assert.assertTrue(true);   
  }
  
  <?xml version="1.0" encoding="UTF-8"?>
<suite name="Suite" parallel="false">
  <test name="Test">
    <classes>
      <class name="DEMO.Test1"/>
            <class name="DEMO.Test2"/>
                  <class name="DEMO.Test3"/>
    </classes>
  </test> <!-- Test -->
</suite> <!-- Suite -->

[RemoteTestNG] detected TestNG version 6.12.0
[TestNGContentHandler] [WARN] It is strongly recommended to add "<!DOCTYPE suite SYSTEM "http://testng.org/testng-1.0.dtd" >" at the top of your file, otherwise TestNG may fail or not work as expected.
Test Case1
Test Case2
Test Case3
Tes Case4
Test Caes10
Test Case5
Test Case6
Test Case7
Test Case8
Test Case9
Test Case11
Test Case12
Test Case13

===============================================
Suite
Total tests run: 13, Failures: 0, Skips: 0
===============================================
