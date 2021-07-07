# Baixar o git no link https://git-scm.com/downloads
 
## No Senac usar o caminho \\10.10.132.30\Educacional\EMI para não precisar baixar da Internet
 
Abrir o Git Bash
 
```
git config --global user.name "o seu nome aqui"
git config --global user.email "seu@email.com.br"
```
 
Gerar a chave ssh
```
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
cat .ssh/id_rsa.pub
