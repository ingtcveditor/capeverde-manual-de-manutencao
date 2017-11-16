## Declaração dos Titulares

### Âmbito

A partir da publicitação da operação de cadastro, pode ter início a entrega das declarações de titularidade.

As declarações podem ser feitas e entregues em postos de atendimento publicitados, nomeadamente nos balcões da casa do cidadão, consulados, por via eletrónica utilizando sitio web publicitado no edital mas acima de tudo durante a atividade de recolha em campo. Esta preferência tem a ver com o facto de se pretender reduzir ao mínimo o número de declarações no sistema informático que não estejam associadas ao respetivo prédio, o que só pode ser feito com segurança, na atividade de terreno.

A recolha da Declaração de Titularidade pode ser feita utilizando o sistema disponibilizado via internet e via gabinete de apoio e prestação de serviços ao cidadão criada para a Operação de Cadastro.

## Declaração feita presencialmente num balcão de atendimento

### Finalidade

Preencher uma declaração no sistema, na presença do titular e imprimir cópia da declaração para entregar ao declarante

### Interveniente

Declarante/Titular Cadastral;

Atendedor;

EE em coordenação com Casa do Cidadão/Porton Di Nos Ilha/outras entidades.

### Diagrama

![](/assets/decl_tit_18.jpg)

Figura 18 - Declaração de Titularidade, presencial

### Fluxograma

![](/assets/flux_decl_tit_19.jpg)

Figura 19 - Fluxograma Declaração de Titularidade, presencial

![](/assets/decl_tit_int_20.jpg)

Figura 20 - Declaração de Titularidade via internet

### Condições de partida

* Existe conectividade ao sistema central;
* Sistema na função **Declaração de Titularidade** disponível via internet no portal previamente definido;
* Existe um polígono para a parcela sobre o qual vai haver declaração ou qualquer outra evidência.

### Sequência típica

No gabinete de apoio ao cidadão:

1. O **atendedor/inquiridor** começa o procedimento utilizando a aplicação LMITS para selecionar a parcela no mapa, sob indicação e supervisão do \(s\) declarante \(s\);
2. O atendedor escolhe a opção “ &lt;&lt;propostas/prédios&gt;&gt;”
3. O sistema apresenta uma lista de prédios \(em caso de PH podem ser muitos\) e o utilizador escolhe qual o prédio;
4. O utilizador escolha a opção &lt;Nova Declaração&gt;
5. O sistema apresenta o formulário da declaração com os atributos obrigatórios e facultativos;
6. O atendedor preenche o formulário conforme indicações do declarante;
7. O atendedor pede a confirmação dos dados e solicita assinatura no _“pad”_ digitalização de assinaturas
8. O atendedor imprime uma cópia da declaração e entrega ao Declarante.

### Sequência Excecionais

A1 - Não existe nenhum prédio associado a parcela

1. O atendedor escolhe “caracterização do prédio”,
2. O sistema apresenta o formulário com tipo de prédio e número de unidades
3. O sistema cria uma proposta por cada unidade administrativa e uma adicional para o caso de Propriedade Horizontal, todas no estado “preparação”

Continuar com a sequência típica

A2 - A declaração é de propriedade horizontal

1. Verificar se o declarante cumpre e prova os requisitos previstos na lei \(administrador/condómino\)
2. Prosseguir com a sequencia típica para o prédio em propriedade horizontal e todas as frações associadas.

## Declaraões Via Internet:

1. O declarante/titular cadastral acede via internet ao portal de serviços públicos \(portonDiNosIlha\), devidamente autenticado;
2. Acede à opção Cadastro Predial&gt; Declaração de Titularidade, em destaque durante a operação do cadastro;
3. O sistema apresenta os passos para o serviço em modo diagrama \(Com mapa, sem mapa, declaração, anexar comprovativos e impressão\);
4. O sistema apresenta o primeiro passo e pergunta se pretende visualizar e indicar no mapa o lote onde se situa o prédio, recomendando que assim seja;
5. Se escolher o mapa são apresentados os lotes com ferramentas de navegabilidade e o utilizador tem a opção de clicar no lote, ou de clicar na opção lote não encontrado;
6. O sistema apresenta o formulário do LIMTS da declaração com os atributos obrigatórios e facultativos;
7. O **declarante** preenche o formulário conforme indicações no sistema;
8. O sistema pede a confirmação dos dados e o utilizador valida ou redita;
9. A declaração é guardada no sistema e caso tenha sido selecionado um lote fica associação estabelecida entre lote e declaração;
10. O sistema solicita a anexação de documento de identificação \(cópia do bilhete de identidade ou passaporte\);
11. Terminado, o Sistema imprime uma cópia da declaração, ou cria um PDF ou ainda envia um correio eletrónico com a cópia da declaração para a conta registrada na declaração;
12. As declarações efetuadas pelo titular ficam disponíveis para posterior acompanhamento.

### Fluxograma

![](/assets/flux_decl_tit_21.jpg)

Figura 21 - Fluxograma Declaração de titularidade via Internet

### Pós- Condições

* Registada uma declaração no LIMTS-1.



