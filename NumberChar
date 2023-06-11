public class NumberChar {
    public static int printcolumn(int index, int column) {
        //Termination case
        if(column==0){
            return index;
        }
        //Recursive call
        int result = printcolumn(index, column-1);
        //Business logic
        result++;
        System.out.print(" "+result);
        return result;
    }
    
    public static void printrows(int rows,int column,int index) {
        //Termination case
        if(rows==0){
            return;
        }
        //Business logic
        index = printcolumn(index, column);
        System.out.println();
        //Recursive call
        printrows(rows-1,column+1,index);
    }
    public static void main(String[] args) {
        printrows(4,1,0);
    }
}
