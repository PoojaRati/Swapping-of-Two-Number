# Swapping-of-Two-Number
Swapping Numbers
import java.util.*;
public class Swaping {
  public static void main(String[] args){
 int x=10;
 int y=40;
 swapfunction(x,y);
  }
public static void swapfunction(int a,int b){
    System.out.println("Before swaping, a="+a+" b="+b);
    int c=a;
    a=b;
    b=c;
    System.out.println("After swaping,a="+a+" b="+b);
    
}  
}
