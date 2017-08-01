# COLA-DINAMICA
 //IMPRIMIR 
 Nodo temporal=Cola;

        while(temporal.siguiente!=null)

        {
            temporal=temporal.siguiente;
          
            
        }
        TXTimprimir.setText(TXTimprimir.getText()+temporal.dato.toString()+" ");
        
        //INSERTAR
         
         Nodo nuevoNodo=new Nodo(TXTinsertar.getText());
       
        if(Cola.dato=="")
        {
            Cola=nuevoNodo;
        }
        else{
            nuevoNodo.siguiente=Cola;
            Cola=nuevoNodo;
        } 
        
        TXTinsertar.setText("");
        
