def solution(statues):
    summation = 0
    
    # arrange statues in ascending order
    for i in range(0, len(statues)):    
        for j in range(i+1, len(statues)):    
            if(statues[i] > statues[j]):    
                temp = statues[i];    
                statues[i] = statues[j];    
                statues[j] = temp;    
     
    # calculate summation of statue heights needed to lead to one unit incremental increases
    for i in range(len(statues)-1):
        if (statues[i+1] - statues[i]) > 1:
            number = statues[i+1] - statues[i] - 1
            summation = summation + number
            
    return summation
    
        
        

