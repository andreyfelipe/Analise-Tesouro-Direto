# Analise-Tesouro-Direto
O programa do tesouro nacional, o tesouro direto, atingiu em meados de 2019 a importante marca de 1 milhão de investidores, o objetivo desse estudo é dar um panorama do perfil médio desses investidores. 
Foram analisados dados de 1.048.575 investidores.
 
Os dados de operações e do cadastro são públicos e os dataset´s estão disponíveis em:
 
http://dados.gov.br/dataset/operacoes-do-tesouro-direto
 
http://dados.gov.br/dataset/investidores-do-tesouro-direto
 
Começando pelos dados cadastrais, temos:
 
Gênero:
 
Dos 1.048.575 investidores, 775.729 são do sexo masculino e 272.846 são do sexo feminino.
 
Plotando em um gráfico de pizza fica:
![Genero](https://user-images.githubusercontent.com/20607306/66218179-09cb0780-e69f-11e9-9a4d-a5aca0a68e75.png)

Idade:
 
Há uma concentração grande entre 30 e 60 anos de idade entre os investidores.

![image002](https://user-images.githubusercontent.com/20607306/66218232-26673f80-e69f-11e9-889f-a9841b9f4063.png)

Profissão:
 
As 10 principais profissões entre os investidores do tesouro direto são:
 
OUTROS                                     **227605**
ENGENHEIRO                                  **81630**
ADMINISTRADOR                               **80263**
EMPRESÁRIO                                  56121
ANALISTA DE SISTEMAS                        47413
MÉDICO                                      **44508**
ESTUDANTE                                   **43827**
ADVOGADO                                    **38066**
BANCARIO E ECONOMIÁRIO                      **29566**
APOSENTADO (EXCETO FUNCIONÁRIO PÚBLICO)     **24613**
 
Plotadas em um gráfico de pizza fica:

![image003](https://user-images.githubusercontent.com/20607306/66218256-354df200-e69f-11e9-99d8-3670a1fd01d1.png)

Estado Civil:
 
O estado civil dos investidores é:
 
Solteiro(a)                                    **484944**
Casado(a) com brasileiro(a) nato(a)            **435753**
Divorciado(a)                                   **57459**
União estável                                   **51644**
Viúvo(a)                                        **10737**
Separado judic.                                  **7873**
Desquitado(a)                                      **78**
Casado(a) com brasileiro(a) naturalizado(a)        **44**
Casado(a) com estrangeiro(a)                       **43**

![image004](https://user-images.githubusercontent.com/20607306/66218413-81009b80-e69f-11e9-9066-7de6e92cd66a.png)

De onde são os investidores do tesouro direto?
 
Há uma concentração grande no sudeste, sobretudo nas capitais.
 
Estado:
 
SP    **422390**
RJ    **132816**
MG     **88579**
PR     **62485**
RS     **56398**
SC     **45629**
DF     **38037**
BA     **31119**
GO     **22454**
ES     **21213**

![image005](https://user-images.githubusercontent.com/20607306/66218424-8bbb3080-e69f-11e9-8c0a-6b1660a9b4c0.png)

Cidades:
SAO PAULO         **210523**
RIO DE JANEIRO     **89801**
BRASILIA           **37879**
BELO HORIZONTE     **35388**
CURITIBA           **28773**
PORTO ALEGRE       **21232**
SALVADOR           **18839**
CAMPINAS           **17563**
FORTALEZA          **14462**
RECIFE             **12826**

![image006](https://user-images.githubusercontent.com/20607306/66218693-0f751d00-e6a0-11e9-8234-e1dadae32f1d.png)

 
Traçando um perfil médio a grosso modo podemos dizer que, o investidor do tesouro é na média homem, com idade entre 30 e 60 anos, com curso superior, solteiro/casado e, reside no sudeste.
 
Agora dando uma olhada mais de perto nas operações:
 
Quais são os títulos mais operados no tesouro direto?
 
Tesouro IPCA+                             **421039**
Tesouro Prefixado                         **249953**
Tesouro Selic                             **212320**
Tesouro IPCA+ com Juros Semestrais        **120258**
Tesouro Prefixado com Juros Semestrais     **44840**
Tesouro IGPM+ com Juros Semestrais           **165**
 
![image007](https://user-images.githubusercontent.com/20607306/66218759-33386300-e6a0-11e9-9968-88ff9df915bf.png)

E os valores das operações?
 
Aqui a visualização fica um pouco suja, pois há uma concentração muito grande de operações com valores mais baixos, deixando a base dos gráficos totalmente preenchidas, irei trabalhar em uma solução, talvez filtrando apenas operações abaixo de um certo valor teremos uma sensibilidade maior.
 
![image008](https://user-images.githubusercontent.com/20607306/66218772-3c293480-e6a0-11e9-9781-b3cbcbb055c6.png)
![image009](https://user-images.githubusercontent.com/20607306/66218775-3fbcbb80-e6a0-11e9-862f-d109b574bee1.png)

A média das operações é: **R$ 13.920,17**
 
A soma do volume financeiro girado (compra e venda de títulos): **R$ 14.596.339.678,91**
 
Se levarmos em conta o período de um ano de operações analisadas chegaremos a:
 
Média Mensal (soma/12): **R$ 1.216.361.639,91**
 
Média diária: (soma/(252)): **R$ 57.921.982,85**


