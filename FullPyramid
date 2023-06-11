public class FullPyramid {
    private static int rows=5;
    public static void printspace(int space) {
        //Termination case + Business logic
        if(space==0){
            return;
        }else{
            System.out.print("  ");
        }
        //Recursive call
        printspace(space-1);
    }
    public static void printstar(int star) {
        //Termination case
        if(star==0){
            return;
        }
        //Business logic
        System.out.print("*");
        System.out.print(" ");
        //Recursive call
        printstar(star-1);
    }
    public static void printline(int row,int space) {
        //Termination case
        if(row==0){
            return;
        }
        //Business logic
        printspace(row-1);
        printstar(space);
        System.out.println();
        //Recursive call
        printline(row-1, space+2);

        //Business logic
        if(space==9){
            return;
        }
        printspace(row-1);
        printstar(space);

        System.out.println();
    }
    
    public static void main(String[] args) {
        printline(rows,1);
        System.out.println();
        
        
    }
}
