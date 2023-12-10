# Automata_note
 BUPTans, study_note

## 3.DFA

#### Concept

<img src="CleanShot 2023-10-28 at 14.03.24@2x.png" alt="CleanShot 2023-10-28 at 14.03.24@2x" style="zoom:25%;" />

<img src="CleanShot 2023-10-28 at 14.59.40@2x.png" alt="CleanShot 2023-10-28 at 14.59.40@2x" style="zoom:25%;" />

>Transition function

<img src="CleanShot 2023-10-28 at 14.03.49@2x.png" alt="CleanShot 2023-10-28 at 14.03.49@2x" style="zoom:25%;" />   

> Transition Table

<img src="CleanShot 2023-10-28 at 14.31.52@2x.png" alt="CleanShot 2023-10-28 at 14.31.52@2x" style="zoom:25%;" />

> Example

<img src="CleanShot 2023-10-28 at 14.06.15@2x.png" alt="CleanShot 2023-10-28 at 14.06.15@2x" style="zoom:25%;" />

#### 🌟**PPT**🌟

## 4.NFA

#### Concept

<img src="CleanShot 2023-10-28 at 14.26.55@2x.png" alt="CleanShot 2023-10-28 at 14.26.55@2x" style="zoom:25%;" />

<img src="CleanShot 2023-10-28 at 14.59.00@2x.png" alt="CleanShot 2023-10-28 at 14.59.00@2x" style="zoom:25%;" />

>Example

<img src="CleanShot 2023-10-28 at 14.30.02@2x.png" alt="CleanShot 2023-10-28 at 14.30.02@2x" style="zoom:25%;" />

<img src="CleanShot 2023-10-28 at 14.30.48@2x.png" alt="CleanShot 2023-10-28 at 14.30.48@2x" style="zoom:25%;" />

## 5.Minimal NFA

![CleanShot 2023-10-28 at 16.40.07@2x](CleanShot 2023-10-28 at 16.40.07@2x.png)

#### 🌟作业题🌟

## 6.RE

#### Concept

![CleanShot 2023-10-28 at 18.43.49@2x](/Users/ri/Desktop/大二上/自动坤/Automata_note/CleanShot 2023-10-28 at 18.43.49@2x.png)

![CleanShot 2023-10-28 at 16.54.22@2x](/Users/ri/Desktop/大二上/自动坤/Automata_note/CleanShot 2023-10-28 at 16.54.22@2x.png)

#### Example

##### RE->RL

![CleanShot 2023-10-28 at 16.58.18@2x](CleanShot 2023-10-28 at 16.58.18@2x.png)

![CleanShot 2023-10-28 at 18.45.03@2x](/Users/ri/Desktop/大二上/自动坤/Automata_note/CleanShot 2023-10-28 at 18.45.03@2x.png)

##### RL->RE

![CleanShot 2023-10-28 at 18.48.04@2x](CleanShot 2023-10-28 at 18.48.04@2x.png)

![CleanShot 2023-10-28 at 18.48.44@2x](CleanShot 2023-10-28 at 18.48.44@2x.png)

![CleanShot 2023-10-28 at 18.49.30@2x](/Users/ri/Desktop/大二上/自动坤/Automata_note/CleanShot 2023-10-28 at 18.49.30@2x.png)

##### RE->NFA

![CleanShot 2023-10-28 at 18.58.05@2x](/Users/ri/Desktop/大二上/自动坤/Automata_note/CleanShot 2023-10-28 at 18.58.05@2x.png)

##### AF->RE 看ppt！！！🌟

## 7.RG

#### 定义

![CleanShot 2023-11-25 at 13.19.35@2x](/Users/ri/Desktop/大二上/自动坤/Automata_note/CleanShot 2023-11-25 at 13.19.35@2x.png)

![CleanShot 2023-11-25 at 13.18.48@2x](/Users/ri/Desktop/大二上/自动坤/Automata_note/CleanShot 2023-11-25 at 13.18.48@2x.png)

## 8. property of RL

### **CLOSURE PROPERTIES** 

#### union

####  intersection

#### concatenation

#### star- closure

#### complementation

#### difference

<img src="/Users/ri/Desktop/大二上/自动坤/Automata_note/CleanShot 2023-11-25 at 15.08.55@2x.png" alt="CleanShot 2023-11-25 at 15.08.55@2x" style="zoom:25%;" />

#### reversal

#### homomorphism

#### right quitient

### pumping lemma 🌟🌟

## 9. cfl

## 11. cfg simplification

<img src="/Users/ri/Desktop/大二上/自动坤/Automata_note/CleanShot 2023-11-25 at 16.31.21@2x.png" alt="CleanShot 2023-11-25 at 16.31.21@2x" style="zoom:25%;" />

<img src="/Users/ri/Desktop/大二上/自动坤/Automata_note/CleanShot 2023-11-25 at 16.34.15@2x.png" alt="CleanShot 2023-11-25 at 16.34.15@2x" style="zoom:25%;" />

<img src="/Users/ri/Desktop/大二上/自动坤/Automata_note/CleanShot 2023-11-25 at 16.36.47@2x.png" alt="CleanShot 2023-11-25 at 16.36.47@2x" style="zoom:25%;" />

<img src="/Users/ri/Desktop/大二上/自动坤/Automata_note/CleanShot 2023-11-25 at 17.19.01@2x.png" alt="CleanShot 2023-11-25 at 17.19.01@2x" style="zoom:25%;" />

## 12.cnf & gnf &CYK

### 1.CNF

==Chomsky Normal Form==

> The string on the right of a production consist of **no more**
> **than two symbols.**

1. simelify
2. terminal sign 
3. two to one

### 2.GNF

==Greibach Normal Form==

>A context-free grammar is said to be in Greibach normal form if all productions have the form
>
>**A->aX**,

### 3.CYK





## 13.PDA

### difine

# 单词

prime number

composite number
