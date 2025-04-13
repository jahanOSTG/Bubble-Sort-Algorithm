
# Bubble Sort Algorithm

## Procedure:

###  Step 1: Start  
### Step 2: Input the size of the array `n`  
###  Step 3: Declare an array `a[n]`  
###  Step 4: Input `n` elements into the array `a`  

---

### Step 5: Perform Bubble Sort

```
For i = 0 to n - 2 do  
    For j = 0 to n - i - 2 do  
        If a[j] > a[j + 1] then  
            Swap a[j] and a[j + 1]  
        End If  
    End For  
End For  
```

---

###  Step 6: Print the sorted array  
###  Step 7: End  

---

##  Complexity 

- ##  **Time Complexity**:
  - Worst Case: **O(n²)**  
  - Average Case: **O(n²)**  
  - Best Case (when array is already sorted): **O(n)**

- ## **Space Complexity**:
  - **O(1)** (In-place sorting)
