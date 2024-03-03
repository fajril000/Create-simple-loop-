# Create-simple-loop-
Create simple loop Mohammad Fajril 
 file with 74 additions and 0 deletions.
 74 changes: 74 additions & 0 deletions74  
simple looping
@@ -0,0 +1,74 @@
a. 1 3 5 7 9 11

public class Loop {
    public static void main(String[] args) throws 
    Exception{
        int maxLoop = 6;
        int a = 1;
        for (int i = 0; i < maxLoop; i++ ) {
            System.out.print(a+ " ");
            a=a + 2;
        }
    }
}


b. 25 20 15 10 5

public class Loop1 {
    public static void main(String[] args) throws 
    Exception{
        int maxLoop = 5;
        int a = 25;
        for (int i = 0; i < maxLoop; i++ ) {
            System.out.print(a+ " ");
            a=a-5;
        }
    }
}


c. -4 -1 2 5 8

public class Loop2 {
    public static void main(String[] args) throws 
    Exception{
        int maxLoop = 5;
        int a = -4;
        for (int i = 0; i < maxLoop; i++ ) {
            System.out.print(a+ " ");
            a=a+3;
        }
    }
}

d. 0 1 1 2 3 5

public class Loop3 {
    public static void main(String[] args) throws Exception {
        int maxLoop = 6; 
        int a = 0;
        int b = 1;
        int c;
        System.out.print(a + " "); 
        System.out.print(b + " "); 
        for (int i = 2; i < maxLoop; i++) { 
            c = a + b;
            System.out.print(c + " ");
            a = b;
            b = c;
        }
    }
}


e. 0 1 1 2 4 7 11

public class Loop4  {
    public static void main(String[] args) {
        int[] sequence = new int[]{0, 1, 1, 2, 4, 7, 11};
        for (int i = 0; i < sequence.length; i++) {
            System.out.print(sequence[i] + " ");
        }
    }
}
