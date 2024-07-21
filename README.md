import java.util.Scanner;


public class uslu {

    static int power(int a,int b){
    
        int result=1;
        
        for(int i=1;i<=b;i++){
        
            result*=a;
            
        }
        return result;
    }
    public static void main(String[] args) {
    
        Scanner input= new Scanner(System.in);
        
        System.out.println("Lütfen ilk sayıyı giriniz: ");
        
        int a=input.nextInt();
        
        System.out.println("Lütfen ikinci sayıyı giriniz: ");
        
        int b=input.nextInt();
        

       System.out.println("üs alma:"+power(a,b));


    }
}
