# DatathONS2
Esse repositório é de um desafio proposto pela ONS (Operador Nacional do Sistema Elétrico). É um projeto feito em conjunto com Flávio e Marcelo, membros de meu time.

O desafio:
O ONS trabalha com ponte entre os membros da Rede Básica de energia. Seu papel, nesse desafio, é garantir a conformidade das informações nos contratos entre usuários (geradores de energia) e o agente de transmissão. Até julho de 2022, foram recebidos cerca de 500 contratos do tipo CCT (contrato firmado entre usuário e transmissor). Estes contratos precisam ser analisados manualmente, o que demanda muito tempo. Assim sendo, nosso objetivo é fazer com que essa validação seja feita de forma automizada.

Nosso Roadmap

A primeira parte que entendemos é que as validações possuem níveis de complexidade diferentes. Assim sendo, dividir os esforços em busca de solucionar aquilo que pode ser feito de forma menos elegante pode ser positivo. Nos primeiros grupos (1 a 3), tentamos solucionar o problema sem utilização da utilização de técnicas de NLP.

#Bibliotecas utilizadas


Grupo 1 a 3:

A solução que buscamos é simples: 
Importamos os dados fornecidos (https://dados.ons.org.br/dataset/datathons-4a-edicao/resource/ab00a0d6-63a2-4db9-b1c5-4cf79f1c7796) dos contratos e descompactamos-os.


