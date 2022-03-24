# cit
Flag=1;
for(i=0;i<n && flag=1;i++){
    flag=0;
    for(j=0;j<n-i-1;j++){
        if(a[j]>a[j+1]){
           temp=a[j];
           a[j]=a[j+1];
           a[j+1]=temp;
           flag=1;
        }
    }
}
