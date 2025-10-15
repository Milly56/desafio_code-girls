
# Desafio da Code Girls 

este repositório é para documentar sobre o meu desafio da Dio, cujo objetivo é consolida meus conhecimentos sobre ECS2 na AWS. 
# Objetivo do Desafio
 Entendimento da EC2.
 Conhecer os diferentes tipos de instância.
 Entender como EC2 se conectar com outros serviços(Lambda e entre outros).

# O que foi aprendido
EC2(Elastic Compute Cloud): São máquinas virtuais que é dentro da aws que pode ser Windows ou Linux.

tem tipo de instâncias como de uso geral, computação otimizada,memória otimizada,espaço otimizado,computação acelerada.

Ami( Amazon Machine Image): criar as imagem da instância, é uma imagem de máquina virtual pré-configurada.

EBS(Amazon Elastic Block Store): é um serviço para fornecer armazenamento em bloco fiável(também conhecido como volumes ou discos rígidos), ele faz parte do modelo IAAS.

S3(Amazon Simple Storage Service): tem um recurso se chamado lambda, é onde jogo os meus objetos na nuvem, ele possui algumas classes de storage onde conseguimos economizar os custos.  

# Diferença entre EBS e S3
A diferença entre imagem e snapshot é que a imagem de máquina da amazon(ami) faz o backup de um servidor inteiro, enquanto, a snapshot é uma cópias em pontos no tempo de um volume do Amazon EBS, que são armazenadas no Amazon S3.

# Cenário Atual
Durante o desafio, criei um cenário sobre uma Clinaca de Veterinária sobre o envio de arquivo para nuvem.

EC2(Hospeda o Sistema)
EBS(armazemento interno)
S3(Guarda os documentos)
Lambda(processa automaticamente os arquivos do S3)





