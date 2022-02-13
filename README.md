# COLA-DINAMICA
 //IMPRIMIR 
 Nodo temporary=Cola;

        while(temporary.next!=null)

        {
            temporary=temporary.next;
          
            
        }
        TXTimprimir.setText(TXTimprimir.getText()+temporary.data.toString()+" ");
        
        //INSERTAR
         
         Nodo newNodo=new Nodo(TXTinsert.getText());
       
        if(tail.data=="")
        {
            tail=newNodo;
        }
        else{
            newNodo.next=tail;
            tail=newNodo;
        } 
        
        TXTinsert.setText("");
        
