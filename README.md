class PrimeNo
{
	public static void main(String args[]){
		int a,i;
		int c=0;
		for(int i=2;i<a;i++){
			if(a%i==0)
			{
				System.out.println(a+" is not a Prime Number");
				c= 1;
				break;
			}
		}
		if(c==0)
			System.out.println(a+" is a Prime Number");


