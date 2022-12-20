<img width=100% src="https://capsule-render.vercel.app/api?type=rect&color=0:2B32B2,100:1488CC&section=header&height=120&text=Análise%20de%20licitações%20da%20UFPR&desc=Tratamento%20e%20visualização%20de%20dados&animation=fadeIn&fontColor=ffffff&fontSize=30&descSize=15&fontAlignY=45&descAlignY=70"/>

<div> 
<img align=right width="28%" height="28%" src="https://www.ufpr.br/portalufpr/wp-content/uploads/2015/11/ufpr_logo.jpg">
  
## Sobre o projeto
Os datasets tratados e analisados neste projeto são referentes às licitações realizadas pela Universidade Federal do Paraná entre os anos de 2014 e 2020. Os arquivos podem ser encontrados no [Portal de Dados Abertos](https://dados.gov.br/dados/conjuntos-dados) do governo federal. Neste repositório é possível encontrar o código utilizado no processo, bem como alguns gráficos construídos com as informações obtidas.
</div>
&nbsp;

## Sobre o tema
>"Licitação é o conjunto de procedimentos administrativos (administrativos porque parte da Administração Pública) para as compras ou serviços contratados pelos governos Federal, Estadual ou Municipal, ou seja todos os entes  federativos. 
De forma mais simples, podemos dizer que o governo deve comprar e contratar serviços seguindo regras de lei, assim a licitação é um processo formal onde há a competição entre os interessados em oferecer produtos e serviços à Administração."

>"É necessário licitar porque o Poder Público tem este dever conforme é exigido pelo art. 37 da Constituição Federal. O processo licitatório é a maneira mais eficaz de assegurar que as contratações públicas ocorram de modo transparente, isonômico e sustentável."

## Tecnologias utilizadas
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-103b91.svg?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/try)
[![Python](https://img.shields.io/badge/python-103b91?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-103b91?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/pt-br/microsoft-365/excel)

### Bibliotecas
[![Pandas](https://img.shields.io/badge/pandas-545454.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/numpy-545454.svg?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Locale](https://shields.io/badge/LOCALE-545454?style=for-the-badge&logo=python&logoColor=white)](https://docs.python.org/pt-br/3.8/library/locale.html)


[![Glob](https://shields.io/badge/GLOB-545454?style=for-the-badge&logo=python&logoColor=white)](https://docs.python.org/3/library/glob.html#module-glob)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-545454?style=for-the-badge&logo=python&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-545454?style=for-the-badge&logo=python&logoColor=white)](https://matplotlib.org/)

## Conhecendo os dados
### Esquema original
|                         Coluna |                                                                              Descrição |
|:-------------------------------|:---------------------------------------------------------------------------------------|
|                            Ano |                                                                      Ano de referência |
|        Modalidade de licitação |                                          Modalidade entre os vários tipos de licitação |
|                     Número/ano |                  Número que identifica a licitação por modalidade no ano de referência |
|                       Processo |                              Número do processo administrativo de trâmite da licitação |
|                       Situação |          Situação em que a licitação se encontra no processo de trâmite administrativo |
|                         Objeto |                                                                    Objeto da licitação |
|             Natureza do objeto |                                                            Natureza do objeto licitado |
|                     Demandante |                                        Unidade Administrativa que solicita a licitação |
|           Modalidade de compra |                                                                Modalidade de aquisição |
|               Homologação(mês) |                                                        Mês de homologação da licitação |
|            Valor estimado UFPR |           Valor, em reais, aos recursos estimados para o objeto da licitação pela UFPR |
|   Valor estimado outros órgãos |   Valor, em reais, aos recursos estimados para o objeto da licitação por outros órgãos |
|          Valor contratado UFPR |         Valor, em reais, aos recursos contratados para o objeto da licitação pela UFPR |
| Valor contratado outros órgãos | Valor, em reais, aos recursos contratados para o objeto da licitação por outros órgãos |

## Alguns gráficos obtidos

<img width="60%" height="60%" src="https://raw.githubusercontent.com/maisumdiego/Licitacoes_UFPR/master/Processos%20homologados%20por%20ano.jpeg">
<img width="100%" height="100%" src="https://raw.githubusercontent.com/maisumdiego/Licitacoes_UFPR/master/Modalidades%20e%20outras%20Homologadas.jpeg">
<img width="60%" height="60%" src="https://raw.githubusercontent.com/maisumdiego/Licitacoes_UFPR/master/Valor%20m%C3%A1ximo%20por%20ano.jpeg">

## Relatórios completos
O arquivo do relatório completo do tratamento de dados está disponível no arquivo [Tratamento de Dados](https://github.com/maisumdiego/Licitacoes_UFPR/blob/master/Tratamento%20de%20Dados.ipynb), já os gráficos obtidos podem ser encontrados no arquivo [Relatório de Análise de Dados](https://github.com/maisumdiego/Licitacoes_UFPR/blob/master/Relat%C3%B3rio%20de%20An%C3%A1lise%20de%20Dados%20I.ipynb) ou no próprio repositório.
