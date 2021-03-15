<img alt="Ignite" src="https://i.imgur.com/ln04ndh.png" />

<h1 align="center">Ignite: Desafio 01 - Conceitos ReactJS</h1>

## :rocket: Sobre o desafio

Nesse desafio, criamos uma aplicação de gestão de tarefas.

## Aplicação

<img alt="Alicação" src="https://i.imgur.com/wRYsfqi.png" />

## Funcionalidades da aplicação

- Adicionar uma nova tarefa

- Remover uma tarefa

- Marcar e desmarcar uma tarefa como concluída

## Testes da alicação

- `should be able to add a task`
Para que esse teste passe, você deve permitir que task seja criada e com isso, exibida em tela. As taks criadas devem conter os atributos seguindo o 
padrão da interface, que é:
```
interface Task {
  id: number;
  title: string;
  isComplete: boolean;
}
```

- `should not be able to add a task with an empty title`
Para que esse teste passe, antes de criar uma nova task, você deve validar se algo foi digitado no input e não permitir a criação da task caso o
valor seja vazio, caso o valor digitado seja vazio, você deve impedir a criação da task.

- `should be able to remove a task`
Para que esse teste passe, você deve permitir que ao clicar no botão com ícone de uma lixeira, a task relacionada a esse botão seja removida do 
estado da aplicação, consequentemente sendo removida da tela.

- `should be able to check a task`
Para que esse teste passe, você deve permitir que ao clicar no checkbox ao lado da task, ela seja marcada como concluída ou não concluída de acordo 
com seu estado atual, alterando seu valor de isComplete de false para true ou ao contrário, de true para false.

## :memo: Licença

Esse projeto está sob a licença MIT. Veja a página [LICENSE](https://opensource.org/licenses/MIT) para mais detalhes.

---
