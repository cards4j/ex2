# ex2: product of integer primitive and reference types compiles and runs 
    01 public class Ex1  {
    02    public static void main(String[] args) {
    03        Integer a = Integer.valueOf(7);
    04        int c = a * 5;
    05        System.out.println(c);
    06    }
    07 }
---
    35
---
Integer reference type variable `a` multiplied by primitive integer literal `5` 
is stored in primitive integer variable `c` and sent to the console as  the product, 35.