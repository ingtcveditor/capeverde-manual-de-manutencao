## Recolher Dados da Parcela: Delimitação, Demarcação e Restrições

### Âmbito

Este procedimento visa caracterizar fisicamente a parcela de terreno e as edificações nelas contidas. Consiste no reconhecimento dos limites da parcela ou no estabelecimento e clarificação de novos limites, corrigindo ou adicionando ao sistema os vértices que delimitam o polígono correspondente à parcela.

Além disso, também pretende recolher os dados físicos cadastrais e caracterizar a tipologia das construções nelas existentes, como sejam mero terreno, construção sem ou com propriedade horizontal, número de unidades existentes na parcela e espaços comuns.

É nesta caracterização física também que se vai aferir riscos ambientais ou vulnerabilidades aplicando as respetivas ferramentas de triagem previstas para esta etapa.

Após esta caracterização física feita pelo topógrafo, será possível classificar esta parcela e perceber que abordagem ter para a clarificação dos direitos associados.

E ainda durante esta caracterização podem surgir conflitos relacionados com a precisão das delimitações entre confinantes pelo que são também ativadas as respetivas ferramentas de identificação e tipificação de potenciais conflitos.

As Câmaras Municipais ficam obrigadas a demarcar ou fornecer informações sobre os limites ou extremas dos lotes de terreno para edificação urbana ou relativamente as quais concedeu por contrato, o direito de propriedade ou outro direito real mas que, até a data da execução do cadastro predial, não tenha sido objeto de implantação física.

### Finalidade

* Delimitação e Demarcação da parcela, sua caracterização física e construções nelas contidas.

### Intervenientes

* EE \(Topógrafo\);
* Titular.

### Diagrama

Figura 28 - Caracterização física da parcela

### Fluxograma

![Recolher e Dados da Parcela e sua Demarcação.jpeg](../assets/recolher_e_dados_da_parcela_e_sua_d.jpeg)

Figura 29 - Caracterização física da parcela

### Condições de partida

* Existe pelo menos um titular ou representante;
* Existe um polígono no sistema correspondente à parcela;
* As imagens ortorectificadas estão disponíveis no equipamento;
* O sistema GNSS está operacional via RTK.

### Ferramentas

* Tipologia de Conflito
* Vulnerabilidade Social: Identificação de construção precária
* Riscos Ambientais AMB2: Identificação de terreno ou construção em área de risco

### Sequência típica do procedimento

1. O **inquiridor** começa o procedimento utilizando o _Tablet_ para selecionar no mapa o polígono correspondente à parcela e escolhe a opção &lt;&lt;visita&gt;&gt;;
2. O **inquiridor** solicita ao \(s\) **titular \(es\)** que mostre os marcos \(vértices\) e limites da parcela;
3. Na presença do **titular,** o **inquiridor** verifica e/ou corrige os vértices do polígono recorrendo ao equipamento GNSS e/ou as imagens ortorectificadas e estabelece a configuração geométrica correta da parcela;
4. Se houver necessidade, pode editar cada vértice do polígono;
5. Se houver necessidade, podem ser adicionados ou eliminados vértices;
6. Para o polígono selecionado, o inquiridor escolhe a opção “caracterização do prédio”;
7. O sistema apresenta o formulário de caracterização já com alguns dados automaticamente preenchidos:
   1. Localização administrativa;
   2. Área da parcela.
8. Preencher ou corrigir os seguintes dados de caracterização da parcela:
   1. Tipo de prédio \(lote de terreno, prédio construído ou prédio em regime de propriedade horizontal\);
   2. Número de unidades administrativas \(apenas 1 para terreno e para prédio que não esteja em propriedade horizontal\).
9. Ao gravar o registo, o sistema irá criar um registo de &lt;&lt;proposta&gt;&gt; por cada unidade administrativa em função do tipo e número de unidades administrativas indicado, se estiver em regime de propriedade horizontal o sistema criará uma &lt;&lt;proposta&gt;&gt; adicional para a propriedade horizontal;
10. Escolher a opção &lt;&lt;propostas&gt;&gt; e o sistema apresenta a lista das &lt;&lt;propostas&gt;&gt; associadas a parcela;
11. Selecionar as propostas referentes às unidades visitadas e escolher a opção “Visita”. O sistema escreve a visita \(timestamp e user\);
12. Fotografar o prédio à frente da servidão principal do prédio; a imagem deve cobrir a máxima área do terreno ou volumetria das construções;
13. Para efeitos de controlo de qualidade, marcar com tinta os pontos utilizados para o levantamento;
14. Terminar o procedimento e seguir para a caracterização física da próxima parcela.

### Sequências Excecionais

A1. Não está presente nenhum titular ou representante =&gt; Tratar ausência

1. Marcar &lt;&lt;ausência&gt;&gt; com um ponto georreferenciado num para-centróide da parcela;
2. No caso de algum testemunho de vizinho ou terceiro, registar no log da visita quem informou e o que informou;
3. Fotografar o prédio à frente da servidão principal do prédio; a imagem deve cobrir a máxima área do terreno ou volumetria das construções;
4. Terminar o procedimento.

A2. Não está presente nenhum titular ou representante mas dispõe-se de informação fornecida pela Câmara Municipal de lote transmitido pela mesma =&gt; Tratar ausência

1. Marcar &lt;&lt;delimitação com base em informação da CM&gt;&gt;;
2. Proceder com sequência típica, utilizando a Câmara Municipal em vez de titular.
3. Terminar o procedimento.

B1. Não existe ainda polígono no sistema =&gt; Criar polígono

1. Verificar o posicionamento de cada marco que delimita a parcela de terreno;
2. Criar os vértices do polígono:
   1. Caso os marcos sejam visíveis na imagem disponível no dispositivo \(_Tablet_\), adicionar os vértices do polígono utilizando a funcionalidade “desenhar”;
   2. Caso não seja possível reconhecer os marcos na imagem, capturar as coordenadas dos marcos utilizando o dispositivo GNSS e criar o respetivo polígono;
3. Prosseguir com o procedimento da sequência típica.

C1. Não existe polígono no sistema, ferramenta de rastreio e construção clandestina =&gt; Usar formulário AUGI

D5. O polígono pertence a um empreendimento/complexo turístico.

1. Tratando-se de um empreendimento turístico, é mais simples e eficaz introduzir  todos os dados em Back Office.
2. Assim, é importante garantir qual sem qualquer ambiguidade qual o número da matriz da parcela, para que depois se faça a geração do prédio ou frações em conformidade em Back Office.

### Pós Condições

* Demarcação da Parcela Finalizada;
* Propostas criadas, um por cada registo predial, no sistema e associados ao respetivo polígono \(parcela de terreno\);
* Dados cadastrais obrigatórios para a identificação física para os prédios recolhidos;
* Registo da visita para cada unidade \(prédio\).



