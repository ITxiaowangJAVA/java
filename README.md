# java
一些自己自学过程中撰写的java源码（超简单/喜欢请带走/欢迎指导）
import java.util.Scanner;
import java.util.Random;

public class KS{
 public static void main(String[]args){
  int KS=1;
  for(KS=1;KS<20;KS++){
  Scanner sc=new Scanner(System.in);
  Random sr=new Random();
  
  
  int b=sr.nextInt(10);
  int c=sr.nextInt(10);
  
 System.out.println(c+"+"+b+"=");
 int d=c+b;
 
 int a=sc.nextInt();
 if(a==d){
  System.out.println("正确");
 }else
 System.out.println("错误"+d);
 
 }
 System.out.println("休息一下");
}
}
