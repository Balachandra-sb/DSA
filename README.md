####)Switch case:-

      cases have to be the same type as expressions,must be a consatant or litera
      ->duplicate case values are not allowed
      ->break is use to terminate the sequence
      ->default will execute when none of the above does
      ->if default is not at the end,put break after it.


####)syntax:-
          switch(expression){
               case :
                  Statement;
                  break;
                default :
                   Statement;
          }


####)example:-

import java.util.*;
class Main {
    public static void Main(String[] args) {
        Scanner sc = new Scanner (System.in);
        int num = sc.nextInt();
        switch(num){
            case 1 -> System.out.println("Monday");
            case 2 -> System.out.println("Tuesday");
            case 3 -> System.out.println("Wednesday");
            case 4 -> System.out.println("thursday");
            case 5 -> System.out.println("Friday");
            case 6 -> System.out.println("Saturday");
            case 7 -> System.out.println("sunday");
            default -> System.out.println("Nothing");

        }
        
    }
}

#####)Terimnary operator (or) enhence if else:-

                                     int n = 5;
                                     if(n == 5){
                                         System.out.println("Yes");
                                    }else{
                                         System.out.println("No');
                                         }
                                     (condition) ? statement1 :statement2;
                                     String res = (n == 5) ? ("Yes") :("No");
                                     System.out.println(res);



Enhance for loop (or) for each loop::

                     In collections we dont have index values in those situations  we have to use for each loop

    Exam):- 
               int[] arr ={1,2,3,4,5};

               for(int var : arr){
                   System.out.println(var)
                }


  Q):--Write any code and it converts int enhance for loop (OR) if else (OR) switch case ?
  
                             
           
