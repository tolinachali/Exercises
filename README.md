# This is a summary of some finding on complexity and  GC calc project
 
# Q#1 Add a logger method to the complexity project and Add a parameter using parseargs that sets nmax
timing data will be written to <C:\Users\HP\Advancedprogramming\day8\my_Exercise\fibonacci_timing_0_to_10.tsv>
---done
![fibonacci_timing_0_to_10](https://user-images.githubusercontent.com/130226558/234590363-9dce85b6-996d-4232-8c43-abde5f24bcbe.png)


# Q#2. Generate logo plots and calculate GC frequency for all miRNAs for mouse, human and rat

![image](https://user-images.githubusercontent.com/130226558/234662199-4ab99167-2343-4acd-ad14-253302c648ac.png)

## GC percent for hsa
average GC % = <70.05512368618675>
The number of sequences are:  2656
## GC frequency for hsa is 
 
  A         C         G         T
0  0.249284  0.236867  0.282235  0.231614
1  0.244986  0.227794  0.295129  0.232092
2  0.205826  0.247373  0.346705  0.200096
3  0.218243  0.225883  0.323782  0.232092
4  0.225883  0.257402  0.284623  0.232092
5  0.239733  0.244031  0.278415  0.237822
6  0.217287  0.267431  0.256447  0.258835

 ## Logger method for hsa
  
2023-04-24 23:15:03,284 - root - INFO - +******************************************************************************+
2023-04-24 23:15:03,285 - root - INFO - project log file is <C:\Users\tolex\Advancedprogramming\day9\levenshtein\logfiles\__20230424_231503__3697017c62772d71b4445895933026a4.log>
2023-04-24 23:15:03,286 - root - INFO - +******************************************************************************+
2023-04-24 23:15:03,286 - root - DEBUG - debug mode is on
 ## And the logo plot  for hsa is 
![mature__uniqseeds_logoplt](https://user-images.githubusercontent.com/130226558/234088020-aaaae7e0-a799-469a-997a-de55491e1030.png)

## GC percent for rat is 
Average GC % = <70.50310821391368>
The number of sequences are:  1978
## GC frequency for mmu is 

 A         C         G         T
0  0.249284  0.236867  0.282235  0.231614
1  0.244986  0.227794  0.295129  0.232092
2  0.205826  0.247373  0.346705  0.200096
3  0.218243  0.225883  0.323782  0.232092
4  0.225883  0.257402  0.284623  0.232092
5  0.239733  0.244031  0.278415  0.237822
6  0.217287  0.267431  0.256447  0.258835

## Logger method for mmu is 
2023-04-26 11:52:52,481 - root - INFO - +****************************************************************************************************+
2023-04-26 11:52:52,482 - root - INFO - project log file is <C:\Users\HP\Advancedprogramming\day8\my_Exercise\logfiles\mature__20230426_115252__3697017c62772d71b4445895933026a4.log>
2023-04-26 11:52:52,483 - root - INFO - +****************************************************************************************************+
2023-04-26 11:52:52,483 - root - DEBUG - debug mode is on

## and the logo plot fo rat  is 
  ![mature__uniqseeds_logoplt](https://user-images.githubusercontent.com/130226558/234096058-ebf8c980-d78a-47ec-a457-1017b8da2546.png)

## GC percent for rno
 Average GC % = <67.4683526671524>
The number of sequences are:  764
 ## GC frequency for rno  is 
    A         C         G         T
0  0.277165  0.223622  0.288189  0.211024
1  0.251969  0.220472  0.270866  0.256693
2  0.242520  0.237795  0.307087  0.212598
3  0.244094  0.223622  0.264567  0.267717
4  0.226772  0.262992  0.231496  0.278740
5  0.277165  0.215748  0.255118  0.251969
6  0.222047  0.280315  0.222047  0.275591

  ## Logger method for for rno is 

2023-04-26 12:02:21,785 - root - INFO - +****************************************************************************************************+
2023-04-26 12:02:21,786 - root - INFO - project log file is <C:\Users\HP\Advancedprogramming\day8\my_Exercise\logfiles\mature__20230426_120221__3697017c62772d71b4445895933026a4.log>
2023-04-26 12:02:21,786 - root - INFO - +****************************************************************************************************+
2023-04-26 12:02:21,787 - root - DEBUG - debug mode is on

##  and the logo plot fo rno   is 
  
  ![mature__uniqseeds_logoplt](https://user-images.githubusercontent.com/130226558/234099403-f5b07b43-7b80-4156-99f8-b7a1b7f26649.png)
