## Emitir comprovativo da visita

### Âmbito

Este procedimento visa entregar a um titular cadastral um comprovativo em que foi feita uma visita ao terreno.

Pode haver duas maneiras de o fazer: via impressão de um comprovativo do sistema, ou por preenchimento manual de um pequeno formulário caso haja algum problema com o sistema de impressão.

Esse comprovativo tem como objetivo servir de _token_ entre o visitado e a EE, em contactos posteriores telefónicos, presenciais, via internet e ainda no processo de consulta pública, mas acima de tudo para transmitir ao declarante/visitado segurança e transparência do processo.

Caso esta funcionalidade não esteja disponível no sistema, deve ser adotado uma alternativa fora do sistema \(por exemplo entrega de cartão onde consta o número do polígono e do processo\).

### Finalidade

Emitir um comprovativo da visita ao terreno ao titular cadastral.

### Interveniente

Inquiridor \(EE\);

Titular cadastral.

### Diagrama

Figura 37 - Emitir Comprovativo da visita

### Sequência típica

1. O **inquiridor** seleciona no sistema a &lt;&lt;proposta/prédio&gt;&gt; em causa, utilizando os mecanismos de seleção e pesquisa existentes no sistema e escolher a operação &lt;&lt;comprovativo&gt;&gt;;
2. O **inquiridor** seleciona preenche dados de contacto caso não haja pelo menos um registado \(SMS, correio eletrónico\);
3. O **inquiridor** escolhe a opção de “imprimir”;
4. O **sistema** imprime o recibo para uma impressora \(de preferência de etiquetas\) o comprovativo da visita
5. O sistema envia:
   1. Uma notificação por SMS com o nº da proposta/visita;
   2. Um correio eletrónico com todo o conteúdo relevante.
6. O **inquiridor** explica ao titular cadastral como utilizar o recibo emitido, nomeadamente no processo de consulta pública.

### Fluxograma

Figura 38 - Fluxograma Emitir Comprovativo

### Outras sequências

A1. O equipamento de impressão não funciona

O inquiridor preenche a ficha de visita com o nº da visita/proposta, data e hora.

