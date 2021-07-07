# hello_world
Repositório para aula de  **git** e **github**

## Obejetivos

* Aprender a clonar o repositório;
* Aprender a clonar os arquivos para trackear;
* Aprender a fazer o commit;
* Aprender a enviar as modificações para o github
* Aprender a baixar as modificações.

## Criar versão de arquivos modificados/incluídos/deletados

Comando para o git monitorar os arquivos excluídos, adicionados ou modificados para serem versionados.

```git
git add .
```

Comando para criar a versão dos arquivos, **a mensagem entre aspas deve apresentar o que foi feito!**

```git
git commit -m "uma mensagem sobre o que foi realizado"
```

Comando para enviar a versão criada para o github
```git
git push origin main
``` 
# Clonar repositório do github

```git
git clone link-do-repositório
```
Clonar com um apelido para a pasta, se o apelido tiver espaço em branco usar aspas
```git
git clone link-do-repositório apelido
```


# ver alterações no repositório
```git
git status
```