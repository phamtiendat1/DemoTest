package demo;

import org.junit.Test;

import static org.junit.Assert.*;

public class CalculatorTest {
    @Test
    public void testadd(){
        Calculator calculator= new Calculator();
        assertEquals(4,calculator.add(3,1));
    }
    @Test
    public void testadd2(){
        Calculator calculator= new Calculator();
        assertEquals(Integer.MAX_VALUE+1,calculator.add(Integer.MAX_VALUE,1));
    }

    @Test
    public void testadd3(){
        Calculator calculator= new Calculator();
        assertEquals(Integer.MIN_VALUE-1,calculator.add(Integer.MIN_VALUE,-1));
    }

    @Test
    public void testsub(){
        Calculator calculator= new Calculator();
        assertEquals(5,calculator.sub(6,1));
    }

    @Test
    public void testsub2(){
        Calculator calculator= new Calculator();
        assertEquals(Integer.MAX_VALUE+1,calculator.sub(Integer.MAX_VALUE,-1));
    }

    @Test
    public void testsub3(){
        Calculator calculator= new Calculator();
        assertEquals(Integer.MIN_VALUE-1,calculator.sub(Integer.MIN_VALUE,1));
    }

    @Test
    public void testmul(){
        Calculator calculator= new Calculator();
        assertEquals(4,calculator.mul(2,2));
    }

    @Test
    public void testmul2(){
        Calculator calculator= new Calculator();
        assertTrue(calculator.mul(-2,2)==4);
    }

    @Test
    public void testmul3(){
        Calculator calculator= new Calculator();
        assertEquals(Integer.MAX_VALUE*2,calculator.mul(Integer.MAX_VALUE,2));
    }

    @Test
    public void testmul4(){
        Calculator calculator= new Calculator();
        assertEquals(Integer.MIN_VALUE*(1/2),calculator.mul(Integer.MIN_VALUE,(1/2)));
    }

    @Test
    public void testdiv(){
        Calculator calculator= new Calculator();
        assertEquals(4,calculator.div(8,2));
    }
    @Test
    public void testdiv2(){
        Calculator calculator= new Calculator();
        assertTrue(calculator.div(8,0)==0);
    }

    @Test
    public void testdiv3(){
        Calculator calculator= new Calculator();
        assertEquals(Integer.MAX_VALUE/(1/2),calculator.div(Integer.MAX_VALUE,(1/2)));
    }

    @Test
    public void testdiv4(){
        Calculator calculator= new Calculator();
        assertEquals(Integer.MIN_VALUE/2,calculator.div(Integer.MIN_VALUE,2));
    }

}