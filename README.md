# Desafio Segmentacao Imagens
Desafio de segmentação, em que retiro o fundo da imagem mantendo os dados centrais.

Problema :  Ao retirar uma foto de um documento sobre a mesa, pode ser que as bordas(fundos) apareçam na imagem.

Objetivo : Retirar esse fundo de forma simples e eficaz, não aumentando o processamento da máquina.

Possivel solução :  
1 Passo - Passar a imagem primeiramente no filtro de média para deixar mais consistente os pixels.<br>
2 Passo - Usar o filtro threshhold para binarizar a imagem.<br>
3 Passo - E retirar os valores abaixo de 4bit.<br>
