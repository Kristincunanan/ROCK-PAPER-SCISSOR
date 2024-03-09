if(jTextField1.getText().equalsIgnoreCase("Rock")&&jTextField2.getText().equalsIgnoreCase("Rock"))
        {
            jLabel4.setText("Draw");
        }
        else if(jTextField1.getText().equalsIgnoreCase("Rock")&&jTextField2.getText().equalsIgnoreCase("paper"))
        {
        jLabel4.setText("Player 2 Wins");
        }
        else if(jTextField1.getText().equalsIgnoreCase("Rock")&&jTextField2.getText().equalsIgnoreCase("Scissor"))
        {
        jLabel4.setText("Player 1 Wins");
        } 
        else if(jTextField1.getText().equalsIgnoreCase("Paper")&&jTextField2.getText().equalsIgnoreCase("paper"))
        {
        jLabel4.setText("Draw");
        }
        else if(jTextField1.getText().equalsIgnoreCase("Paper")&&jTextField2.getText().equalsIgnoreCase("Rock"))
        {
        jLabel4.setText("Player 1 Wins");
        }
        else if(jTextField1.getText().equalsIgnoreCase("Paper")&&jTextField2.getText().equalsIgnoreCase("Scissor"))
        {
        jLabel4.setText("Player 2 Wins");
        }
        else if(jTextField1.getText().equalsIgnoreCase("Scissor")&&jTextField2.getText().equalsIgnoreCase("Scissor"))
        {
        jLabel4.setText("Draw");
        }
        else if(jTextField1.getText().equalsIgnoreCase("Scissor")&&jTextField2.getText().equalsIgnoreCase("paper"))
        {
        jLabel4.setText("Player 1 Wins");
        }
        else if(jTextField1.getText().equalsIgnoreCase("Scissor")&&jTextField2.getText().equalsIgnoreCase("Rock"))
        {
        jLabel4.setText("Player 2 Wins");
        }
        
        else 
        {
            Component This = null;
            JOptionPane.showMessageDialog(This, "Invalid Input");
        }
         
        
      
    }                                        

   
      jTextField1.setText("Rock");
    }                                        

   
        jTextField2.setText("Rock");
        
        
        
        
        
        
                 
    }                                        

    
       jTextField1.setText("Scissor");
    }                                        

   
       jTextField2.setText("Paper");
    }                                        

   
jTextField1.setText("Paper");
    }                                           

  
        jTextField1.setText("Paper");
    }                                        

   
        jTextField2.setText("Scissor");
    }                                        

