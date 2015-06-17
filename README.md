# javasample
just a description
package fibonacci;

public class fibonacci {
	public static void main(String args[]){
		int s1=-1,s2=1,s3,i;
		for(i=0;i<10;i++){
			s3=s1+s2;
			s1=s2;
			s2=s3;
			System.out.println(s3);
		}
	}

}
