# **_Desafio 01 - Conceitos do React_**



&nbsp;
## **_Sobre o desafio_**
Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no ReactJS.

Essa será uma aplicação onde o seu principal objetivo é uma pequena aplicação de atividades a fazer, para treinar um pouco mais sobre manipulação do estado no React.

* Adicionar uma nova tarefa
* Remover uma tarefa
* Marcar e desmarcar uma tarefa como concluída

A seguir veremos com mais detalhes o que e como precisa ser feito 🚀


&nbsp;
## **_Template da aplicação_**
Para te ajudar nesse desafio, criamos para você esse modelo que você deve utilizar como um template do GitHub.

O template está disponível na seguinte URL:<br>
[Ignite template](https://github.com/rocketseat-education/ignite-template-reactjs-conceitos-do-react)


&nbsp;
## **_O que devo editar na aplicação?_**
Com o template já clonado, as depêndencias instaladas, você deve completar onde não possui código com o código para atingir os objetivos de cada teste. Nesse desafio, você deve editar apenas o seguinte arquivo para completar as funcionalidades da aplicação:
`src/components/TaskList.tsx;`

### **_components/TaskList.tsx_**
Esse é o componente responsável por todas as funcionalidades da aplicação, é um componente simples, mas onde botaremos em prática várias partes da manipulação do estado.

Você deve criar as funcionalidades para as três funções presentes nesse arquivo, que são:

* **_handleCreateNewTask_**: Deve ser possível adicionar uma nova task no estado de `tasks`, com os campos `id` que deve ser gerado de forma aleatória, `title` que deve ser um texto e `isComplete` que deve iniciar como false.

* **_handleToggleTaskCompletion_**: Deve alterar o status de `isComplete` para uma task com um ID específico que é recebido por parâmetro.

* **_handleRemoveTask_**: Deve receber um ID por parâmetro e remover a task que contém esse ID do estado.



&nbsp;
## **_Especificação dos testes_**
Em cada teste, tem uma breve descrição no que sua aplicação deve cumprir para que o teste passe.

Para esse desafio, temos os seguintes testes:

### **_Teste TaskList.spec.tsx_**
* **_should be able to add a task_**
Para que esse teste passe, você deve permitir que task seja criada e com isso, exibida em tela. As taks criadas devem conter os atributos seguindo o padrão da interface, que é:

```json
interface Task {
  id: number;
  title: string;
  isComplete: boolean;
}
```


* **_should not be able to add a task with an empty title_**
Para que esse teste passe, antes de criar uma nova task, você deve validar se algo foi digitado no input e não permitir a criação da task caso o valor seja vazio, caso o valor digitado seja vazio, você deve impedir a criação da task.

* **_should be able to remove a task_**
Para que esse teste passe, você deve permitir que ao clicar no botão com ícone de uma lixeira, a task relacionada a esse botão seja removida do estado da aplicação, consequentemente sendo removida da tela.

* **_should be able to check a task_**
Para que esse teste passe, você deve permitir que ao clicar no checkbox ao lado da task, ela seja marcada como concluída ou não concluída de acordo com seu estado atual, alterando seu valor de `isComplete` de `false` para `true` ou ao contrário, de `true` para `false`.


&nbsp;
## **_Entrega_**
Esse desafio deve ser entregue a partir da plataforma da Rocketseat. Envie o link do repositório que você fez suas alterações. Após concluir o desafio, além de ter mandado o código para o GitHub, fazer um post no Linkedin é uma boa forma de demonstrar seus conhecimentos e esforços para evoluir na sua carreira para oportunidades futuras.



&nbsp;
## **_Prévia do projeto:_**
![prévia do projeto](https://fernandagoncalves.com.br/github/image.JPG)