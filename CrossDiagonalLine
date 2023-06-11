public class CrossDiagonalLine {
    private static int lines=10;

    public static void printspace(int space) {
        //Termination case
        if(space<=0){
            return;
        }
        //Business logic
        System.out.print("  ");
        //Recursive call
        printspace(space-1);
    }

    public static void methodCall(int count, int rows) {
        printspace(count);
        System.out.print(" *");
        printspace(rows-2);
        if(rows<=1){
            System.out.print("");
        }else{
            System.out.print(" *");
        }        
        System.out.println();
    }
    
    public static void printline(int rows,int count) {
        //Termination case
        if(rows<=0){
            return;
        }
        //Business logic
        methodCall(count, rows);        
        //Recursive call
        printline(rows-2, count+1);

        if(lines%2==0){
            //Business logic
            methodCall(count, rows);
        }
        else{
            if(rows==1){
                //Business logic
                System.out.print("");
            }
            else{
                //Business logic
                methodCall(count, rows);
            }
        }
    }
    public static void main(String[] args) {
        printline(lines, 0);
        
    }
}
