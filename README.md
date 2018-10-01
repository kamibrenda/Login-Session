# Login-Session
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package login;

import javax.swing.JButton;
import javax.swing.JFrame;
import javax.swing.JLabel;
import javax.swing.JPanel;
import javax.swing.JTextField;

/**
 *
 * @author Administrator
 */
public class Login {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        //to create a front deskapplication
     JFrame myframe=new JFrame("Login");
     JPanel mypanel=new JPanel();
     JLabel namelabel=new JLabel("Username");
     JLabel namelabel2=new JLabel("Password");
     JTextField name=new JTextField();
     name.setColumns(20);
     JButton Login=new JButton("Login");
     mypanel.add(name);
     mypanel.add(namelabel);
     mypanel.add(namelabel2);
     mypanel.add(Login);
     myframe.add(mypanel);
     myframe.setSize(1000, 1000);
     myframe.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
     myframe.setVisible(true);
    }
    
    
}
