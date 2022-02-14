# Problema 1
Um painel solar térmico (superfície negra ideal) possui 3 vidros completamente transparentes para a radiação solar, e com absorvidade a para a radiação infravermelha. A Figura 1 mostra o diagrama de fluxos radiativos desse painel.

<img src="imgs/painel.png" width="400px" style="display: block; margin:auto" />

Admitindo que o sistema encontra-se em equilíbrio radiativo (não existindo outros fluxos de energia para o exterior), e que os fluxos de radiação infravermelha emitida (E0, E1, E2, E3) satisfazem o sistema de 4 equações:

![formula](https://render.githubusercontent.com/render/math?math=%5Ccolor%7Bwhite%7D+%5Cbegin%7Balign%2A%7D%0D%0A%5Cbegin%7Bcases%7D%0D%0A-E_0+%2B+E_1+%2B+%281-a%29E_2+%2B+%281-a%29%5E2E_3%2BE_S+%26%3D+0+%5C%5C%0D%0AaE_0+-+2E_1+%2B+aE_2+%2B+a%281-a%29E_3+%26%3D+0+%5C%5C%0D%0Aa%281-a%29E_0+%2B+aE_1+-+2E_2+%2B+aE_3+%26%3D+0+%5C%5C%0D%0Aa%281-a%29%5E2E_0+%2B+a%281-a%29E_1+%2B+aE_2+-+2E_3+%26%3D+0%0D%0A%5Cend%7Bcases%7D%0D%0A%5Cend%7Balign%2A%7D)

calcule os fluxos emitidos pelas 4 superfícies, resolvendo o sistema de equações para o caso a=0.8, E_S=500Wm^-2. 

O sistema de equações lineares deve ser resolvido utilizando o método de Eliminação Gaussiana, sem e com pivotamento. 
