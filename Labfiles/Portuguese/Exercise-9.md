# Exercício 9: Gerar documentação utilizando o GitHub Copilot [opcional]

### Duração estimada: 10 minutos

O GitHub Copilot pode ajudar a agilizar o processo de geração de documentação para os seus projetos de software. Auxilia na geração automática de comentários de código, na criação de documentação Markdown, no fornecimento de modelos para secções comuns, na garantia de consistência gramatical e de estilo e na referência cruzada de código e documentação. Esta ferramenta pode poupar tempo e melhorar a qualidade da documentação do seu projeto, tornando-a mais acessível e fácil de utilizar.

Neste exercício, irá gerar documentação utilizando o GitHub Copilot.

>**Nota**: O GitHub Copilot irá sugerir automaticamente um corpo de função completa ou código em texto cinzento. Exemplos do que provavelmente verá neste exercício, mas a sugestão exata pode variar.

>**Nota**: Se não conseguir ver nenhuma sugestão do GitHub Copilot no VS Code, reinicie o VS Code uma vez e tente novamente.


## Objetivos do laboratório

Você poderá concluir as seguintes tarefas:

   - Tarefa 1: Gerar um arquivo README com o GitHub Copilot usando comentários
   - Tarefa 2: Enviar código do codespace para o seu repositório

### Tarefa 1: Gerar um arquivo README com o GitHub Copilot usando comentários

1. A partir do codespace na janela do VS Code Explorer, crie um novo ficheiro.

   ![](../../media/chat-code-new.png)

1. Nomeie o ficheiro como `Document.md` e prima `CTRL + I` para pedir ao GitHub Copilot para fazer algo.

   ![](../../media/ex-7-docmd.png)

1. Digite a instrução `Create a markdown document to create a virtual network in Azure Portal` **(1)** e clique em `>` ou prima `Enter` **(2)**.

   ![](../../media/ex-7-mdsearch.png)

1. O Copilot dará uma resposta e poderá revê-la **(1)**, clicar em **Accept** **(2)** e premir `CTRL + S` para guardar o ficheiro. Além disso, pode descartar a sugestão como mostra a imagem abaixo.

   ![](../../media/8thex.png)

### Tarefa 2: Envie o código para seu repositório a partir do codespace

1. Execute o comando abaixo para adicionar os arquivos:

    ```
    git add .
    ```

1. Execute o comando abaixo para confirmar os arquivos:

    ```
    git commit -m "files"
    ```

1. Execute o comando abaixo para enviar os arquivos. Copie seu e-mail de usuário do GitHub e cole-o entre aspas.

   ```
   git config --global user.email "<inject key="AzureAdUserEmail" enableCopy="true"/>"
   ```

1. Execute o comando abaixo para confirmar os arquivos, substituindo "xxxx" pelo número no e-mail.

   ```
   git config --global user.name "<inject key="GitHub User Name" enableCopy="true"/>_clabs"
   ```

1. Execute o comando abaixo para enviar todos os arquivos para o repositório:

    ```
    git push
    ```

## Resumo

Neste exercício, você gerou com sucesso um documento usando o GitHub Copilot Chat e enviou o código para seu repositório.

### Concluiu o laboratório com sucesso
