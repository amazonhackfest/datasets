# Datasets
 Um conjunto de datasets para auxiliar os participantes do 1º Amazon Hackfest - Contra a Corrupção.
 
<!-- toc -->

  * [Presenças, votações e votos dos deputados federais na câmara](#presenças-votações-e-votos-dos-deputados-federais-na-câmara)
  * [Discursos dos deputados federais na câmara](#discursos-dos-deputados-federais-na-câmara)
  * [Gastos da Cota para Exercício da Atividade Parlamentar dos deputados federais](#gastos-da-cota-para-exercício-da-atividade-parlamentar-dos-deputados-federais)
  * [Prestação de contas dos partidos de 2007-2017](#prestação-de-contas-dos-partidos-de-2007-2017)
  * [Repositório de dados eleitorais](#repositório-de-dados-eleitorais)
  * [SICONV: uso de verba do governo federal por municípios e estados (e universidades, institutos, ...) via convênios](#siconv-uso-de-verba-do-governo-federal-por-municípios-e-estados-e-universidades-institutos--via-convênios)
  * [Compras Governamentais](#compras-governamentais)
  * [Nuvem Cívica](#nuvem-cívica)
  * [Portal da Transparência da Prefeitura de Manaus](#portal-da-transparência-da-prefeitura-de-Manaus) 
  * [Receitas e Despesas Públicas – Portal da Transparência](#receitas-e-despesas-públicas-portal-da-transparência) 
  * [Sanções – Portal da Transparência](#sanções-portal-da-transparência) 
  * [Servidores Civis e Militares do Executivo Federal – Portal da Transparência](#servidores-civis-e-militares-do-executivo-federal-portal-da-transparência) 
  * [Dirigentes de Empresas – Portal da Transparência](#dirigentes-de-empresas-portal-da-transparência) 
  * [Programas Sociais Bolsa Família – Portal da Transparência](#programas-sociais-bolsa-família-portal-da-transparência) 
  * [Cartões de Pagamento – Portal da Transparência](#cartões-de-pagamento-portal-da-transparência) 
  * [Seguro Defeso – Portal da Transparência](#seguro-defeso-portal-da-transparência)
  * [Pedidos e Respostas do e-SIC](#pedidos-e-respostas-do-e-sic)
  * [Webservice do e-OUV](#webservice-do-e-ouv)
  * [Relatórios da CGU](#relatórios-da-cgu)
  * [Dados sistematizados sobre parlamentares, seus gastos, parentes, empresas onde eles gastaram e discursos](#dados-sistematizados-sobre-parlamentares-seus-gastos-parentes-empresas-onde-eles-gastaram-e-discursos)
  * [Projeto Brasil.IO](#projeto-brasil-io)
  * [Contribuindo](#contribuindo)

<!-- tocstop -->

---
 
### Presenças, votações e votos dos deputados federais na câmara
?    | ! |
 --- | --|
*O que é* | Dados das presenças, das propostas votadas e dos votos individuais dos deputados federais. |
*Formato* | Em xml através de uma API da câmara ou em csvs [neste repositório](https://github.com/nazareno/dados-da-camara-federal). |
*Dicas*   | Tem bastante dado a mais na API da câmara, inclusive discursos dos deputados. |
*Projetos usando* | [House of Cunha](http://www.houseofcunha.com.br)  |

---

### Discursos dos deputados federais na câmara
?    | ! |
 --- | --|
*O que é* | Dados dos discursos de nossos representantes da câmara. |
*Formato* | Em xml através de uma API da câmara |
*Url*     | [Na API de dados abertos da câmara](http://www2.camara.leg.br/transparencia/dados-abertos/dados-abertos-legislativo/webservices/sessoesreunioes-2/obterinteiroteordiscursosplenario) |
*Dicas*   | Às vezes os exemplos da API não funcionam tal qual estão na página, mas mudando um pouco dá certo.  |
*Projetos usando* | [Retórica Parlamentar](http://retorica.labhackercd.net/), [Matéria do NEXO](http://cidadania20.com/projectos/deputados-federais-em-plenario/) |

---

### Gastos da Cota para Exercício da Atividade Parlamentar dos deputados federais
?    | ! |
 --- | --|
*O que é* | Cada deputado tem cerca de R$50 mil / mês para gastar em sua atividade parlamentar. A câmara abriu os dados de todos esses gastos para que a população fiscalize. |
*Formato* | A câmara disponibiliza arquivos XML, JSON, CSV e XLSX compactados para download contendo os dados relativos aos gastos parlamentares registrados na Câmara dos Deputados. |
*Url*     | Direto no [site da câmara](http://www2.camara.leg.br/transparencia/cota-para-exercicio-da-atividade-parlamentar/dados-abertos-cota-parlamentar) |
*Dicas*   | Tem bastante dado a mais na API da câmara, inclusive discursos dos deputados. |
*Projetos usando* | [House of Cunha](http://www.houseofcunha.com.br), [Serenata de Amor](http://serenatadeamor.org) |

---

### Prestação de contas dos partidos de 2007-2017
?    | !  |
 --- | -- |
*O que é* | Íntegra das contas anuais dos diretórios nacionais dos partidos e seus demonstrativos |
*Formato* | CSV |
*Url*     | http://www.tse.jus.br/partidos/contas-partidarias/prestacao-de-contas/contas-anuais/prestacao-de-contas-partidarias |
*Dicas*   | Pode ser interessante cruzar os nomes dos candidatos com os dos parlamentares na API da câmara.  |
*Projetos usando* | [De onde vem o dinheiro nas eleições de 2016?](https://nazareno.shinyapps.io/minha-cidade/)

---

### Repositório de dados eleitorais
?    | !  |
 --- | -- |
*O que é* | O Repositório de dados eleitorais é uma compilação de informações brutas das eleições, desde as de 1945, voltada para pesquisadores, imprensa e pessoas interessadas em analisar os dados de eleitorado, candidaturas, resultados e prestação de contas. |
*Formato* | CSV |
*Url*     | http://www.tse.jus.br/eleicoes/estatisticas/repositorio-de-dados-eleitorais-1/repositorio-de-dados-eleitorais |
*Dicas*   |  |
*Projetos usando* |  | 

---

### SICONV: uso de verba do governo federal por municípios e estados (e universidades, institutos, ...) via convênios
?    | !  |
 --- | -- |
*O que é* | Boa parte das obras estruturantes e grandes serviços dos municípios e estados é feito com verba federal obtida via convênios. O SICONV tem dados abertos detalhados sobre os convênios celebrados, licitações e pagamentos envolvidos, se a prestação de contas foi aceita ou houve problema, e o cronograma disso tudo. Tem também informação dizendo se a verba do convênio é resultante de uma emenda parlamentar de um deputado federal ou senador. |
*Formato* | CSVs |
*Url*     | http://portal.convenios.gov.br/download-de-dados  |
*Dicas*   | Há um MER na página. Os csvs são atualizados diariamente. Esses csvs são mais completos que a API de convênios. Prestação de contas rejeitada é sinal de que o convênio não foi executado corretamente. Deputados alocam verbas via emendas parlamentares que acabam sendo executadas como convênios. |
*Projetos usando* | [As Diferentonas](https://github.com/nazareno/diferentonas-server/), [Na emenda dos deputados](https://github.com/CelioBarros/NaEmendaDeputado), Quase todos [os apps que participaram do hackathon do MJ](https://github.com/LabPi) |

---

### Compras Governamentais
?    | ! |
 --- | --|
*O que é* | API de acesso para dados abertos do Sistema Integrado de Administração e Serviços Gerais - SIASG. O SIASG é o sistema onde se operacionaliza as compras do Governo Federal. Essa operacionalização se dá em diversos módulos, contemplando o catálogo de materiais e serviços (CATMAT / CATSER), o cadastramento e divulgação da licitação (SIDEC, Divulgação), as intenções de registros de preços (IRP), o cadastramento dos fornecedores (SICAF), a realização das licitações (Compras governamentais, Sessão Pública, RDC), o resultado das licitações (SISPP, SISRP), os empenhos de pagamentos (SISME) e o registro e gestão dos contratos (SICON).|
*Formato* | API REST (xml, json, e csv) |
*Url*     | http://compras.dados.gov.br/docs/home.html |
*Dicas*   | Também é disponibilizada uma representação em HTML, que possibilita uma visualização através do navegador e melhora a classificação desses conteúdos nas ferramentas de busca. É possível filtrar sua busca por municípios, no caso de Manaus o código é do município é 2550 (ex: http://compras.dados.gov.br/fornecedores/doc/municipio/2550)
*Projetos usando* |  |

---

### Nuvem Cívica
?    | ! |
 --- | --|
*O que é* | API de acesso para diversas fontes de dados abertos governamentais.|
*Formato* | API REST (json) |
*Url*     | https://github.com/AppCivicoPlataforma/AppCivico |
*Dicas*   | Tem informações georreferênciadas sobre escolas e estabelecimentos de saúde públicos/privados do país (coletados através do DATA SUS e INEP). Há tembém informações sobre os remédios fabricados no Brasil (ANVISA). Além disso, há API para consulta de postos do Site Nacional de Empregos (SINE)|
*Projetos usando* |  |

---

### Portal da Transparência da Prefeitura de Manaus
?    | ! |
 --- | --|
*O que é* | Trata da divulgação, em tempo real, de informações pormenorizadas sobre a execução orçamentária e financeira da Prefeitura de Manaus. Por meio da pesquisa, é possível, detalhar todos os documentos emitidos pelas unidades gestoras do Poder Executivo Municipal no decorrer da execução das suas despesas, inclusive, pela fase em que a despesa está: empenho, liquidação e pagamento.|
*Formato* | download de arquivos pdf, doc, xls e odt |
*Url*     | https://transparencia.manaus.am.gov.br/transparencia/v2/#/home |
*Dicas*   | Observe que no canto superior direito da tela encontra-se um ícone com a opção “download”. Clicando-se nesse ícone são apresentadas as opções de importação nos formatos. |
*Projetos usando* |  |

---

### Receitas e Despesas Públicas – Portal da Transparência
?    | ! |
 --- | --|
*O que é* | Transferências de recursos federais, constitucionais, legais ou voluntárias, para estados, municípios, Distrito Federal, instituições privadas com e sem fins lucrativos e ao exterior, realizados pelos órgãos e entidades da Administração Pública Federal, que executam as despesas pelo Sistema Integrado de Administração Financeira do Governo Federal (Siafi). |
*Formato* | API REST |
*Url*     | http://www.transparencia.gov.br/swagger-ui.html#/Despesas32P250blicas|
*Dicas*   | Os dados dos serviços disponibilizados na API de dados deverão ser consumidos via requisições HTTP aos serviços REST. A API está documentada com exemplos de uso em http://www.transparencia.gov.br/swagger-ui.html. Também é possível baixar os dados em formato .csv através do link http://www.portaltransparencia.gov.br/download-de-dados |
*Projetos usando* | Para onde foi o meu dinheiro? |

---

### Sanções – Portal da Transparência
?    | ! |
 --- | --|
*O que é* | No Portal da Transparência, sanções são punições aplicadas a pessoas físicas, pessoas jurídicas e servidores públicos federais, decorrentes da relação com o Poder Executivo Federal, como: Cadastro de Empresas Inidôneas e Suspensas (CEIS) – Empresas e pessoas físicas impedidas de participar de licitações ou de celebrar contratos com a Administração, em todas as esferas e nos três Poderes; Cadastro Nacional de Empresas Punidas (CNEP) – Empresas que sofreram punições previstas na Lei nº 12.846/2013; Entidades Privadas Sem Fins Lucrativos Impedidas (CEPIM) – Entidades privadas sem fins lucrativos que estão impedidas de celebrar convênios, contratos de repasse ou termos de parceria com a Administração Pública; Expulsões da Administração Federal (CEAF) – Servidores civis do Poder Executivo Federal e da Câmara dos Deputados punidos com demissão, destituição ou cassação de aposentadoria. |
*Formato* | API REST |
*Url*     | http://www.portaltransparencia.gov.br/sancoes |
*Dicas*   | Os dados dos serviços disponibilizados na API de dados deverão ser consumidos via requisições HTTP aos serviços REST. A API está documentada com exemplos de uso em http://www.transparencia.gov.br/swagger-ui.html. Também é possível baixar os dados em formato .csv através do link http://www.portaltransparencia.gov.br/download-de-dados |
*Projetos usando* |  |

---

### Servidores Civis e Militares do Executivo Federal – Portal da Transparência
?    | ! |
 --- | --|
*O que é* | Informações sobre cargo, função, situação funcional e remuneração dos servidores civis e militares, bem como dos agentes públicos do Poder Executivo Federal. |
*Formato* | API REST |
*Url*     | http://www.transparencia.gov.br/swagger-ui.html#/Servidores32do32Poder32Executivo32Federal |
*Dicas*   | Os dados dos serviços disponibilizados na API de dados deverão ser consumidos via requisições HTTP aos serviços REST. A API está documentada com exemplos de uso em http://www.transparencia.gov.br/swagger-ui.html. Também é possível baixar os dados em formato .csv através do link http://www.portaltransparencia.gov.br/download-de-dados |
*Projetos usando* |  |

---

### Dirigentes de Empresas – Portal da Transparência
?    | ! |
 --- | --|
*O que é* | Informações sobre ocupantes de cargos de gerência e direção em empresas estatais e subsidiárias. |
*Formato* | CSV |
*Url*     | http://www.portaldatransparencia.gov.br/download-de-dados/dirigentes/201806 |
*Dicas*   |  |
*Projetos usando* |  |

---

### Programas Sociais Bolsa Família – Portal da Transparência
?    | ! |
 --- | --|
*O que é* | Informações sobre as transferências de recursos federais diretamente repassados a cidadãos, referentes ao pagamento do Bolsa Família, realizadas pelo Ministério do Desenvolvimento Social, por meio da Caixa Econômica Federal. |
*Formato* | API REST |
*Url*     | http://www.transparencia.gov.br/swagger-ui.html#/Bolsa32Fam237lia |
*Dicas*   | Os dados dos serviços disponibilizados na API de dados deverão ser consumidos via requisições HTTP aos serviços REST. A API está documentada com exemplos de uso em http://www.transparencia.gov.br/swagger-ui.html. Também é possível baixar os dados em formato .csv através do link http://www.portaltransparencia.gov.br/download-de-dados |
*Projetos usando* |  |

---

### Cartões de Pagamento – Portal da Transparência
?    | ! |
 --- | --|
*O que é* | Conheça os gastos realizados por meio de cartões de pagamento. O Cartão de Pagamento do Governo Federal é utilizado para despesas de pequeno vulto ou despesas eventuais que exijam pronto pagamento. O Cartão de Compras Centralizadas é utilizado para aquisição de passagens aéreas e o  da Defesa Civil para ações de socorro, assistência às vítimas e restabelecimento de serviços essenciais. |
*Formato* | API REST |
*Url*     | http://www.transparencia.gov.br/swagger-ui.html#/Gastos32por32meio32de32cart227o32de32pagamento |
*Dicas*   | Os dados dos serviços disponibilizados na API de dados deverão ser consumidos via requisições HTTP aos serviços REST. A API está documentada com exemplos de uso em http://www.transparencia.gov.br/swagger-ui.html. Também é possível baixar os dados em formato .csv através do link http://www.portaltransparencia.gov.br/download-de-dados |
*Projetos usando* |  |

---

### Seguro Defeso – Portal da Transparência
?    | ! |
 --- | --|
*O que é* | O seguro-desemprego do pescador artesanal é uma assistência financeira temporária concedida aos pescadores profissionais artesanais que, durante o período de defeso (aquele em que os animais protegidos normalmente se reproduzem), são obrigados a paralisar a atividade para preservação da espécie e sustentabilidade da atividade pesqueira na região. Para ter direito, o trabalhador deve comprovar que exerce a pesca, do pescado protegido, de maneira ininterrupta, seja sozinho ou em regime de economia familiar. |
*Formato* | API REST |
*Url*     | hhttp://www.transparencia.gov.br/swagger-ui.html#/Seguro32Defeso |
*Dicas*   | Os dados dos serviços disponibilizados na API de dados deverão ser consumidos via requisições HTTP aos serviços REST. A API está documentada com exemplos de uso em http://www.transparencia.gov.br/swagger-ui.html. Também é possível baixar os dados em formato .csv através do link http://www.portaltransparencia.gov.br/download-de-dados |
*Projetos usando* |  |

---

### Pedidos e Respostas do e-SIC
?    | ! |
 --- | --|
*O que é* | Base de dados dos pedidos e respostas realizados no Poder Executivo Federal, por meio do e-SIC, com base na Lei de Acesso à Informação.|
*Formato* | CSV e XML |
*Url*     | http://www.consultaesic.cgu.gov.br/busca/_layouts/15/DownloadPedidos/DownloadDados.aspx |
*Dicas*   | O arquivo Pedidos contém dados sobre as solicitações, incluindo o conteúdo dos pedidos e respostas. Já o arquivo Recursos fornece o conteúdo, dentre outros dados, dos recursos apresentados pelo solicitante quando ele entende que não foram concedidas a informação ou o motivo para a negativa. O arquivo solicitante fornece informações individualizadas, exceto nome, sobre os autores dos pedidos. Atualização diária |
*Projetos usando* | Achados e Pedidos |

---

### Webservice do e-OUV
?    | ! |
 --- | --|
*O que é* |Webservice para registro e consulta de manifestações de ouvidoria (denúncias, reclamações, sugestões etc.) direcionadas às ouvidorias do governo federal, incluindo a Ouvidoria-Geral da União da CGU.|
*Formato* | |
*Url*     | [Neste link](etc/e-ouv---documentacao-webservices.docx) |
*Dicas*   |O documento disponível no link acima explica como acessar os serviços e conectar seu aplicativo ao e-OUV. Por meio do serviço, um aplicativo para detectar irregularidades em obras federais pode, por exemplo, registrar diretamente uma denúncia para a CGU. Importante: o e-OUV permite o registro apenas de manifestações para órgãos do Poder Executivo Federal. Assim, se a obra ou serviço for realizado apenas com recursos estaduais, por exemplo, a denúncia deve ser encaminhada a órgãos estaduais como ouvidoria do Governo do Estado, Tribunal de Contas ou Ministério Público estadual.|
*Projetos usando* | Reclame Aqui |

---

### Relatórios da CGU
?    | ! |
 --- | --|
*O que é* | Relatórios de fiscalização em estados e municípios, auditorias anuais de contas de órgãos federais, avaliações de programas federais, entre outros. |
*Formato* |PDF |
*Url*     | http://auditoria.cgu.gov.br/public/relatorio/consultar.jsf?windowId=9db |
*Dicas*   |É possível baixar um ou mais arquivos ou exportar a lista de resultados em formato csv. |
*Projetos usando* | |

---

### Dados sistematizados sobre parlamentares, seus gastos, parentes, empresas onde eles gastaram e discursos
?    | ! |
 --- | --|
*O que é* | Dados da câmara e de outras fontes, incluindo geolocalização das empresas onde parlamentares gastaram, seus parentes, seus assessores e mais coisa que parece bem legal, sistematizado pelo pessoal da Operação Serenata de Amor  |
*Formato* | csvs compactados como xz  |
*Url*     | https://github.com/datasciencebr/serenata-toolbox/|
*Dicas*   |   |
*Projetos usando* | https://serenatadeamor.org |

---

### Projeto Brasil.IO
?    | ! |
 --- | --|
*O que é* | Projeto para tornar acessíveis os dados brasileiros de interesse público e temos como valores principais a transparência e colaboração. |
*Formato* | API REST |
*Url*     | https://brasil.io/api/datasets |
*Dicas*   | Disponibiliza aplicações especiais que cruzam dados de diversos datasets e facilitam o trabalho investigativo. |
*Projetos usando* |  |

---

## Contribuindo

Adoramos contribuições. Para adicionar um novo dado, copie o template abaixo, edite a seção e mande um pull request.

```
### Título
     ?    | ! |
      --- | --|
*O que é* |   |
*Formato* |   |
*Url*     |   |
*Dicas*   |   |
*Projetos usando* |  |
```
