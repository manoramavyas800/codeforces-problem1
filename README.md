# codeforces-problem1
import java.util.Scanner;
public class CandiesAndTwoSisters {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);;
           int n = sc.nextInt();
           while(n-->0){
               String s1 = sc.next();
               StringBuilder s2 = new StringBuilder();
               for(int i=s1.length()-1;i>=0;i--){
                   char c = s1.charAt(i);
                   if(c=='p'){
                       s2.append('q');
                       
                   }else if(c=='q'){
                       s2.append('p');
                   }else{
                       s2.append(c);
                   }
               }
               System.out.println(s2.toString());


        }
        sc.close();

    }

                 

    }
}
