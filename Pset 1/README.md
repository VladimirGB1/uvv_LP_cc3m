# Pset 1
#### Questão 1:
#### O resultado esperado seria: [226, 166, 119, 55], pois 255 - 29 = 226, 255 - 89 = 166 e assim por diante.

#### Questão 2:
![bluegillInvertida](https://github.com/VladimirGB1/uvv_LP_cc3m/blob/main/Pset%201/Imagens/bluegillInvertida.png)

#### Questão 3:
#### Ox,y= (80 × 0.00) + (53 × (-0.07)) + (99 × 0.00) +
####       (129 × (-0.45)) + (127 × 1.20) + (148 × (-0.25)) +
####       (175 × 0.00) + (174 × (-0.12)) + (193 × 0.00)

#### Ox,y: 0 + (-3.71) + 0 +
####       -58.05 + 152.4 + (-37) +
####       0 + (-20.88) + 0

#### Ox,y = -3.71 - 58.05 + 152.4 - 37 - 20.88
#### Ox,y = 32.76

#### Questão 4:
![pigbirdKernel.png](https://github.com/VladimirGB1/uvv_LP_cc3m/blob/main/Pset%201/Imagens/pigbirdKernel.png)

#### Questão 5:

#### matriz de desfoque de 3x3:
#### K = [[2 2 2
####     [2 2 2]
####     [2 2 2]]
#### A soma de todos os elementos de K é 18. portanto o kernel seria:
#### k = [[2/18 2/18 2/18]
####     [2/18 2/18 2/18]
####     [2/18 2/18 2/18]]
#### exeplo de imagem desfocada B de tamanho 5x5:
#### B =
#### [[10 20 30 40 50]
#### [15 25 35 45 55]
####[20 30 40 50 60]
#### [25 35 45 55 65]
#### [30 40 50 60 70]]
#### o valor do pixel na posição (2,2) da imagem nítida como exemplo:
#### (2,2) = (152/18 + 252/18 + 352/18 + 202/18 + 302/18 + 402/18 + 202/18 + 302/18 + 40*2/18)
#### calculo:
#### (2,2) = (152/18 + 252/18 + 352/18 + 202/18 + 302/18 + 402/18 + 202/18 + 302/18 + 40*2/18)
#### = (30/18 + 50/18 + 70/18 + 40/18 + 60/18 + 80/18 + 40/18 + 60/18 + 80/18)
#### = (330/18)
#### = 18.33
 

![pythonFocada.png](https://github.com/VladimirGB1/uvv_LP_cc3m/blob/main/Pset%201/Imagens/pythonFocada.png)
#### Questão 6:
#### Basicamente o que o kernel X faz e destacar as bordas horizontas e o kernel y destaca as bordas verticais.
![constructBordas.png](https://github.com/VladimirGB1/uvv_LP_cc3m/blob/main/Pset%201/Imagens/constructBordas.png)
