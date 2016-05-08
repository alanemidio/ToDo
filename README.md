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
Os metodos implementados foram:  
  api/todo - retorna toda a lista de atividades a realizar  
  api/todo/5 - retorna item com codigo = 5  
  api/todo?nome=medico - retorna item cujo nome seja medico onde este representa uma consulta médica  
  
## Testes
Foram realizados testes e todos passaram com sucesso.

