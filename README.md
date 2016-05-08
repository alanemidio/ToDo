# To Do List
###Projeto To Do List - Pós graduação de Engenharia de Software CESMAC   

Este projeto consiste em implementar uma API que gerencie uma lista de atividade para serem realizadas "To Do". Esta API deverá conter as funcionalidades (consultas a lista de atividades a serem realizadas, consultar, incluir ou excluir uma nova atividade). Cada atividade possui 2 informações o codigo e sua descrição. O projeto tambem servirá como atividades de saula de aula e avaliacao dos alunos na matéria topicos avancados de Engenharia de Software ministrada pelo professor Daniel Fireman.

## Informações da API e suas funcionalidades  
###Lista de funcionalidades
####- Listar
>Este metodo retorna a lista de todas as atividades cadastradas.  
Para acessar: [http://localhost:3890/api/todo](http://localhost:3890/api/todo)  

####- Consultar pelo Codigo
>Este metodo realisa uma consulta na lista a partir do codigo da atividade. Este código é passado como parametro para busca.  
Para acessar: [http://localhost:3890/api/todo/5](http://localhost:3890/api/todo/5)

####- Consultar pelo Nome
>Este metodo realisa uma consulta na lista a partir do nome da atividade. Este nome é passado como parametro para busca.  
Para acessar: [http://localhost:3890/api/todo?nome=Medico](http://localhost:3890/api/todo?nome=Medico)


## Implementação
Para implementar a api, sera necessario um servidor IIS com framework .Net 4.0 instalado no servidor.
O arquivo **www.rar** possui todos os arquivos necessarios para instalação, sendo necessario descompactar este aquivo em um local no servidor. No servidor IIS criar uma nova aplicação com nome ToDo e apontar o caminho sa pasta onde foi descompactado o arquivo. Depis disto basta acessar o caminho: **http://seuservidor/todo/api/todo**
  
## Informações do codigo fonte
O codigo fonte estao em dois arquivos **clToDo** e **ToDoControler** onde o arquivo clTodo é o arquivo da classe e o arquivo ToDoControler o arquivo contendo o codigo dos metodos implementados.


## Testes
Foram realizados testes e todos passaram com sucesso. 
Durante os testes foram capturadas as telas de retorno e amazenadas em imagens. Estas imagens possuem o nome Teste_xxxxxx.jpg. Onde xxxxxx refere-se ao nome da funcionalidade.
* Listar Teste_Listar.jpg
* Consultar pelo Codigo Teste_Consultar_pelo_Codigo.jpg
* Consultar pelo Nome Teste_Consultar_pelo_Nome.jpg


