# LARGEST-ELEMENT-OF-AN-ARRAY
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        int a[];
        a=new int[100];
        int l=0;
        Scanner sc= new Scanner(System.in);
        int n=sc.nextInt();// Array length
        for(int i=0;i<n;i++){
            int k=sc.nextInt();
            a[0]=k;
        }
        for (int i=0;i<n;i++){
            if(l<a[i]){
                l=a[i];
            }
        }
            
        System.out.print(l+" is the arrays largest element ");
    }
}
