# Java-Calculator


//This program works like a calculator
public class Calculator{
  public Calculator(){

  }
  public int add(int number1, int number2){
    int sum = number1 + number2;
    return sum;
  }
  public int subtract(int number1, int number2){
    int sub = number1 - number2;
    return sub;
  }
  public int multiply(int number1, int number2){
    
    int multi = number1 * number2;
    return multi;
  }
  public int divide(int number1, int number2){
    int div = number1 / number2;
    return div;
  }
  public int modulo(int number1, int number2){
    int modu = number1 % number2;
    return modu;
  }
  public static void main(String[] args){
    Calculator myCalculator = new Calculator();
    System.out.println(myCalculator.add(5,7));
    System.out.println(myCalculator.subtract(45,11));
    System.out.println(myCalculator.multiply(2,2));
    System.out.println(myCalculator.divide(2,2));
    System.out.println(myCalculator.modulo(10,3)); 
  }

}
