# Comandos Git / GitHub



### Autenticação SSH:

1. ssh-keygen -t ed25519 -C  (Email do GitHub)

2. cd /c/Users/seu usuário /.ssh/  (navegar até a pasta)

3. ls  (mostrar arquivos na pasta)

4. cat id_ed25519.pub (chave publica gera o ssh para por no github)

5. eval $(ssh-agent s-)  (Inicia o agent)

6. ssh-add id_ed25519 (chave privada)
   
   

#### Comandos para clonar repositório



+ clone SSH e HTTPS
  
  - git clone (URL SSH)
  
  - git clone (URL HTTPS)

*Caso receba um erro alerta de "fingerprint" confirme com "yes"*

### Autenticação Token:

1. Crie um token na pagina do GitHub

2. após criar copie e cole o Token no arquivo de texto e save em pasta segura

3. Quando for solitado a autenticação copie cole

#### Comandos para clonar repositório

+ git clone (Url HTTPS)

### Comandos Gerais:

+ mkdir (Cria um pasta coamndo + o nome da mesma)

+ cd (comando + nome da pasta acessa a mesma)
  
  - cd .. (voltar ao diretório anterior)

+ git init (inicializar o git)

+ ls (mostras os arquivos do diretório)
  
  - ls -a (mostra arquivos ocultos no diretório)

+ git config --global user.email (configurar email que será registrado no commit)

+ git config --global user.name (configurar nome que será registrado no commit

+ git mv ( + nome do arquivo ) (+ nome do diretório) (exemplo ./diretório/)

### COMMITAR:

1. git add * ( . ou comando + nome do arquivo )

2. git commit -m "Texto descritivo do commit"

### STATUS GIT - SITUAÇÃO DOS COMMITS:

+ git status (Essencial para verificar o status do diretório, se foram adicionados ou commitados)

### GIT / GITHUB COMANDOS:

1. git status (verifica a situação dos commits)

2. git remote add origin (+ o enderço do github, pode ser SSH ou HTTPS)

3. git remote --v (verifica a lista de URLs do repositório remoto)

4. git push origin main  ("origin" - nome da branch dado a url remota, "main" nome da branch do repositório do github)


