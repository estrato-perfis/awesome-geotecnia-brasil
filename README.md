# awesome-geotecnia-brasil

Lista curada, em português, de recursos **livres e públicos** para quem trabalha com geotecnia, hidrogeologia, geologia e meio ambiente no Brasil: dados abertos, software livre, normas (só o nome e o número, com link para o catálogo oficial) e material de ensino aberto.

> Links conferidos em 14/11/2026. Páginas de governo saem do ar ou mudam de endereço: se um link falhar, abra uma _issue_. Apoio de consulta: nada aqui substitui a norma técnica nem o responsável técnico.

## Índice

- [Dados públicos](#dados-públicos)
- [Coordenadas e geodésia](#coordenadas-e-geodésia)
- [Software livre](#software-livre)
- [Normas técnicas](#normas-técnicas)
- [Ensino e pesquisa abertos](#ensino-e-pesquisa-abertos)
- [Do Estrato Perfis](#do-estrato-perfis)

## Dados públicos

- [Serviço Geológico do Brasil (SGB)](https://www.sgb.gov.br/): portal do órgão, com acesso aos produtos e às bases de geologia, hidrologia e hidrogeologia.
- [RIGeo, repositório institucional do SGB](https://rigeo.sgb.gov.br/): relatórios, mapas e artigos técnicos do Serviço Geológico para baixar.
- [Portal INDE](https://inde.gov.br/): reúne em um só lugar dados geoespaciais de órgãos do governo federal.
- [CETESB, áreas contaminadas](https://www.cetesb.sp.gov.br/cetesb/qualidade_ambiental/areas_contaminadas): página da agência ambiental paulista sobre o gerenciamento de áreas contaminadas, com os procedimentos em vigor e o cadastro do estado.
- [ANA, dados abertos](https://www.gov.br/ana/pt-br/acesso-a-informacao/dados-abertos): porta de entrada para os dados da Agência Nacional de Águas e Saneamento Básico.
- [HidroWeb (ANA)](https://www.snirh.gov.br/hidroweb/apresentacao): acervo de dados hidrológicos da rede nacional (chuva, vazão, níveis).
- [IBGE, arquivos geocientíficos](https://geoftp.ibge.gov.br/): diretório de downloads públicos do IBGE: cartas e mapas, informações ambientais, nomes geográficos e recortes territoriais.
- [Embrapa Solos](https://www.embrapa.br/solos): pesquisa e material sobre solos e sua classificação no Brasil.
- [MapBiomas](https://brasil.mapbiomas.org/): mapas anuais de cobertura e uso da terra, úteis para contextualizar uma área de estudo.
- [TerraBrasilis (INPE)](https://terrabrasilis.dpi.inpe.br/): plataforma de dados geográficos de monitoramento da vegetação nativa (PRODES e DETER).

## Coordenadas e geodésia

- [IBGE, posicionamento geodésico](https://geoftp.ibge.gov.br/informacoes_sobre_posicionamento_geodesico/): pastas com a rede de referência (RBMC, redes altimétrica, gravimétrica e planialtimétrica), os serviços de posicionamento e o material do SIRGAS.
- [PROJ](https://proj.org/): biblioteca livre de transformação de coordenadas, base de quase todo software de geoprocessamento.
- [pyproj](https://pyproj4.github.io/pyproj/stable/): interface Python para o PROJ, para converter entre SIRGAS 2000, UTM e latitude/longitude.

## Software livre

- [QGIS](https://qgis.org/): sistema de informação geográfica livre, com mapas, análise e edição de dados.
- [Documentação do QGIS em português](https://docs.qgis.org/latest/pt_BR/docs/): manuais de usuário, de treinamento e de desenvolvimento.
- [Repositório de plugins do QGIS](https://plugins.qgis.org/): complementos para o QGIS, de código aberto.
- [GDAL](https://gdal.org/): biblioteca e utilitários de linha de comando para ler, converter e processar dados raster e vetoriais.
- [GeoPandas](https://geopandas.org/): tabelas com geometria em Python, para trabalhar com pontos de furos e poços.
- [Shapely](https://shapely.readthedocs.io/): operações geométricas planas em Python (distâncias, polígonos, interseções).
- [ezdxf](https://ezdxf.readthedocs.io/): biblioteca Python (licença MIT) para criar e ler arquivos DXF.
- [FloPy](https://github.com/modflowpy/flopy): pacote Python, em domínio público, para montar e rodar modelos de água subterrânea com o MODFLOW.
- [MODFLOW e programas relacionados (USGS)](https://www.usgs.gov/mission-areas/water-resources/science/modflow-and-related-programs): o modelo de água subterrânea do Serviço Geológico dos EUA, com versões e ferramentas.

## Normas técnicas

Normas são vendidas pela ABNT. Aqui entram **só o nome e o número**, para você achar a edição vigente no catálogo oficial: [ABNT Catálogo](https://www.abntcatalogo.com.br/) (busque pelo número). Nenhum texto de norma está neste repositório.

- NBR 6484: sondagem de simples reconhecimento com SPT (edição de 2020).
- NBR 8036: programação de sondagens de simples reconhecimento dos solos para fundações de edifícios.
- NBR 15495-1: poços de monitoramento de águas subterrâneas em aquíferos granulares, parte 1 (projeto e construção).

## Ensino e pesquisa abertos

- [Biblioteca Digital de Teses e Dissertações da USP](https://www.teses.usp.br/): teses e dissertações em texto completo, muitas de geotecnia e geologia.
- [Geologia USP. Série Científica](https://www.revistas.usp.br/guspsc): revista de geologia de acesso aberto.
- [Portal de Livros Abertos da USP](https://livrosabertos.abcd.usp.br/): livros acadêmicos de acesso aberto (leia a licença de cada obra antes de reutilizar).
- [SciELO Brasil](https://www.scielo.br/): periódicos científicos brasileiros de acesso aberto.
- [MIT OpenCourseWare](https://ocw.mit.edu/): material de cursos do MIT, gratuito, em inglês, incluindo engenharia civil e ciências da Terra.
- [Zenodo](https://zenodo.org/): repositório aberto onde dados e códigos recebem DOI e podem ser citados.

## Do Estrato Perfis

Ferramentas e material gratuitos do [Estrato Perfis](https://estratoperfis.com.br). As calculadoras funcionam no navegador, sem cadastro.

- [Ferramentas gratuitas](https://estratoperfis.com.br/ferramentas): o conjunto de calculadoras.
  - [Número de sondagens (NBR 8036)](https://estratoperfis.com.br/ferramentas/numero-de-sondagens-nbr-8036): quantos furos programar para uma área.
  - [Classificação por N<sub>SPT</sub> (NBR 6484)](https://estratoperfis.com.br/ferramentas/classificacao-nspt-nbr-6484): compacidade e consistência pelo N<sub>SPT</sub>.
  - [Pré-filtro e selo de poço de monitoramento](https://estratoperfis.com.br/ferramentas/pre-filtro-e-selo-poco-de-monitoramento): volumes e sacos de material de um poço.
  - [Volume de purga](https://estratoperfis.com.br/ferramentas/volume-de-purga-poco-de-monitoramento): quanto purgar antes de coletar.
  - [Gradiente hidráulico e velocidade de fluxo](https://estratoperfis.com.br/ferramentas/gradiente-hidraulico-e-velocidade-de-fluxo): a partir de três poços.
  - [Cota de camadas e nível d'água](https://estratoperfis.com.br/ferramentas/cota-de-camadas-e-nivel-dagua): da profundidade à cota.
  - [Conversor UTM SIRGAS 2000](https://estratoperfis.com.br/ferramentas/conversor-utm-sirgas-2000): UTM e latitude/longitude.
  - [RQD e IQR de sondagem rotativa](https://estratoperfis.com.br/ferramentas/rqd-e-iqr-sondagem-rotativa): qualidade do maciço rochoso.
  - [Folha de campo de sondagem SPT e planilha](https://estratoperfis.com.br/ferramentas/folha-de-campo-sondagem-spt-e-planilha): folha para imprimir e planilha.
- Guias:
  - [Como ler um boletim de sondagem SPT](https://estratoperfis.com.br/guias/como-ler-boletim-sondagem-spt)
  - [Poço de monitoramento e piezômetro](https://estratoperfis.com.br/guias/poco-de-monitoramento-e-piezometro)
  - [Como ler uma seção geológica](https://estratoperfis.com.br/guias/como-ler-secao-geologica)
  - [Como fazer um mapa potenciométrico](https://estratoperfis.com.br/guias/como-fazer-mapa-potenciometrico)
  - [NBR 6484: o que mudou de 2001 para 2020](https://estratoperfis.com.br/guias/nbr-6484-2001-e-2020-o-que-mudou)
- [Glossário](https://estratoperfis.com.br/glossario): termos de geotecnia, hidrogeologia e meio ambiente.
- [Material didático](https://estratoperfis.com.br/material-didatico): para professores e estudantes.
- [geotecnia-br](https://github.com/estrato-perfis/geotecnia-br): biblioteca pequena, em Python e JavaScript (MIT): classificação por N<sub>SPT</sub>, UTM SIRGAS 2000, carga hidráulica, volumes de poço e número de sondagens.
- [qgis-estrato-furos](https://github.com/estrato-perfis/qgis-estrato-furos): plugin do QGIS que carrega furos e poços de um CSV em UTM SIRGAS 2000 e calcula carga e gradiente (GPL-2.0-or-later).
- [Dados fictícios de sondagens SPT e poços de monitoramento, para ensino](https://doi.org/10.5281/zenodo.24249026): conjunto aberto (CC BY 4.0) com furos SPT, camadas e poços em duas campanhas, todos inventados, para aula e testes.
- Dados fictícios para ensino (furos SPT e poços, CC BY 4.0): no Zenodo, com DOI, depois da publicação. O link entra aqui quando existir.

## Contribuir e licença

Veja [`CONTRIBUTING.md`](CONTRIBUTING.md). Esta lista está sob [CC0 1.0](LICENSE): use como quiser.
