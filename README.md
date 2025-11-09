# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
MOV A,P0 

MOV R0,A 

MOV B,R0 

MUL AB 

MOV P2,A 

END
```

## OUTPUT
<img width="536" height="324" alt="508693266-dbb0a874-d3b1-4b5a-bae0-7558bd2272cb" src="https://github.com/user-attachments/assets/a50b3e78-bb39-4728-8950-871c1182b5cc" />
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/414f0dc6-ee94-4010-b0cb-b06cad545fd6" />



## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END
```


## OUTPUT
<img width="439" height="320" alt="508693301-04b62ba6-2472-4be9-a62e-20399ab8c62b" src="https://github.com/user-attachments/assets/40449533-5a80-445b-84c1-e3461d7cd15b" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/b915b25d-9915-4031-98a6-4c902ec7dc61" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
