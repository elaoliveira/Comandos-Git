# Comandos Git

## Configurações iniciais do Git

- [x] ``````git --version```
- [x] ```git config --global user.name "seu nome aqui"```
- [x] ```git config --global user.email "seu email aqui"```

## Comandos práticos Git

```cd (nomeDaPasta)``` - Navega/entra nas pastas

```mkdir exemplo/``` --> Cria uma pasta

```touch exemplo.txt``` --> Cria um arquivo de texto

```git init``` --> Cria um repositório/Cotainer

```git status``` --> Verifica a situação do repositório

```git add``` . --> Adiciona os arquivos da pasta no repositório

```git commit``` -m "comentario" --> Sela os arquivos 

```git log``` + (--oneline/--graph) --> Mostra todos os commits

```git branch teste``` --> Só cria uma nova branch

```git branch -M teste``` / ```git checkout -b teste``` --> Cria uma nova branch e entra na branch 

```git checkout teste``` --> Entra na branch teste

```git branch``` --> Exibe todas as branchs

### Criando um novo repositório via SSH
 - [x] No terminal, digite: ```ssh-keygen```
 - [x] Em seguida dê Enter sem preencher nada até finalizar
 - [X] Depois copie a chave ssh localizada no arquivo id_rsa.pub que foi criado
    - Copie tudo o que houver dentro do arquivo
 - [X] E acesse o seu GitHub, depois vá em Settings --> SSH and GPG Keys --> New SSH Key
 - [X] Adicione o título(geralmente coloco o nome da máquina) e cole a chave ssh em Key
 - [X] Após clique em "Add SSH Key"
 - [ ] Pronto! Agora o GitHub conversa automaticamente com sua máquina 
 
 ### Enviar repositório existente 
```git remote add origin git@github.com:MatheusMMonteiro/teste.git```
```git branch -M main```
```git push -u origin main```
 

