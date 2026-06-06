# Hackerranl-solutionss

<img width="381" height="334" alt="image" src="https://github.com/user-attachments/assets/6e084533-1251-46d4-8af0-eed5b8f148f1" />
<img width="370" height="265" alt="image" src="https://github.com/user-attachments/assets/3fe409de-c73e-4f78-9e99-780ff62a232a" />

solution

import java.util.*;

public class Solution {

    public static void main(String args[]){
    
        Scanner sc = new Scanner(System.in);
        
        int a = sc.nextInt();
        int b = sc.nextInt();
        
        int c = a+b;
        System.out.print(c); 
    }
}


<img width="382" height="351" alt="image" src="https://github.com/user-attachments/assets/2a628e5b-de9b-49fa-8761-37f07840ceca" />
<img width="370" height="286" alt="image" src="https://github.com/user-attachments/assets/ca4ca6bd-9ca6-4712-b266-5bc4412df919" />

import java.util.*;

public class Solution{

    public static void main(String args[]){
    
        Scanner sc = new Scanner(System.in);
        
        int a = sc.nextInt();// sizze of an array
        
        int arr[] = new int[a];// declaration of an array
        
        //until now array is emty
        
        // now we want to fill array
        
        for(int i=0;i<a;i++){
            arr[i]=sc.nextInt();
        }
        
        // now inside have the stuff
        
        //pravin program logic
        int sum=0;
        for(int i=0;i<a;i++){
            sum = sum + arr[i];// traverse to add each elements
            
        }
        
        System.out.print(sum);
        
    }
}










