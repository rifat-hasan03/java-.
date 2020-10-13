# java-.
package com.yaj;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

//        1.print sum of all the numbers from 1 to 10
//        2.print sum of all numbers from m to n
//        3.print sum of all the even numbers from m to n
//        4.print sum of all the odd numbers from m to n

//       answer 1:-
//        int sum= 0;
//        for(int i=1; i<=10; i++){
//            sum = sum+i;
//        }
//        System.out.println("the number is:"+sum);


//        answer 2:-

        Scanner input = new Scanner(System.in);

        int sum= 0;
        int m,n;
        System.out.println("Enter initial number:");
        m = input.nextInt();

        System.out.println("Enter final number:");
        n = input.nextInt();

        for(int i=m; i<=n; i++){
            sum = sum+i;
        }
        System.out.println("The sum is:"+sum);






//        continue and break useing..........?

//        for(int i=1; i<=100; i=i+3){
//            if(i==10){
//                continue;
//            }
//            if(i>13){
//                break;
//            }
//            System.out.println(i);
//        }







//        useing a  continue statement........?

//        for(int i=1; i<=100; i++){
//            if(i==10){
//                continue;
//            }
//            System.out.println(i);
//        }

//           for(int i=1; i<=10; i=i+3){
//               if(i==10){
//                   continue;
//               }
//               System.out.println(i);
//           }





        //        Break statement..............?

//        for(int i=1; i<=100; i++){
//
//            if(i==10){
//                break;
//            }
//            System.out.println(i);
//        }








//        control statement ------loping......?




//        do looping.............?
//      int i=1;
//
//       do{
//           System.out.println("ban");
//           i++;
//       }while (i<=10);



//       while..........?
//        int i=2;
//        while (i<=10){
//            System.out.println(i);
//            i=i+2;
//        }






//        for looping..................?

//        for(int i=1;i<=13;i++){
//           System.out.println(i + "  :Bngladesh");
//        }
//
//        for(int i=1;i<=1003;i++){
//            System.out.println(i);
//        }
//
//
//        for(int i=2; i<=1003; i=i+2){
//            System.out.println(i);
//        }




//     math calass....................?
//        ========================================
//        int x= 30, y= -40;
//        int max= Math.max(x,y);
//
//        System.out.println("Max:"+max);
//
//        int min= Math.min(x,y);
//
//        System.out.println("Min:"+min);
//
//
//        int absolute= Math.abs(y);
//
//        System.out.println("absolute of y:"+absolute);
//
//        int p= 3, k= 4;
//        double power = Math.pow(p,k);
//        System.out.println("x to the power y ="+power);
//
//        int round = Math.round(8.8f);
//        System.out.println("Round of 8.8="+round);
//
//        int rounddown= Math.round(8.4f);
//        System.out.println("Round of 8.4="+rounddown);
//
//        double pi =Math.PI;
//        System.out.println("pi = "+pi);

 //        Bitwise operator...........?
//        =========================================

//        int a=32, b=12, c;
//         c = a>>3;
//
//         System.out.println("a>>3 = "+c);
//
//       c = a<<3;
//       System.out.println("a<<3="+c);




//        Note========&= Bitwise and, |=Bitwise or , >>=Bitwise shift right, <<=Bitwise shift left,~=Bitwise Not.....
//        ^=Bitwise exor================================
//         int a=32, b=12, c;
//         c = a&b;
//
//        System.out.println("a & b = "+c);
//
//        c = a|b;
//        System.out.println("a | b="+c);
//
//        c = a^b;
//        System.out.println("a^b = "+c);





//        useing a conditional operator...........?
//        ==========================================

//        Scanner input = new Scanner(System.in);
//        int num1, num2, large;
//        System.out.print("Enter 2 number:");
//        num1 = input.nextInt();
//        num2 = input.nextInt();
//
//        large = (num1>num2) ? num1 : num2;
//        System.out.print("large number = "+ large);







//        control statement : useing swith, case, break, default
//        =============================================
//        Scanner input = new Scanner(System.in);
//        int digit;
//        System.out.println("Enter any digit:");
//        digit = input.nextInt();
//
//        switch(digit){
//
//            case 0:
//                System.out.println("zero");
//                break;
//            case 1:
//                System.out.println("one");
//                break;
//            case 2:
//                System.out.println("two");
//                break;
//            case 3:
//                System.out.println("three");
//                break;
//            case 4:
//                System.out.println("four");
//                break;
//            case 5:
//                System.out.println("five");
//                break;
//            case 6:
//                System.out.println("six");
//                break;
//            case 7:
//                System.out.println("seven");
//                break;
//            case 8:
//                System.out.println("eight");
//                break;
//            case 9:
//                System.out.println("nine");
//                break;
//            default:
//                System.out.println("not a digit");
//
//
//
//
//        }


