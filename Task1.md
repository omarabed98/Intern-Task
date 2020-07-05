# Intern-Task
public class one{

     public static void main(String []args){
         
         
 int re;
 int sum=0;
 int  temp;    
 int n=141; 
  
  temp=n;    
  
  if(n>0 && n<150){
  while(n>0 ){    
   re=n%10; 
   sum=(sum*10)+re;    
   n=n/10;    
  }    
  
  
   if(temp==sum)    
   System.out.println("Palindrome number ");    
  else    
   System.out.println("Not palindrome");  
  }else{
      
    System.out.println("Your Number must between 0 -150 ");  

      
  }
   
  
         
     }
}
