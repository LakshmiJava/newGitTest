# newGitTest
import java.util.Scanner;

public class FactorialOfNumberUsingDoWhile {

	public void enterInput() {
		Scanner sc=new Scanner(System.in);
		System.out.println("Enter n number ");
		int n=sc.nextInt();
		nFactorial( n);
	}
	public void nFactorial(int n) {
		int res=1;int sum=0;
		do {
			res= res*n;
			sum=res;
			n--;
			
		}while(n!=0);
		System.out.println(sum);

	}
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		FactorialOfNumberUsingDoWhile obj=new FactorialOfNumberUsingDoWhile();
		obj.enterInput();
	}

}
