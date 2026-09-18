# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:

<img width="929" height="1280" alt="image" src="https://github.com/user-attachments/assets/e801bdd2-8834-49ba-b785-73a528e75a7a" />

<img width="1055" height="1280" alt="image" src="https://github.com/user-attachments/assets/25324ba9-7370-440f-b9ea-4e81aeabf7c9" />

<img width="1040" height="1280" alt="image" src="https://github.com/user-attachments/assets/1d2153b9-79e1-4f3a-8e86-8b8a25de0fb6" />

<img width="1280" height="883" alt="image" src="https://github.com/user-attachments/assets/78228c04-ff51-4a13-b356-0268a43b8c22" />

## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 
```
num=[1] 
den=[1 15 50 0]
sys=tf(num,den)
rlocus(sys)
[k poles]=rlocfind(sys)
```
## Output:

<img width="699" height="626" alt="image" src="https://github.com/user-attachments/assets/07e393e0-26db-4427-91c3-006cc4555e41" />

<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/51ae39c2-d5f5-41d2-ab00-d27e4328d009" />


## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 744.551 .
