## COMANDOS BÁSICOS DO GIT


• **Clonar um código já existente**
  ```bash
  git clone https://github.com/usuario/repositório.git
  ```  
• **Criar um diretório**  
  ```bash
  mkdir nome_diretorio
  ```  

• **Entra na pasta**
 ```bash
 CD "NOME DA PASTA"
``` 
• **Retorna um nível na pasta**
 ```bash
 CD ..
 ```
• **Cria repositório local**
 ```bash
 git init
 ```
• **Ver as configurações do repositório**
 ```bash
 CAT CONFIG
 ```
• **Adiciona repositório local ao remoto**
 ```bash
 git remote add origin URL
 ```
• **Entra na pasta e mostra o arquivo GIT**
 ```bash
 cd "NOME DA PASTA"
 ```
• **Verifica se o repositório está atualizado com o remoto**
 ```bash
 git remote -v
 ```
• **Vê o status da nossa área de preparação ou árvore de preparação**
 ```bash
 git status
 ```
• **Cria o arquivo Read.me**
 ```bash
 touch Read.me
```
• **Insere todos os arquivos da pasta no commit**
 ```bash
 git add .
```

• **Insere o documento especificado no commit**
```bash
git add "NOME DO ARQUIVO"
```

•  **Insere a mensagem no commit**
 ```bash
 GIT COMMIT -M "mensagem para subir no commit"
 ```


•  **Mostra o status do commit**
 ```bash
 git log 
```

• **Sai do projeto caso iniciarmos o init na pasta incorreta**
 ```bash
 rm -rf .git
 ```

•  **Restaura o último estado do arquivo**
```bash
git restore "NOME DO ARQUIVO" 
```

• **Edita a mensagem do último commit**
 ```bash
 git commit --amend
 ```

•  **Restaura estado do commit**
 ```bash
 GIT RESET --* + CÓDIGO DO COMMIT (hash OBTIDO NO GIT LOG )
 

    • *SOFT -> Pega os arquivos que estavam posteriores ao último commit informado;

    • *MIXED (vem por padrão) -> Adiciona os arquivos na árvore de trabalho como untracked files;

    • *HARD - Ignora os arquivos contidos na último commit (apaga os arquivos que estavam na pasta, restaura para o estado anterior)
```

• **Mostra o status detalhado dos commits**
 ```bash
  git reflog
 ```

• **Exclui um arquivo da pasta**
 ```bash
 git rm "NOME DO ARQUIVO"
```

• **Exclui uma pasta inteira**
 ```bash
 git rm -r "NOME DA PASTA"
```

• **Faz o upload do diretório do local fisico para o remoto**
 ```bash
 git push -u origin main
```

• **Puxa as alterações feitas online para o reposositorio local mesclando as alteracoes**
 ```bash
 git pull
```

• 🦉 PRIMEIROS PASSOS



 1. Cria o repositório no GitHub

 2. Conecta o repositório com git init

 3. Adiciona todos os arquivos necessários para o commit

 4. Verifica com git status

 5. Faz o commit

 6. Faz o Git push


 • 👾 BRANCHS

 Branchs são novos ramos dos projetos que criamos, caso criarmos uma nova branch e depois novos commits, estes reportarão à nova branch.

 •  **Cria uma nova branch**
  ```bash
  git checkout -b "nome"
  ```

 •  **Cria um arquivo txt com o texto informado no #**
  ```bash
  echo "#TEXTO-1" > TEXTO-1
  ```

 • **Retorna para o nome da branch informada**
   ```bash
   git checkout "nome da branch"
   ``` 

 • **Mostra os últimos commits de cada branch**
  ```bash
  git branch -v
  ```

 • **Mostra todas as branchs de um projeto**
  ```bash
  git branch
  ```

 • **Exclui a branch citada**
  ```bash
  git branch -D "nome da branch"
  ```  

 • **Mescla as alterações de branchs**
  ```bash
  git merge "nome da branch"
````

• **Baixa as alterações na brench remota sem mesclar**
 ```bash
 git fetch origin main
````

• **Compara as diferenças entre as branchs main e a origun/main**
 ```bash
 git diff main origin/main
````
 
• GIT MERGE ORIGIN/MAIN -> **Mescla as alterações**
 ```bash
 git merge origin/main
````
 
• **Clona apenas uma branch do repositório**
 ```bash
 git clone url --branch "NOME DA BRANCH" --single-branch
````

• **Volta arquivos deletados/modificados em um local arquivado para uso poterior, importante que eles ficam ocultos nos commits**
 ```bash
 git stash
````
• **Lista os arquivos que estão arquivados**
  ```bash
  git stash list
  ````

• **Exclui os arquivos que estavam arquivados**
 ```bash
 git stash pop
````

• **Mantém os arquivos arquivados para uso posterior**
 ```bash
 git stash apply
````

• 📊 CRIANDO UMA TABELA



| Coluna 1 | Coluna 2 | Coluna 3 |

|-------| ----- | ------- |

| Informações 1 | Informações 2 | Informações 3 |

| Informações 4 | Informações 5 | Informações 6 |


• 👨🏼‍💻 Criando um espaço para código

Para inserir um espaço para código escreva usando acento grave " ` ". Como no exemplo abaixo:

````

Insira aqui sua linha de código

````