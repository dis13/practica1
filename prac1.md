# practica1

  Numero=Numero%2;

    if(Numero==0){                                   
 	
    System.out.println("\nEl Numero ": "+" Es Par");
 	
    }else{   	
    System.out.println("\nEl Numero ": "+"Es Impar");
  
    }//else



 
    int a = 1;                                       
    for(int i=1; i<=Numero; i++){
    	
    if (Numero % i==0){
    	
    a++;	
    	 	
    }//if		
    }//for
    
    if(a!=2){
    	
    System.out.println("\nEl Numero:" No Es Primo");	
    	
    }else{
    
    areatexto.append("\nEl Numero:" Es Primo");			
    }


    int Numero4=0;                               
   
    if(Sumatoria>0){
    		
    for(int i=1; i<=Sumatoria; i++){
    		
    Numero4=Numero4+i;				  		
    }//for
  
    System.out.println("\nLa sumatoria de:"   "+Numero4);    
    }

    int factorial = 1;
    
    while(Numero2!=0){
    		
    factorial=factorial*Numero2;
    Numero2--;
    }	
    
    System.out.println("\nEl Factorial Del Numero es: "+ factorial);
