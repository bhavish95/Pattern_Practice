public class DiagonalLine {
    private static void printspace(int space) {
        //Termination case
        if(space==0){
            return;
        }

        //Business logic
        System.out.print("  ");
        //Recursive call
        printspace(space-1);
    }
    //Using Stack Builder
    public static void printline(int rows) {
        //Termination case
        if(rows==0){
            return;
        }
        //Business logic
        printspace(rows-1);
        System.out.print("*");
        System.out.println();
        
        //Recursive call
        printline(rows-1);
        
        //Business logic
        printspace(rows-1);
        System.out.print("*");
        System.out.println();
    }
    //Using Stack Fall
    public static int printpattern(int rows,int lines) {
        //Termination case
        if(rows==0){
            return lines-1;
        }
        //Recursive call
        int space = printpattern(rows-1,lines);
        //Business logic
        printspace(space);
        System.out.println("*");
        return space-1;
    }
    public static void main(String[] args) {
        printline(5);
        printpattern(5,5);
    }
}
