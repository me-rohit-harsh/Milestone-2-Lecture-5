# ***🌟Give Star If you find this helpful :)🌟***
# 1. ***Square Pattern***
### Code:Square Pattern
import java.util.Scanner;
public class Solution {


	public static void main(String[] args) {
		
		 Scanner scan = new Scanner(System.in);
        int n = scan.nextInt();
        int i=1;
        while(i<=n){
            int j=1;
            while(j<=n){
                System.out.print(n);
                j++;
            }
            i++;
            System.out.println();
        }	
	}

}

# 2. ***Triangular Star Pattern***
### Code:Triangular Star Pattern
import java.util.Scanner;
public class Solution {

	public static void main(String[] args) {
		
		Scanner scan = new Scanner(System.in);
        int n = scan.nextInt();
        int i=1;
        while(i<=n){
            int j=1;
            while(j<=i){
                System.out.print("*");
                j++;
            }
            i++;
            System.out.println();
        }	
	}

}

# 3. ***Triangle Number Pattern***
### Code:Triangle Number Pattern
import java.util.Scanner;
public class Solution {

	public static void main(String[] args) {
		Scanner scan = new Scanner(System.in);
        int n = scan.nextInt();
        int i=1;
        while(i<=n){
            int j=1;
            while(j<=i){
                System.out.print(i);
                j++;
            }
            i++;
            System.out.println();
        }	
	}

}

# 4. ***Reverse Number Pattern***
### Code:Reverse Number Pattern
import java.util.Scanner;
public class Solution {

	public static void main(String[] args) {
	        Scanner scan = new Scanner(System.in);
        int n = scan.nextInt();
        int i=1;
        while(i<=n){
            int j=0;
            while(j<i){
                System.out.print(i-j);
                j++;
            }
            System.out.println();
            i++;
        }	
	}

}

# 5. ***Alpha Pattern***
### Code:Alpha Pattern
import java.util.Scanner;
public class Solution {

	public static void main(String[] args) {
		Scanner scan=new Scanner(System.in);
        int val=scan.nextInt();
        int i =1;
        while(i<=val){
            int j=1;
            while(j<=i){
                int a =64+i;
                char c=(char)a;
                System.out.print(c);
                j++;
            }
            System.out.println();
            i++;
        }	
	}

}

# 6. ***Character Pattern***
### Code:Character Pattern
import java.util.Scanner;
public class Solution {

	public static void main(String[] args) {	
		Scanner scan=new Scanner(System.in);
        int val=scan.nextInt();
        int i =1;
        while(i<=val){
            int j=1;
            while(j<=i){
                int a =63+j+i;
                System.out.print((char)a);
                j++;
            }
            System.out.println();
            i++;
        }		
	}

}

# 7. ***Interesting Alphabets***
### Code:Interesting Alphabets
import java.util.Scanner;
public class Solution {

	public static void main(String[] args) {
		 Scanner scan=new Scanner(System.in);
            int val=scan.nextInt();
            int i =1;
            while(i<=val){
                int j=1;
                while(j<=i){
                    int a =64-i+j+val;
                    System.out.print((char)a);
                    j++;
                }
                System.out.println();
                i++;
            }
	}

}

# ***🌟Give Star If you find this helpful :)🌟***
