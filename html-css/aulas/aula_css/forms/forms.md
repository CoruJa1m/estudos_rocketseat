# form 
form e um formulario que recebe informacoes e manda e tipo uma conexao de informacoes de cliente a servidor
a tag para formulario e <form>
- e um elemento que dfine um formulario
- container estilo <section> <footer>
- form  usa outros tipos de dados que os dois acima
action= manda informacoes pra algum lugar 

# fieldset
- agrupamento de campos 
- mesmo proposito
- semantica
- acessibilidade

* atributos especiais

* disabled
- desabilita todos os elementos interno
- nao serao enviados ao submeter o formulario

* form
- id do field a qual pertence
- nao precisa estar dentro do formulario

* name
- nome do grupo

<legend>
- nome do agrupamento
- primeiro elemento dentro do fieldset
-
# label
* acossiar e identificar uma ou mais dados de entrada
- atributos 
- for ,fazer a conexar entre o label e a entrada de dados
- e feita via id do input e dso funciona com algum elemento ex:button

<button>

- e um botao 

- serve para mandar dados

- e estiliozado pelo user agerte (navegador)

* ele tem algums valores que dao funcoes ex: submit(enviar) reset(resetar) dentre outros

<datalist>

* e uma lista de valores a uma tag imput que auto completa no label
- sao sugestivos e nao obrigatorios
- usuario pode selecionar um dos valores 

# list
* recebe como valor o id de um <datalist> residente no mesmo documento

* obs:sim tem que ter uma id na datalist para ter a conexao das duas
