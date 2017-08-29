
package MoveTests;

import java.util.logging.Level;
import java.util.logging.Logger;
import javax.swing.JFrame;

public class MoveTest {
    public static void main(String[] args) {
        Frame f = new Frame();
        f.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        f.setSize(600, 400);
        f.setVisible(true);
        f.setResizable(false);
        
        
        while(true){
            if(f.getUp())f.player_posy-=5;
            if(f.getDown())f.player_posy+=5;
            if(f.getLeft())f.player_posx-=5;
            if(f.getRight())f.player_posx+=5;
            
            
            f.repaintScreen();
            
            
            try {
                Thread.sleep(16);
            } catch (InterruptedException e) {
                e.printStackTrace();
            }
        }
        
    }
    
}
