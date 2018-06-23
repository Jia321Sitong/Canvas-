package canvas;

/**
 *
 * @author sitongliu
 */
public class CanvasDrawing {
    private int rowCount;
    private int colCount;
    private char[][] pixels; // first [] put rowcount, second [] put colcount. although all lower ,but one putting[] becont referncetype


  public CanvasDrawing(){// entry point for the class creation ,called constructor
        // what do we want to here ?
        rowCount = 50;
        colCount = 100;
        pixels = new char[rowCount][colCount];//
  }
        //alternatively, you can let your user to specify rowCount, cOLcOUNT
        public CanvasDrawing(int rCount, int cCount) {// another entry point for the boject creation
               
            rowCount = rCount;
            colCount = cCount;
            pixels = new char [rowCount][colCount];
            

        }

        public CanvasDrawing(int rCount, int cCount, char color ){// another entry point for the boject creation
            rowCount = rCount;
            colCount = cCount;
            pixels = new char [rowCount][colCount];

            for(int r=0; r< rowCount;r++){
                for( int c =0; c < colCount; c++){
                    pixels[r][c] = color;
                }
            }

        }
        public void render(){// void no return type
            for(int r=0; r< rowCount;r++){
                for( int c =0; c < colCount; c++){
                    System.out.print(pixels[r][c]) ;
                }
                System.out.println();//println is jump to next line, show every pixels
        }

    }// this call mathord
    
    
}
