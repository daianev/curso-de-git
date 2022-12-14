## Meu Curso de Git ![Dog](https://pipz.com/static/images/blog/eddie.png)

### [Link para o meu projeto](https://github.com/daianev/curso-de-git)

### Inicializando um Projeto Rapidamente

1- Crie um novo repoditório no Git **(público ou privado)**;

2- Crie uma pasta vazia **(com o nome do projeto)**;

3- Dentro desta pasta crie um arquivo utilizando o seguinte comando:

```bash
echo "# Meu curso de Git" >> README.md
```

4- Inicialize o repositório:

```bash
git init
```  

5- Aceito as mudanças no arquivo README.md, atualizando:

```bash
git add README.md
``` 

6- Faço o commit das mudanças, utilizando:

```bash
git commit -m "iniciando o projeto"
``` 

7- Crie a branch principal, utilizando:

```bash
git branch -M main
``` 

8- Adicione a origem do repoditório remoto **(github)**:

```bash
git remote add origin https://github.com/daianev/curso-de-git.git
``` 

9- Por fim, sincronize o branch remoto **(origin)** com as informações do branch local **(main)**;


```bash
git push -u origin main
``` 