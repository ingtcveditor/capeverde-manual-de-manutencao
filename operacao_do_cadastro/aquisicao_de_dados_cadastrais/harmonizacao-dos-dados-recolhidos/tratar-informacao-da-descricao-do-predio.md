## Tratar Informação da descrição do Prédio

### Âmbito

O tratamento da informação do prédio visa a obtenção da mais verídica descrição cadastral do prédio em função dos dados recolhidos e dos elementos presentes na declaração e demais evidências. Também permite verificar a existência de potenciais conflitos em razão dos limites das parcelas.

### Finalidade

* Ter uma versão da proposta com uma caracterização predial satisfatória e sinalizar os potenciais conflitos.

### Intervenientes

* EE \(Qualificador\).

### Diagrama

Figura 41 - Verificar Caracterização da Parcela

### Ferramentas

* Caracterização física do prédio: Verificações topológicas da parcela;
* Caracterização física do prédio: Sinalização \(apenas\) de construções precárias;
* Tipologia de conflitos.

### Condições de partida

* Existe pelo menos uma declaração existente na parcela.

### Sequência típica dos eventos

1. O **Qualificador** começar por verificar a caracterização física da parcela
   1. Localização administrativa determinada pelo acesso principal;
   2. Configuração geográfica com utilização das “verificações topológicas”.
2. A seguir, tratar cada &lt;&lt;proposta/prédio&gt;&gt; na página de caracterização do prédio;
3. Verificar cuidadosamente se existem todos os identificadores do prédio, nomeadamente número matricial, índice de registo predial caso exista, índice de escritura pública caso exista; Verificar cuidadosamente todos os dados exigidos para a caracterização cadastral do prédio: área, tipologia, permilagem, bloco e fração no caso de propriedade horizontal, descrição no caso de área comum, finalidade do prédio;
4. Verificar os registos existentes no sistema matricial, de notariado e de registo notarial, quando existem, são consultados para validar ou completar as informações introduzidas na visita de campo;
5. No caso de situações de construções precárias, ter em atenção as ferramentas de rastreio e tratamento excecional, e sinalização dessa caracterização utilizando a flag &lt;&lt;construção precária&gt;&gt;;
6. No caso de caracterizações que indiciem um potencial conflito, sinalizar a proposta/prédio com a flag “em conflito” e anotar na respetiva página a tipologia deste conflito identificado
7. Atualizar a informação de controlo de execução da proposta clicando na opção &lt;&lt;atualizar data de proposta&gt;&gt;, de modo a se poder aferir a sua “atualidade” em função da data da declaração e de outras evidências. O sistema escreve no “log” das ações que o prédio foi atualizado para a proposta e para a parcela; caso esta funcionalidade não esteja disponível no sistema, deve ser registada fora do sistema \(registo na folha de gestão de processos\).
8. Sinalizar processos em que existe discrepância entre a declaração e proposta; caso esta funcionalidade não esteja disponível no sistema, deve ser registada fora do sistema \(registo na folha de gestão de processos\)

### Sequência excepcional

A1. Empreendimentos/complexos turísticos com parcelas que estejam em regime de propriedade horizontal

Para os empreendimentos/complexos turísticos com parcelas que estejam em regime de propriedade horizontal, é aconselhável a geração automática das fracções, trazendo a informação do registo predial mais recente

1. Associar previamente as evidências matriciais e registrais ao prédio-mãe \(fracção 0\);
2. Utilizar a funcionalidade gerar frações;
3. Para cada fração confrontar a descrição predial com a existente na documentação recebida e demais evidências e corrigir em conformidade as diferenças detectadas.

### Fluxograma

![Tratar Informação do Prédio na Proposta - New Page.jpeg](../assets/tratar_informacao_do_predio_na_prop.jpeg)

Figura 42 - Fluxograma Verificar Caracterização da Parcela

### Pós- Condições

* As eventuais correções topológicas da parcela foram executadas.
* Cada proposta da parcela foi analisada e atualizada com os dados do prédio e identificados os conflitos em razão dos limites da parcela.
* Existe registo dos processos que contêm discrepâncias entre as informações da declaração de titularidade e da proposta.



