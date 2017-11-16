## Tratar Eventos com Impacto no Cadastro

### Âmbito

As &lt;&lt;propostas/prédios&gt;&gt; estão a ser tratadas com harmonização dos dados que vieram da visita de campo, das declarações de titularidade, das evidências e documentos de prova apresentados, da perspetiva de haver ou não restrições de natureza ambiental ou outra sobre o prédio, se há ou não indícios de conflitos.

Todavia, seja em situações normais ou excecionais como é o caso da realização do cadastro, deve-se ter também em atenção os eventos que possam estar a ocorrer nos serviços e que podem alterar a decisão de uma caracterização provisória a favor do cadastro ou do cadastro diferido.

Assim, deve-se por um lado procurar nos sistemas envolvidos no processo de clarificação dos direitos se existem pedidos em curso ou já qualificados que possam alterar completamente a caracterização refletida na proposta, sinalizando e associando pedidos existentes na matriz, no cartório notarial e no registo predial ao prédio, de modo a dar maior confiança aos titulares e atores no processo de cadastro; por outro, deve-se alterar a &lt;&lt;proposta/prédio&gt;&gt; sempre que seja informada a alteração da sua situação legal por qualquer das entidades envolvidas no registo.

Este procedimento que deve ser feito periodicamente e sempre que necessário visa sinalizar os prédios com transações em curso no período do cadastro.

### Finalidade

* Associar ao prédio, evidências de pedidos em curso na Câmara Municipal, Cartório Notarial ou Registo Predial.

### Interveniente

* EE \(Qualificador\).

### Diagrama

Figura 47 - Tratar Eventos com Impacto no cadastro

### Condições de partida

* Existe acesso do BackOffice aos sistemas matriciais, registo predial e escritura pública.

### Sequência típica

1. Consultar os eventos que ocorreram; \(Com recurso à base de dados\);
2. Harmonizar as alterações para os processos que ainda não tenham sido enviados para consulta pública;
3. Adequar os pareceres em conformidade;
4. Atualizar os dados dos eventos, sinalizando o seu tratamento; funcionalidade não disponível, utilizar _log_ file de controlo de eventos para o efeito.

### Pós-Condições

* Os prédios com alterações introduzidas em período de operação de cadastro são sinalizadas no sistema.



