# Canvas-
Use Java to drawing 
package canvas;

/**
 *
 * @author Jia liu
 */
public class Canvas {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args){
        // TODO code application logic here
        try{// No.2 way 
        System. out. println("This is my Canvas");
        //type followed by varialbe name followed by = followed by new...
        CanvasDrawing myCanvas = new CanvasDrawing(10,20,'&');//myCanvas is a object,
        myCanvas.render();//this myCanvas object call render founction 
        System. out. println("This is end my Canvas");
    
        }
      finally{
           System.out.println("Goodbye");
     }
        
    
    
    }
