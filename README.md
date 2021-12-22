# Selenium
package testng;

import org.testng.Reporter;
import org.testng.annotations.BeforeMethod;
import org.testng.annotations.Test;

public class TestNg2 
{
 @Test(
		 enabled=false)
 public void TC01()
 {
   Reporter.log("Running TC01",true);	 
 }
 @Test //(invocationCount=3)
 public void bTC02()
 {
   Reporter.log("Running TC02",true);	 
 }
 @BeforeMethod
  public void openBrowser()
  {
	  Reporter.log("Launch Browser...",true);
  }
 
 
 @Test
 public void aTC03()
 {
   Reporter.log("Running TC03",true);	 
 }
}
 

