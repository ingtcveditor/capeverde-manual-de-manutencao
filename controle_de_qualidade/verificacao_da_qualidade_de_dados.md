## Verificação da Qualidade de Dados {#verifica-o-da-qualidade-de-dados}

Os parâmetros de qualidade que aqui se definem visam garantir a obtenção de dados fidedignos capazes de integrar um sistema de informação.

Os dados cadastrais não podem apresentar deficiências nos aspetos que a seguir são apresentados.

### Completude {#completude}

Tabela 15 - Omissão de dados

| Omissão de dados |   |
| --- | --- |
| Nome | Percentagem de ausência de dados |
| Elemento de qualidade dos dados | Completude |
| Sub-elemento de qualidade dos dados | Omissão |
| Medida básica da qualidade dos dados | Percentagem de dados em falta |
| Definição | Dados em falta em relação aos dados existentes, tendo por base a estrutura de dados definida. |
| Tipo de valor da qualidade dos dados | Percentagem |
| Exemplo | Marco de propriedade existente no terreno e não coordenado. |
| Valor de medida | 0% (zero por cento) para as entidades Ponto Coordenado, Estrema, Polígono Objeto Cadastro, Objeto Cadastro, Prédio, Cadastro Diferido, Construção Génese Ilegal, Titular, Representante, Declaração, Confirmação, Reclamação. |

Fonte: NTOC

Tabela 16 - Excesso de dados

| COMISSÃO |   |
| --- | --- |
| Nome | Percentagem de excesso de dados |
| Elemento de qualidade dos dados | Completude |
| Sub-elemento de qualidade dos dados | Comissão |
| Medida básica da qualidade dos dados | Percentagem de dados em excesso |
| Definição | Dados excedentes em relação aos dados existentes, tendo por base a estrutura de dados definida. |
| Tipo de valor da qualidade dos dados | Percentagem |
| Exemplo | Marco de propriedade coordenado e não existente no terreno. |
| Valor de medida | 0% (zero por cento) para as entidades Ponto Coordenado, Estrema, Polígono Objeto Cadastro, Objeto Cadastro, Prédio, Cadastro Diferido, Construção Génese Ilegal, Titular, Representante, Declaração, Confirmação, Reclamação. |

Fonte: NTOC

### Consistência topológica {#consist-ncia-topol-gica}

Tabela 17 - Sobreposição de pontos coordenados

| SOBREPOSIÇÃO |   |
| --- | --- |
| Ponto Coordenado |
| Definição: Local de coordenadas conhecidas que determina a geometria de uma ou mais estremas. |
| Nome | Sobreposição de pontos |
| Nome alternativo | Overlap |
| Elemento de qualidade dos dados | Consistência lógica |
| Sub-elemento de qualidade dos dados | Consistência topológica |
| Definição | Indicação de que não existe sobreposição topológica entre os pontos cadastrais incluídos em Ponto Coordenado, com exceção de prédios que estejam em litígio entre titulares (cadastro diferido). |
| Descrição | Nenhum dos pontos cadastrais se pode sobrepor, com exceção de prédios que estejam em litígio entre titulares (cadastro diferido). |
| Exemplo |  |

Fonte: NTOC

Tabela 18 - Sobreposição de estremas/limites

| SOBREPOSIÇÃO |   |
| --- | --- |
| Estrema/limite |
| Linha imaginária delimitadora do prédio e que é definida pelas coordenadas dos marcos de propriedade, mas que também pode estar materializada no terreno (muro, vedação, sebe, etc…). |
| Nome | Sobreposição de estremas |
| Nome alternativo | Overlap |
| Elemento de qualidade dos dados | Consistência lógica |
| Sub-elemento de qualidade dos dados | Consistência topológica |
| Definição | Indicação de que nenhuma estrema se pode sobrepor a ela própria, com exceção de prédios que estejam em litígio entre titulares (cadastro diferido). |
| Descrição | Nenhuma das estremas se pode sobrepor, com exceção de prédios que estejam em litígio entre titulares (cadastro diferido). |
| Exemplo |  |

Fonte: NTOC

Tabela 19 - Sobreposição de polígonos de objetos de cadastro

| SOBREPOSIÇÃO |   |
| --- | --- |
| Polígono Objeto Cadastro |
| Superfície no plano delimitado por estremas que constituem uma poligonal fechada que define espacialmente o objeto do cadastro |
| Nome | Sobreposição de polígonos |
| Nome alternativo | Overlap |
| Elemento de qualidade dos dados | Consistência lógica |
| Sub-elemento de qualidade dos dados | Consistência topológica |
| Definição | Indicação que nenhum dos polígonos correspondentes a objetos cadastrais se pode sobrepor, com exceção de prédios que estejam em litígio entre titulares (cadastro diferido). |
| Descrição | Nenhum dos polígonos correspondentes a objetos cadastrais se pode sobrepor, com exceção de prédios que estejam em litígio entre titulares (cadastro diferido). |

