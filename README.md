# ci-demo

Um pipeline simples e objetivo para um trabalho de Continuous Integration utilizando GitHub Actions.    

# 2. Objetivo da atividade

Atividade para treinamento e pratica de workflow de github actions e criação de pipeline .  
# 3. Estrutura do projeto

#Códigos utlizados no trablho

```yaml
.github/workflows/ci.yml

name: CI Example
on: [push]

jobs:
  first-job:
    runs-on: ubuntu-latest

    steps:
      - name: Print message
        run: echo "Pipeline executado com sucesso!"
```
*Expicação do código:*

### **name: CI Test**
É o nome do workflow. Esse nome aparecerá na aba Actions do GitHub.

### **on: [push]**
Indica o evento que dispara o workflow. Neste caso, sempre que houver um push no repositório.

### **jobs:**
Define os trabalhos que o workflow irá executar.

### **first-job:**
É o nome do job, ou seja, do conjunto de tarefas que será executado.

### **runs-on: ubuntu-latest**
Indica o ambiente onde o pipeline será executado. Aqui, o GitHub cria uma máquina virtual Linux
Ubuntu.

### **steps:**
Define a sequência de passos que o job vai seguir.

### **- name: Print message**
É o nome do passo. Serve para identificar visualmente o que está sendo executado.

### **run: echo "Pipeline executado com sucesso!"**
É o comando executado no passo. Neste caso, ele apenas imprime uma mensagem no terminal do
pipeline.

## Lição Aprendida
Graças aos ensinamentos da aula, tivemos uma noção de como utilizar o actions do github e tambem como documentar em markdown, tivemos orientação, correção e apoio na atividade de agora.
script.sh
README.md
