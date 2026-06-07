# Repo-61
Largest Element In Array
import java.util.*;
public class Like {
    public static int largest(int[] arr){
        int large=Integer.MIN_VALUE;
        for(int a:arr){
            large=Math.max(large,a);
        }
        return large;
    }
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int arr[]={10,20,30,40,50,60,70};
        int ans=largest(arr);
        System.out.println(ans);
        sc.close();
    }
}
