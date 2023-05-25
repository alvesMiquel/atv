# ENEM 2023
atividade do curso de logica lcc
Algoritmo "semnome"
//  
//  
// Descrição   : Aqui você descreve o que o programa faz! (função)
// Autor(a)    : Miquel Alves 
// Data atual  : 30/3/2023
Var
// Seção de Declarações das variáveis 
nome,mae,pai,CPF,datanascimento,modal, bairro:caracter
senha,confirmesenha, rendafamiliar,quantpessoas,escolhaescola,escolhanaoinseto,enem: inteiro
isencao, opum,opdois,optres,opquatro : real
carros,motos,casa,geladeiras,notbook,TVs,viaja,celular,secadoras,lavar,microondas,frezees, esc0lha: inteiro
Inicio
// Seção de Comandos, procedimento, funções, operadores, etc... 
//Inicio do cadastro basico
Repita
Escreval("enem 2023")
Escreval("1- ISENCAO")
ESCREVAL("2- INSCRICAO")
ESCREVAL("0 - SAIR ")
leia (esc0lha)
Se (esc0lha=0) entao
Escreval("fim da execusão")
// A VARIAVEL ENEM VAI SER USADA PARA MANTER O SISTEMA SEMPRE ABERTO
//ATE QUE O USUARIO DIGITE 0
//PARA ISSO FOI UTILIZADO O REPITA NO INICIO DO CODIGO QUE ESTA FINALIZANDO NO FIM
//DO CODIGO0
LEIA (ENEM)
Escreval("Informe seu nome completo")
Leia(nome)
Escreval("nome da Mae")
Leia(Mae)
Escreval("nome do Pai")
Leia(Pai)
Escreval("Informe seu CPF")
Leia(CPF)
Escreval("datanascimento")
Leia(datanascimento)
Escreval("Qual sua modalidade de estudo")
Leia(modal)
Escreval("Você estudou em escola publica")
Escreval("digite 1 para publica")
Escreval("digite 2 para particular")
Leia(escolhaescola)

//Fim das informacoes basicas
// inicio cadastro da senha
repita

Escreval("Informe sua sua senha com 6 numeros de 0 a 9")
Leia(senha)
Escreval("confirme sua senha")
leia(confirmesenha)
Se senha=confirmesenha entao
Escreval("Cadastro com sucesso")
Senao
SE <> confirmesenha entao
Escreval("Senhas nao correspondentes")
FIMSE
FIMSE
Ate senha=confirmesenha
Escreval("Pedido recebido, aguarde a aprovação")
//Essa parte do codigo vai servir como referencia
//Para aprovar ou nao a insencao
Escreval("Informe a renda familiar")
Escreval("digite 1- de 1000 a 2000")
Escreval("digite 2- de 2000 a 3000")
Escreval("digite 3- de 3000 a 4000")
Escreval("digite 4- de 5000 a 6000")
Escreval("digite 5- de 6000 ou mais")
OPUM <-2000
OPDOIS <- 3000
OPTRES <- 4000
OPQUATRO <- 5000
Leia(rendafamiliar)
Escreval("Quantas carros tem em sua casa")
Leia(carros)
Escreval("Quantas motos tem em sua casa")
leia(motos)
Escreval("Quantas casas tem")
Leia(casa)
Escreval("Quantas geladeiras tem em sua casa, quanto custou")
Leia(geladeiras)
Escreval("Quantos aparelhos celular tem em sua casa")
Leia(celular)
Escreval("Quantos aparelos de notbook tem em sua casa")
Leia(notbook)
Escreval("Quantas TVs tem em sua casa")
Leia(TVs)
Escreval("Quantos microondas tem em sua casa,quala marca")
Leia(microondas)
Escreval("Quantos frezees tem em sua casa")
Leia(frezees)
Escreval("Quantas maquinas de lavar tem em casa")
Leia(lavar)
Escreval("Quantas secadoras tem em casa")
Leia(secadoras)
Escreval("quantas pessoas moram contigo, informe")
Leia(Quantpessoas)
//a linha a baixo pega a quantidade de pessoas e da razaorenda familiar e quant. pessoas
Isencao <- (rendafamiliar/quantpessoas)
//regra de negocio para a aprovacao da isencaoentao
SE(escolhaescola=1) E (rendafamiliar=OPUM) E (quantpessoas<=4) ENTAO
SE(carro>=1) E (moto>= 1) ENTAO
ESCREVAL ("ISENCAO APROVADA")
SENAO
ESCREVAL("SUA ISENCAO NAO FOI APROVADA")         FIMSE         FIMS        //FIM DA VALIDACA      SENAO
SE (ENEM = 2 ) ENTAO
ESCREVAL("INFORME SEU CPF")
LEIA (CPFCONSULTADO)            SE (CPF = CPFCONSULTADO) ENTAO
ESCREVAL( " 1 - CONFIRMAR SUA INSCRIÇÃO ")
ESCREVAL( " 2 - PARA SAIR ")
leia (CONFIRME)
SE (CONFIRME =1 ) ENTAO
ESCREVAL("INSCRICAO REALIZADA COM SUCESSO")
ESCREVAL("NOME", NOME)
ESCREVAL("CPF",  CPF)
ESCREVAL("LOGIN", CPF)
FIMSE
FIMSE
SENAO
SE(ENEM = 3 ) ENTAO
FIMSE
FIMSE
FIMSE
ATE(ENEM = 0)
Fimalgoritmo
