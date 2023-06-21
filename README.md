# Monibank

Página de cadastro completa do Monibank.

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Monibank**
| :label: Tecnologias | Javascript
| :rocket: URL         | https://monibank-topaz.vercel.app/index.html
| :fire: Desafio     | https://cursos.alura.com.br/course/javascript-validando-formularios

Formulário com validação de dados:

![image](https://github.com/matheusporezeli/Monibank/assets/112051389/0294c0e6-e533-4eaf-88cf-1894089b6a4a)


Captura de imagem:

![image](https://github.com/matheusporezeli/Monibank/assets/112051389/0a60329b-e6bd-46ed-8bc1-615510dfa756)



## Detalhes do projeto

Projeto para o cadastro de um usuário no Monibank.
Iniciamos com alguns conceitos básicos de html limitando a quantidade de caracteres em um elemento input e transformar um campo em obrigatório.</br>
Já iniciando no javascript começamos utilizando patterns e regex para selecionar elementos do html, construindo funções para cada elemento e detectando eventos do usuário.</br>
Com isso importamos funções entre arquivos e veridicamos se o CPF com números repetidos.</br>
Na parte de validações, validamos os dígitos verificadores do CPF, utilizando fórmulas matemáticas no código e também verificamos se o usuário é maior de 18 anos.</br>
Para a verificação de possíveis erros nós encontramos as validações padrões que existem no JavaScript com o Validity State, interpretamos cada tipo de erro, fizmos uma mensagem customizada para cada um, tirando o comportamento padrão do html e inserindo essas mensagens.</br>
Com os dados validados nós salvamos eles no localStorage para serem utilizados posteriormente.</br>
Para a captura da foto para o cadastro nós iniciamos a câmera no navegador, capturamos a foto com um evento de click, aplicamos um fluxo de navegação escondendo e mostrando elementos e atualizamos o localStorage para conter a foto enviada pelo usuário.

