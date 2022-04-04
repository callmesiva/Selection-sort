# Selection-sort


     int arr[]={6,5,8,9,2};
     for(int i=0; i<arr.length-1;i++)
      {
        int min=arr[i];
        
        for(int j=i+1; j<arr.length; j++)
        {
          if(min>arr[j])
          {
            min = arr[j];
            arr[j]=arr[i];
            arr[i]=min;
          }
        }
        
      }
      
          for(int i=0; i<arr.length; i++)
          {
            System.out.print(arr[i]+" ");
           }
      
