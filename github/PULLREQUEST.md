# Como fazer um Pull Request

1. Ao clonar ou fazer um fork de um repositório, crie uma nova branch temporária para
trabalhar nas tarefas desejadas e faça um switch para essa nova branch. 

```
# git checkout -b cria e já seleciona a nova branch para desenvolvimento.
git checkout -b minha_branch
```

2. Faça as alterações e realize os commits necessários relacionados à essas alterações.

```
git add arquivos_alterados
git commit -m "mensagem do commit"
```

3. Ao finalizar a tarefa, verifique que tudo está OK

4. Faça um push para a branch remota correspondente à sua branch local de desenvolvimento:

```
git push origin minha-branch
```

5. Se tudo estiver ok, então é hora de fazer um merge com a branch principal, para isso
é necessário criar um Pull Request no github.

- Um Pull Request só pode ser criado entre duas branches diferentes. Exemplo: branch-dev (para)-> main

- Clique no botão de pull request ou caso aparece uma mensagem "Compare and Pull Request" indicando que há a possibilidade de criar um PR, clique e você sera direcionado para a tela de criação de um pull request.

