# Java-using-Array-Method-Fill
import java.util.*;
class Main {
    public static void main(String[] args) {
        System.out.println(System.in);
        int a[]={72,56,9,76,1098};
        Arrays.fill(a, 100);
        for(int temp : a){
            System.out.printf("%d ",temp);
        }
    }
}