Fonte: NTOC

Tabela 20 - Lacuna entre pontos coordenados

| LACUNA |   |
| --- | --- |
| Ponto Coordenado |   |
| Nome | Lacuna entre pontos coordenados |
| Nome alternativo | Gap |
| Elemento de qualidade dos dados | Consistência lógica |
| Sub-elemento de qualidade dos dados | Consistência topológica |
| Definição | Não podem existir pontos de coordenadas conhecidas que se encontrem caracterizados como sendo do mesmo tipo e que distem menos que o EMQ definido, com exceção de prédios que estejam em litígio entre titulares (cadastro diferido). |
| Descrição | Todos os pontos coordenados e que sejam do mesmo tipo, e que distam menos que o valor definido para o EMQ são considerados como sendo um só, com exceção de prédios que estejam em litígio entre titulares (cadastro diferido). |

Fonte: NTOC

Tabela 21 - Lacuna entre polígonos de objeto de cadastro

| LACUNA |   |
| --- | --- |
| Polígono Objeto Cadastro |   |
| Nome | Sobreposição de polígonos |
| Nome alternativo | Gap |
| Elemento de qualidade dos dados | Consistência lógica |
| Sub-elemento de qualidade dos dados | Consistência topológica |
| Definição | Indicação que não podem existir lacunas entre polígonos de objetos cadastrais com exceção de prédios sem dono (cadastro diferido). |
| Descrição | Na área correspondente à operação não podem existir lacunas entre os vários tipos de polígonos de objetos cadastrais com exceção de prédios sem dono (cadastro diferido). |

Fonte: NTOC

Tabela 22 - Lacuna entre estrema e polígono de objeto de cadastro

| LACUNA |   |
| --- | --- |
| Estrema e Polígono Objeto Cadastro |   |
| Nome | Lacuna entre estrema e polígono de objeto de cadastro. |
| Nome alternativo | Gap |
| Elemento de qualidade dos dados | Consistência lógica. |
| Sub-elemento de qualidade dos dados | Consistência topológica. |
| Definição | Indicação que não podem existir lacunas entre polígonos de objetos cadastrais e estremas. |
| Descrição | Não podem existir lacunas entre os polígonos de objetos cadastrais do tipo prédio com a entidade estrema, ou seja, cada aresta de um polígono tem de coincidir com a estrema que gerou. |

Fonte: NTOC

Tabela 23 - Lacuna entre ponto coordenado e estrema I

| LACUNA |   |
| --- | --- |
| Ponto Coordenado e Estrema - I |   |
| Nome | Lacuna entre ponto coordenado e estrema. |
| Nome alternativo | Point-in-edge. |
| Elemento de qualidade dos dados | Consistência lógica. |
| Sub-elemento de qualidade dos dados | Consistência topológica. |
| Definição | Os pontos de coordenadas conhecidas que se encontram caracterizados como tipo Marco de Propriedade ou Marca de Propriedade ou Ponto de Estrema têm de coincidir com linhas que identifiquem pelo menos uma estrema. |
| Descrição | Não podem existir lacunas entre a entidade estrema com a entidade ponto coordenado do tipo marco de propriedade ou marca de propriedade ou de estrema, i.e., cada estrema tem de coincidir com o ponto coordenado que gerou. |

Fonte: NTOC

Tabela 24 - Lacuna entre ponto coordenado e estrema II

| LACUNA |   |
| --- | --- |
| Ponto Coordenado e Estrema - II |   |
| Nome | Lacuna entre estrema e ponto coordenado. |
| Nome alternativo | Point-in-edge. |
| Elemento de qualidade dos dados | Consistência lógica. |
| Sub-elemento de qualidade dos dados | Consistência topológica. |
| Definição | Indicação de que não podem existir lacunas entre estremas e pontos coordenados. |
| Descrição | Todas as estremas recolhidas ao longo da operação de cadastro têm que, em cada uma das suas extremidades, coincidir com um ponto coordenado. |

Fonte: NTOC

Tabela 25 - Lacuna entre ponto coordenado e polígono objeto de cadastro