//     logical && useing........???
//    ================================================

//        Scanner input = new Scanner(System.in);
//        int ch;
//        System.out.print("Enter any letter:");
//        ch = input.next().charAt(0);
//
//
//      if(ch>='a' && ch<='z'){
//          System.out.println("small Letter");
//      }else if(ch>='A' && ch<='Z'){
//          System.out.println("Capital Letter");
//      }else{
//        System.out.println("not a letterr");
//    }


//        useing logical operator..vowel-consonant useing if - else................?
//        =======================================
//        Scanner input = new Scanner(System.in);
//        int ch;
//        System.out.print("Enter any letter:");
//        ch = input.next().charAt(0);
//
//        if(ch=='a' || ch=='e' || ch=='i' || ch=='o' || ch== 'u'){
//            System.out.print("vowel");
//        }
//        else{
//            System.out.print("consonant");
//        }



//         vowel-consonant useing if - else............?
//        ======================================

//      Scanner input = new Scanner(System.in);
//      char ch;
//      System.out.print("Enter any letter:");
//     ch = input.next().charAt(0);
//
//     if(ch=='a'){
//         System.out.println("vowel");
//     }
//     else if(ch=='e'){
//            System.out.println("vowel");
//        }
//     else if(ch=='i'){
//            System.out.println("vowel");
//        }
//     else if(ch=='o'){
//            System.out.println("vowel");
//        }
//      else if(ch=='u'){
//            System.out.println("vowel");
//        }
//      else {
//         System.out.println("consonant");
//     }


//      Even or odd .........................?
//        ===================================
//        Scanner input = new Scanner(System.in);
//        int num;
//        System.out.print("Enter any positive integer:");
//        num = input.nextInt();
//
//        if(num%2==0){
//            System.out.print("Even");
//        }else{
//            System.out.print("odd");
//        }


//        useing a Relational operator.................?
//======================================================
//        if   ....... else if
//        =======================================
//        Scanner input = new Scanner (System.in);
//        int num;
//        System.out.print("Enter any integer:");
//        num = input.nextInt();
//        if(num>0){
//            System.out.print("positive");
//        }
//        else if(num<0){
//            System.out.print("Negative");
//        }
//        else {
//            System.out.print("Equal to zero");
//        }

//        useing unary operator......?
//        int x = 10, result;
//
//        result = +x;     //-10
//        System.out.println("result="+result);
//
//        result = -x;    //+10
//        System.out.println("result="+result);
//
//        result = ++x;  //prefix Increment
//        System.out.println("result="+result);
//
//        result = x++;  //postfix Increment
//        System.out.println("result="+result);
//
//        result = --x;  //prefix Decrement
//        System.out.println("result="+result);
//
//        result = x--;  //postfix Decrement
//        System.out.println("result="+result);

//        How to change from  Fahrenheit to celsius........???
//        Scanner input = new Scanner(System.in);
//        double celsius, fahrenheit;
//
//        System.out.print("celsius:");
//        fahrenheit = input.nextDouble();
//
//        celsius = 5/9 * fahrenheit - 32;
//        System.out.println("celsius:" + celsius);



//     How to change from celsius to Fahrenheit........???
//        Scanner input = new Scanner(System.in);
//        double celsius, fahrenheit;
//
//        System.out.print("celsius:");
//        celsius = input.nextDouble();
//
//        fahrenheit = 1.8 * celsius + 32;
//        System.out.println("fharenheit:" + fahrenheit);



//        how to find the radius of a circle..........................
//       Scanner input = new Scanner(System.in);
//       double radius, area;
//        System.out.print("Enter radias :");
//        radius = input.nextDouble();
//
//        area = 3.1416 * radius *radius;
//        System.out.print("Area of circle:"+ area);




//        program to find a circle triangle..........
//        Scanner input = new Scanner(System.in);
//        double base, height, area;
//        System.out.println("Enter base: ");
//        base = input.nextDouble();
//        System.out.println("Enter height: ");
//        height = input.nextDouble();
//        area = 0.5*base*height;
//        System.out.println("Area of triangle:"+area);
    }
}
