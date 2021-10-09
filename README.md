# java
／／十以内加法口算
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


／／拓展——十以内加减法口算（规避负值）
import java.util.Scanner;
import java.util.Random;

public class KS2{
	public static void main(String[]args){
		int KS=1;
		for(KS=1;KS<20;KS++){
		Scanner sc=new Scanner(System.in);
		Random sr=new Random();
		
		
		int b=sr.nextInt(10);
		int c=sr.nextInt(10);
	if(b>c){
		System.out.println(b+"-"+c+"=");
	}else	
	System.out.println(c+"+"+b+"=");
	
	int d=c+b;
	int e=b-c;
	
	
	int a=sc.nextInt();
	if(a==d){
		System.out.println("正确");
	}else if(a==e){
		System.out.println("正确");
	}else if(b<=c&a!=d){
		System.out.println("错误，正确答案是:"+d);
	}else
	System.out.println("错误，正确答案是:"+e);
	}
	System.out.println("休息一下");
}
}
／／我是一名新手，有很多地方需要学习，还望多多指教
