## Verificar e Recolher Dados dos Titulares

### Âmbito

Este procedimento visa obter os elementos de identificação obrigatórios titulares cadastrais que permitam o seu registo no Cadastro de forma inequívoca.

O NIF \(número de identificação fiscal\) é a chave utilizada para que um titular cadastral esteja uma única vez na base de dados, ficando assim a responsabilidade da unicidade entre o número e o titular cadastral afeta aos serviços fiscais centrais e por conseguinte fora da responsabilidade do Cadastro.

No âmbito da execução do Cadastro, poderiam ser delegadas competências para que a entidade executante possa atribuir NIF, mas prefere-se que sejam acionados os serviços fiscais ou da Casa do Cidadão, nomeadamente o serviço móvel para o efeito.

### Finalidade

* Verificar a identidade do titular e recolher dados em falta para o inscrever no sistema uma única vez

### Intervenientes

* EE-Inquiridor;
* Titular cadastral;
* Casa Cidadão.

### Diagrama

![Macintosh HD:Users:PNM:Downloads:MCA.LAND - Registar Titular - New Page \(1\).png](../assets/macintosh_hduserspnmdownloadsmc.png)

Figura 30 - Registar Titular

### Ferramentas

* Vulnerabilidade Social: ASG 1 para identificação de titular cadastral em situação de vulnerabilidade.

### Condições de partida

* Existe um ou mais titulares ou representantes;
* A base de dados de identificação fiscal \(NIF\) está disponível;
* A base de dados da identificação e registo civil estão disponíveis.

### Sequência típica

1. O **inquiridor** começa o procedimento utilizando a aplicação móvel \(Tablet\) selecionando a parcela e escolhendo a funcionalidade “Titulares”;
2. O **inquiridor,** utilizando os respetivos formulários no sistema, localiza na lista de titulares, agrupados por &lt;&lt;proposta&gt;&gt; e para cada um dos titulares do prédio em questão, verifica e valida os dados de:
   1. Tipo de Titular \(Singular ou Coletiva\);
   2. Nome ou Designação conforme o caso;
   3. Estado Civil no caso de pessoas singulares e cônjuge se aplicável;
   4. Número de Identificação Fiscal;
   5. Morada ou Sede;
   6. Dados de Contacto.
3. Para os titular envolvidos, o inquiridor faz a avaliação inicial de vulnerabilidade social ou de género aplicando a ferramenta de rastreio para este processo;
4. Se o **titular** não estiver registado no sistema utilizar a funcionalidade &lt;&lt;novo titular&gt;&gt; para o inscrever. Caso ele não tenha ainda um NIF, informá-lo da sua obrigatoriedade para a posterior conclusão do processo de cadastro e quais os balcões disponíveis para a sua obtenção;

Concluída a sua inscrição, o **inquiridor** passa para o procedimento de verificação dos direitos.

### Fluxograma

![Verificar e Recolher Dados dos Sujeitos e Titulares.jpeg](../assets/verificar_e_recolher_dados_dos_suje.jpeg)

Figura 31 - Fluxograma Registar Titular

### Sequências e casos excecionais

A1: No caso de Propriedade Horizontal, não existe nenhum titular presente para uma dada fração da parcela:

1. Selecionar na parcela “Propostas”;
2. Na lista de Propostas, selecionar o prédio ou prédios, em questão e marcar “Ausência de Titular”.

A2: O titular não possui NIF

1. Informar o titular da necessidade da sua obtenção no Balcão Móvel ou Fixo da Casa de Cidadão ou na repartição de finanças;
2. Prosseguir com a sequência típica colocando que não há NIF.

A3 - Declaração\(ões\) pertencentes a empreendimentos/complexos turísticos

1. Tratando-se de um empreendimento turístico, é mais simples e eficaz registar dados dos titulares em Back Office;
2. Deve-se recolher uma listagem em papel, ou em formato digital, de todos os prédios e fracções do empreendimento, que será posteriormente utilizada para comparação com as declarações e propostas geradas pelo sistema, via acesso direto à base de dados.

### Pós-Condições

* Os dados dos titulares que prestaram declarações anteriores foram verificados e validados no sistema;
* Dados obrigatórios para a identificação dos titulares foram obtidos.



