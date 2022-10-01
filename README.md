# **Hello-world in GitHub**
Compartilho aqui um básico sobre o GitHub com uso de branches, commits e pull requests.
Este tutorial é um exercicio prático de GitHub onde crio o repositório Hello Word e crio um fluxo de trabalho de pull request aqui no GitHub, uma prática comum de criar e revisar o código.

### **Criar um repositório** 
  Um repositório geralmente é usado para organizar um único projeto. Os repositórios podem conter pastas e arquivos, imagens, vídeos, planilhas e conjuntos de dados - tudo o que o projeto precisar. Geralmente os repositórios incluem um arquivo README, um arquivo com informações sobre o projeto. Os arquivos README são escritos na linguagem Markdwn. O GitHub permite adicionar um arquivo README ao projeto ao mesmo tempo em que criamos o repositório.
  
### **Criando um branch**
  O Branch permite que trabalhemos com diferentes versões de um repositório de uma só vez.
  Por padrão o repositório tem um branch chamado "main" que é considerado o branch definitivo. podemos criar branch adicionais com base em main no repositório. pode-se usar branches para ter diferentes versões de um projeto de uma só vez. Isso é útil quando queremos adicionar novas funcionalidades a um projeto sem alterar a principal fonte de código. O trabalho feito em diferentes branches não aparecerá no branch principal até que façamos a merge, podemos assim usar branches para fazer experimentos e edições antes de fazer commit na main.
  Quando criamos um branch com base na branch main, fazemos uma cópia assim como ele é naquele momento. Se outra pessoa fez alterações no branch enquanto estou trabalhando no meu branch, posso fazer um pull dessas atualizações da main.
  
### **Commitando as alterações**
  Quando crimaos uma branch o GitHub nos direciona para a página de código do novo branch, que é uma cópia da main.
  Fazemos e salvamos alterações nos arquivos do repositório. No GitHub, as alterações salvas são denominadas commits. Cada commit tem uma mensagem de commit associada, que é uma descrição que explica por que uma determinada alteração foi feita. As mensagens de commit capturam histórico das alterações para que outros colaboradores possam entender o que se fez e o porque também.
  
### Abrindo um pull request
  Os pull requests são o centro da colaboração em GitHub. Ao abrir um pull request, estamos propondo nossas alterações e solicitando que alguém analise e faça pull nessas alterações e os mescle em seu branche. As alterações, adições e subtrações são exibidas em cores diferentes.
  Assim que fazemos um commit, podemos abrir um pull request e começar uma discussão, mesmo antes de o código ser concluido.
  Usando o recurso do GitHub na mensagem de solicitação de pull, podemos solicitar comentários de pessoas ou equipes específicas, estejam elas no corredor ou a dez fusos horários de distância.
  Você pode até abrir um pull request em seu próprio repositório e fazer merge você mesmo. E uma ótima maneira de aprender o fluxo de GitHub antes de trabalhar em projetos maiores.
  
### Mesclando o pull request
  Às vezes, uma solicitação de pull pode introduzir alterações no código que entram em conflito com o código existente. Se houver algum conflito, o GitHub irá alertar sobre o código conflitante e impedirá a fusão até que os conflitos sejam resolvidos. Podemos criar um commit que resolve os conflitos ou usar comentários na pull request para discutir os conflitos com os integrantes da equipe main. Não tendo confitos estaremos pronto para fazer merge do branch na branch principal.
