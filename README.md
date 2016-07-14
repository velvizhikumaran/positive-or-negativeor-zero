# positive-or-negativeor-zero
public class Checking {
	public static void main(String[] args) {
		if(args.length!=0){
int a=Integer.parseInt(args[0]);
	if(a>0){
	System.out.println("the number "+a+" is a positive number");
	}
	else if(a<0){
		System.out.println("the number "+a+" is a negative number");
	}
		else{
			System.out.println("the number "+a+" is neither positive nor negative");
		}
	}
	else{
		System.out.println("An integer number as argument is expected");
	}
}
}
