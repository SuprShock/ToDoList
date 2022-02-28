 <h2>Projeto de lista com checagem </h2>
 
---------------------------------------------------------------------
 
<p>O programa consiste em desenvolvimento de uma SPA, para To Do List, com templete <a href="https://github.com/rocketseat-education/ignite-template-reactjs-conceitos-do-react" target="_blank"> pré-definido</a> e criar as funcionalidades de:</p>
<ul><li>handleCreateNewTask</li><li>handleToggleTaskCompletion</li><li>handleRemoveTask</li></ul>
<p>Todas as funcionalidades foram aplicadas no arquivo <a href='https://github.com/SuprShock/ToDoList/blob/main/src/components/TaskList.tsx' target="_blank">TaskList.Tsx</a>, disponivel na pasta components</p>

<h2>Testes</h2>
<p>Os testes  aplicados envolvem validação dos componente e sua interação:</p>
<ol><li>should not be able to add a task with an empty title<p>Para que esse teste passe, antes de criar uma nova task, você deve validar se algo foi digitado no input e não permitir a criação da task caso o valor seja vazio, caso o valor digitado seja vazio, você deve impedir a criação da task.</p></li>
<li>should be able to remove a task <p>Para que esse teste passe, você deve permitir que ao clicar no botão com ícone de uma lixeira, a task relacionada a esse botão seja removida do estado da aplicação, consequentemente sendo removida da tela.</p></li>
<li>should be able to check a task<p>Para que esse teste passe, você deve permitir que ao clicar no checkbox ao lado da task, ela seja marcada como concluída ou não concluída de acordo com seu estado atual, alterando seu valor de isComplete de false para true ou ao contrário, de true para false.
</p></li>
</ol>
