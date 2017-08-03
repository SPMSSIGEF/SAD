# CONCEITO


<a name="conceito"></a>

# 1. Conceito

Todas as despesas registadas na plataforma de Aprovação de Despesa passam pelo mesmo processo. Quando um utilizador acede ao registo de uma nova despesa e após preencher todos os campos obrigatórios, esta fica numa fase de “Inscrição”, como mostra o esquema da Figura 1.

<div class="class">
</div>

<div style="text-align:center"><img src ="https://spmssigef.github.io/pages/img/logos/img1.png" /></div>



Nesta fase, a despesa pode estar em dois estados: “Inscrita”, quando o utilizador preenche todos os campos da despesa mas guarda a informação sem a submeter, ou “Submetida” quando o utilizador, após preencher os campos obrigatórios, submete a despesa. Caso a despesa seja submetida, a situação atribuída a esta despesa é “Aguarda”.
Nesta situação, a despesa entra então numa fase de “Validação”, como pode ser observado na Figura 2, onde fica sujeita à decisão tomada pelo validador.


<div style="text-align:center"><img src ="https://spmssigef.github.io/pages/img/logos/img2.png" /></div>


Esta fase é considerada como um estado intermédio, isto é, a despesa não pode ser considerada como aprovada ou não aprovada, é aqui que o validador toma a decisão.
O validador pode visar ou não visar a despesa ou remeter novamente à entidade para revisão. No caso de o validador visar a despesa, esta fica na situação “Visar”, caso contrário, fica na situação “Não Visar”.  
Na Figura 3 pode ser observado o histórico com as validações que a despesa em questão já sofreu.


<div style="text-align:center"><img src ="https://spmssigef.github.io/pages/img/logos/img3.jpg" /></div>


Se na fase de validação, o registo de despesa não esteja em conformidade, poderá ser solicitado a sua revisão com a identificação do estado de “Rever”, sendo que, neste caso, a despesa fica novamente como “Inscrita”, uma vez que a entidade necessita de fazer alterações na informação que foi preenchida.  
Após a despesa ter sido visada pelo validador, esta entra da fase de “Aprovação”, fase esta que está representada na Figura 4, sendo que nesta fase é o aprovador que toma a decisão acerca da despesa.


<div style="text-align:center"><img src ="https://spmssigef.github.io/pages/img/logos/img4.png" /></div>


O aprovador pode visar ou não visar a despesa ou ainda, mais uma vez, colocar esta na situação “Rever” e esta volta para a fase “Validação”, uma vez que passa outra vez pela análise do validador, sendo que este retorna a despesa para a entidade rever, ficando como inscrita de modo a entidade conseguir fazer as alterações que são necessárias. Na Figura 5 pode ser observado um resumo das passagens de estados que uma despesa pode sofrer.


<div style="text-align:center"><img src ="https://spmssigef.github.io/pages/img/logos/img5.png" /></div>


<a name="conceito"></a>
