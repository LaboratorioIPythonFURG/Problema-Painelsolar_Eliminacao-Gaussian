# Problema
Um painel solar térmico (superfície negra ideal) possui 3 vidros completamente transparentes para a radiação solar, e com absorvidade $a$ a para a radiação infravermelha. A Figura 1 mostra o diagrama de fluxos radiatvos desse painel.

<img src="imgs/painel.png" width="400px" style="display: block; margin:auto" />

Admitindo que o sistema se encontra em equilíbrio radiativo (não existindo outros fluxos de energia para o exterior), note que os fluxos de radiação infravermelha emitida $(E0, E1, E2, E3)$ satisfazem o sistema de 4 equações:

![formula](https://render.githubusercontent.com/render/math?math=%24%24%20%5Cbegin%7Balign%2A%7D%20%5Cbegin%7Bcases%7D%20-E_0%20%2B%20E_1%20%2B%20%281-a%29E_2%20%2B%20%281-a%29%5E2E_3%2BE_S%20%26%3D%200%20%5C%5C%20aE_0%20-%202E_1%20%2B%20aE_2%20%2B%20a%281-a%29E_3%20%26%3D%200%20%5C%5C%20a%281-a%29E_0%20%2B%20aE_1%20-%202E_2%20%2B%20aE_3%20%26%3D%200%20%5C%5C%20a%281-a%29%5E2E_0%20%2B%20a%281-a%29E_1%20%2B%20aE_2%20-%202E_3%20%26%3D%200%20%5Cend%7Bcases%7D%20%5Cend%7Balign%2A%7D%24%24)

Calcule os fluxos emitidos pelas 4 superfícies, resolvendo o sistema de equações para o caso $a=0.8$, $E_S=500Wm^-2$. 

O sistema de equações lineares deve ser resolvido utilizando o método de Eliminação Gaussiana, sem e com pivotamento. 