| LACUNA |   |
| --- | --- |
| Ponto Coordenado e Polígono Objeto Cadastro |
| Nome | Lacuna entre ponto coordenado e polígono de objeto de cadastro. |
| Nome alternativo | Point-in-polygon. |
| Elemento de qualidade dos dados | Consistência lógica. |
| Sub-elemento de qualidade dos dados | Consistência topológica. |
| Definição | Os pontos de coordenadas conhecidas que se encontram caracterizados como tipo Marco de Referência têm de se encontrar no interior do polígono do objeto de cadastro do tipo prédio. |
| Descrição | Não podem existir lacunas entre os polígonos de objetos cadastrais do tipo prédio com a entidade ponto coordenado do tipo arco de Referência, visto o marco de referência não poder encontrar-se no exterior do objeto que pretende demarcar. |

Fonte: NTOC

### Consistência conceptual {#consist-ncia-conceptual}

Tabela 26 - Relação entre objeto de cadastro e Declaração de Titularidade I

| Objeto Cadastro e Declaração – I |
| --- |
| Objeto Cadastro: Entidade cadastral de natureza geral cuja existência se encontra comprovada, ou pela existência de uma porção da superfície terrestre corretamente demarcada e/ou delimitada pelas respetivas estremas, ou pela Declaração de Titularidade de propriedade, ou pela composição das duas condições em simultâneo. |
| Declaração: Documento preenchido por titular de prédio ou por seu representante mandatado para o efeito, no qual constam dados de natureza cadastral e, através do qual, se pretende legitimar a titularidade do prédio. |
| Nome | Relação entre objeto de cadastro e Declaração de Titularidade. |
| Elemento de qualidade dos dados | Consistência lógica. |
| Sub-elemento de qualidade dos dados | Consistência conceptual. |
| Definição | Cada Declaração de Titularidade não pode ser associada a mais do que um objeto de cadastro diferente. |
| Descrição | A Declaração de Titularidade caracteriza um só objeto de cadastro, o que equivale a exigir que não pode existir mais de um objeto de cadastro associado à mesma declaração. |

Fonte: NTOC

Tabela 27 - Relação entre objeto de cadastro e Declaração de Titularidade II

| Objeto Cadastro e Declaração - II |
| --- |
| Nome | Relação entre objeto de cadastro e Declaração de Titularidade. |
| Elemento de qualidade dos dados | Consistência lógica. |
| Sub-elemento de qualidade dos dados | Consistência conceptual. |
| Definição | Os objetos de cadastro tipo Prédio só são caracterizados quando associados a pelo menos uma Declaração de Titularidade. |
| Descrição | Os objetos de cadastro necessitam de ser caracterizados por pelo menos uma Declaração de Titularidade. Por definição, o único objeto de cadastro que pode não apresentar associação com uma Declaração de Titularidade é o cadastro diferido. |

Fonte: NTOC

Tabela 28 - Diferentes regimes de objeto cadastro

| Objeto Cadastro |   |
| --- | --- |
| Nome | Diferentes regimes do objeto de cadastro. |
| Elemento de qualidade dos dados | Consistência lógica. |
| Sub-elemento de qualidade dos dados | Consistência conceptual. |
| Definição | Os objetos de cadastro do tipo Prédio, que se encontrem associados a mais de uma Declaração de Titularidade, não podem apresentar um regime de objeto de cadastro diferente. |
| Descrição | Os objetos de cadastro do tipo Prédio são caracterizados, no que diz respeito ao seu regime de objeto de cadastro, de duas formas distintas: titular único ou compropriedade. A associação entre duas ou mais declarações de titularidade distintas e o mesmo objeto de cadastro têm que ser unânimes quanto ao seu regime. Caso não se confirme a unanimidade, o objeto de cadastro é do tipo Cadastro Diferido. |

Fonte: NTOC

### Posicional {#posicional}

Tabela 29 - EMQ Pontos cadastrais

| Pontos Cadastrais |
| --- |
| (1) As coordenadas dos pontos cadastrais têm que apresentar um EMQ inferior ou igual a 40 (quarenta) centímetros nas áreas urbanas e 70 (setenta) centímetros nas áreas rústicas. |

Fonte: NTOC

### Metadados {#metadados}

Os dados cadastrais têm de respeitar o perfil de _metadados_ caracterizadores da informação estabelecidos para o Sistema de Informação Territorial de Cabo Verde (SIT-CV).

Assim, assumem uma natureza obrigatória os seguintes _metadados_:

*   Referenciação cartográfica;
*   Exatidão e Precisão;
*   Conteúdo;
*   Estrutura da informação;
*   Enquadramento geográfico;
*   Título da informação;
*   Data de referência da informação;
*   Idioma da informação;
*   Designação do domínio da informação;
*   Resumo descrevendo o conjunto da informação;
*   Formato de disponibilização;
*   Histórico da informação;
*   Técnico responsável pelos _metadados_;
*   Data da elaboração dos _metadados_;
*   Proprietário da informação;
*   Produtor da informação.

Os demais _metadados_ têm natureza facultativa.