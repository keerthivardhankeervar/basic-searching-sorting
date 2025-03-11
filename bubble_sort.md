# Bubble Sort

Bubble sort psuedocode

```
# Write the psuedocode 
START  
  READ array A of size N  
  REPEAT (N-1) times  
    SWAPPED = false  
    FOR i = 0 TO N-2  
      IF A[i] > A[i+1] THEN  
        SWAP A[i] and A[i+1]  
        SWAPPED = true  
      END IF  
    END FOR  
    IF SWAPPED = false THEN  
      BREAK  
    END IF  
  END REPEAT  
PRINT sorted array A  
END
```
