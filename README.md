# fernanda
Teste
Questões 

A – Com suas palavras explique o que é lavagem de dinheiro. 

De modo simplificado a lavagem de dinheiro tem como objetivo difundir na economia recursos de todos os tipos  como imóveis e dinheiro de origem ilícita. Para isso muitas vezes será utilizado um processo de 3 partes que são separadas mas podem ocorrer simultaneamente. 
Elas são primeiro afastar o recurso de sua origem criminosa, assim evitando a associação direta entre crime e recursos; Segundo passar  recurso através de várias movimentações assim dificultando ainda mais o rastreamento; E por fim a 3 parte a disponibilidade do recurso que agora se encontra lícito para o criminoso.
As etapas 1 e 2 podem ser repetidas várias vezes até que o dinheiro se encontre “limpo”.

Fonte:https://www.gov.br/fazenda/pt-br/assuntos/prevencao-lavagem-dinheiro



B – O que é Cartão de Pagamento do Governo Federal (CPGF), e qual a sua finalidade.

De maneira resumida o CPGF seria parecido com um cartão de crédito utilizado pelo governo e seus servidores para agilizar e simplificar alguns tipos de gastos, esses gastos devem estar dentro do parâmetros do suprimentos de fundos. Com o cartão temos uma maior transparência e facilidade na prestação de contas.

Fonte:https://www.portaltransparencia.gov.br/pagina-interna/603242-cartao-de-pagamento-do-governo-federal



C – Quem pode utilizar o CPGF? 

O governo e seus servidores.



D – Qual a URL onde é possível fazer o download dos arquivos do CPGF?

https://www.portaltransparencia.gov.br/download-de-dados/cpgf



E – Qual a URL da paǵina com a descrição dos campos (ou dicionário de dados) da CPGF?

https://www.portaldatransparencia.gov.br/pagina-interna/603393-dicionario-de-dados-cpgf



F – É possível identificar o nome e o documento do portador do CPGF, em todas as movimentações ou há movimentações onde não é possível identificar o portador? 

Em sua maioria sim temos como identificar o nome e o documento do portador CPGF, sua exceção ocorre quando a despesa entra em caráter sigiloso que segue suas próprias regras.



G – É possível identificar o Órgão do portador do CPGF? 

Sim, temos órgão do portador como também o órgão superior.



H - Qual o nome do Órgão cujo código é 20402? 

Seria Agência Espacial Brasileira



I - É possível identificar o Nome e Documento (CNPJ) dos favorecidos pela utilização do CPGF? 

Em sua maioria sim, a exceção será as despesas em caráter sigiloso



J – É possível identificar a data e o valor das movimentações financeiras do CPGF, em todas as movimentações? Ou há movimentações onde não é possível identificar as datas e ou valores? 

Pode-se identificar os valores em todas as movimentações, já as datas em sua maioria temos o acesso a não ser quando se trata de uma despesa sigilosa.



K (código) – Qual a soma total das movimentações utilizando o CPGF? 

![image](https://user-images.githubusercontent.com/98679482/151687662-5d4f3df5-9ea2-4bdc-958a-ed242eadf7ec.png)



L (código) – Qual a soma das movimentações sigilosas ? 

![image](https://user-images.githubusercontent.com/98679482/151687798-66431693-fdba-485c-8c4f-56a498287634.png)



M (código) – Qual o Órgão que mais realizou movimentações sigilosas no período e qual o valor (somado)? 

Orgão que mais reslizou movimentação sigilosa foi o Ministério da Justiça e Segurança Pública.
![image](https://user-images.githubusercontent.com/98679482/151687912-d0a76f13-0e56-4fd3-95a7-ce80ae3ca9db.png)

O valor somado dos gastos sigilosos do Ministério da Justiça e Segurança Pública.
![image](https://user-images.githubusercontent.com/98679482/151687920-d95a5695-36aa-4854-b268-26036c4111b8.png)



N (código) – Qual o nome do portador que mais realizou saques no período? Qual a soma dos saques realizada por ele? Qual o nome do Órgão desse portador? 

Nome do portador que mais realizou saque e o nome do seu órgão superior
![image](https://user-images.githubusercontent.com/98679482/151688020-93911119-950f-4510-807e-e6ff7da0dd01.png)

A soma de saque realizado por ele.
![image](https://user-images.githubusercontent.com/98679482/151688083-88961225-6cd9-4be1-9536-69dce038ba51.png)



O (código) – Qual o nome do favorecido que mais recebeu compras realizadas utilizando o CPGF? 

A empresa que mais favorecida será o "MERCADOPAGO.COM REPRESENTACOES LTDA", já no geral serão as movimentaçãos sigilosas.
![image](https://user-images.githubusercontent.com/98679482/151688180-92cc4ab8-0987-48b9-a2aa-222a176aa5ff.png)



P - Descreva qual a abordagem utilizada para desenvolver o código para os ítens de K a O.
RESPOSTA===> 
Para conseguir a resposta da questão "K", utilizei o comando “sum” para somar todas as linhas da coluna de “Valor de Transação”, resultando na soma de todos os movimentos do mês de outubro.
Na questão "O" fiz em duas partes, a primeira fiz um “select” na coluna “Nome Favorecido” e também realizei o comando “sum” na coluna “Valor de Transação''. Por fim utilizei “group by” para agrupar as instruções do “select”





