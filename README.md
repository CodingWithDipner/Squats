# Squats

#Problem
Somu went to the gym today. He decided to do X sets of squats. Each set consists of 15 squats. Determine the total number of squats that he did today.

#Input Format

-> The first line contains a single integer T — the number of test cases. Then the test cases follow.

-> The first and only line of each test case contains an integer X — the total number of sets of squats that Somu did.

#Output Format

For each test case, output the total number of squats done by Somu.

# Constraints

1 ≤ T ≤ 1000

1 ≤ X ≤ 10^5

# Explanation:

Test Case 1: 

Since, he does only 1 set of squats, the total number of squats done by him is 15.

Test Case 2: 

Since, he does 4 sets of squats, the total number of squats is 15+15+15+15=60.

#CODE

    import java.util.Scanner;

    public class Squats {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
		    int T=sc.nextInt();
		    for(int i=1;i<=T;i++){
		      int X=sc.nextInt();
		    
		      int Y=15;
		      int Z=X*Y;
		      System.out.println(Z);
		    }
      }
    }
