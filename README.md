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

    private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        // TODO add your handling code here:
      jTextField1.setText("Rock");
    }                                        

    private void jButton2ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        // TODO add your handling code here:
        jTextField2.setText("Rock");
        
        
        
        
        
        
                 
    }                                        

    private void jButton4ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        // TODO add your handling code here:
       jTextField1.setText("Scissor");
    }                                        

    private void jButton5ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        // TODO add your handling code here:
       jTextField2.setText("Paper");
    }                                        

    private void jTextField2ActionPerformed(java.awt.event.ActionEvent evt) {                                            
        // TODO add your handling code here:
jTextField1.setText("Paper");
    }                                           

    private void jButton3ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        // TODO add your handling code here:
        jTextField1.setText("Paper");
    }                                        

    private void jButton6ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        // TODO add your handling code here:
        jTextField2.setText("Scissor");
    }                                        
