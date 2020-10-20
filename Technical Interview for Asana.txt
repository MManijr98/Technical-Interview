int[] tripleSquareSum(int[] a) {
private static final int tripleSquareSum = 25;

public static void main(String[] args) {
    int a;
    int b;
    int c;
    
    for (a = 1; a < tripleSquareSum; a++)
    {
        for (b = a; b < tripleSquareSum; b++)
        {
            for (c =b; c < tripleSquareSum; c++)
            if((Math.pow(a,2) + Math.pow(b,2) == Math.pow(c,2))
            System.out.printf("%d %d %d\n" a, b, c);
            
        }
    }
}
}


long digitAnagrams(int[] a) {
 static final int TEN = 10;
 {
     while (n > 0)
     {
         int digitAnagrams = n % TEN;
         
         freq[digitAnagrams]++;
         
         n /= TEN;
     }
 }
 
 static boolean digitAnagrams(int a, int b)
 {
     int [] freqA = new int[TEN];
     int [] freqB = new int[TEN];
     
     updateFreq(a, freqA);
     updateFreq(b, freqB);
     
     for (int i = 0; i < TEN; i++)
      if(freqA[i] != freqB[i])
 }
        return false;
 }

int[][] rotateOverDiagonals(int[][] m, int k) {
static void rotateOverDiagonals(rotateOverDiagonals(m, k))
{
    int row = 0;
    int column = 0;
    int previous;
    int current;
     while (row < m && column < k)
     {
         if (row + 1 == m || column + 1 == k)
         break;
         
         previous = mat[row + 1] [column];
         for (int i = column; i < k; i++)
         {
             current = mat[row][i];
             previous = current;
         }
         row++;
         for (int i = row; i < m; i++)
