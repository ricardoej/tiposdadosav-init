# Programação Tipos de Dados Avançados

## Informações Gerais
- **Componente Curricular:** Programação Tipos de Dados Avançados
- **Carga-horária:** 32 horas
- **Ementa:** Criando e manipulando variáveis indexadas (vetores e matrizes). Manipulação de Strings. Mesclando os tipos de dados. Alocação dinâmica de memória. Conceitos e prática de referências.
- **Conteúdo:** Matrizes. Strings. Funções: parâmetros e tipo de retorno. Recursividade. Tipos de dados compostos (definidos pelo programador). Referência e alocação dinâmica de memória. Passagem de parâmetros por valor e por referência. Testes unitários. Arquivos.

## Bibliografia Básica
- FURGERI, Sérgio. Java 8 - Ensino Didático - Desenvolvimento e Implementação de Aplicações. Editora Saraiva, 2015. [Link](https://integrada.minhabiblioteca.com.br/#/books/9788536519340/)
- FINEGAN, Edward; LIGUORI, Robert. OCA Java SE 8: guia de estudos para o exame 1Z0-808. Grupo A, 2018. [Link](https://integrada.minhabiblioteca.com.br/#/books/9788582604779/)
- FORBELLONE, A. L. V.; EBERSPACHER, H. F. Lógica de programação. São Paulo: Makron Books, 2000. 

## Bibliografia Complementar
- ARRER, Harry. Programação estruturada de computadores: algoritmos estruturados. 3. ed. Rio de Janeiro LTC, 1999. 
- HORSTMANN, Cay; CORNELL, Gary. Core Java: Volume I – Fundamentos. São Paulo: Pearson, 2010. 
- SCHILDT, Herbert. Java para Iniciantes. Grupo A, 2015. [Link](https://integrada.minhabiblioteca.com.br/#/books/9788582603376/)
- SIERRA, Kathy; BATES, Bert. Use a Cabeça Java. 2.ed. São Paulo: Alta Books, 2010. 
- SANTOS, Marcela G.; SARAIVA, Maurício O.; FÁTIMA, Priscila G. Linguagem de programação. Grupo A. [Link](https://integrada.minhabiblioteca.com.br/#/books/9788595024984/)

## Sistema de Avaliação
- Trabalho Prático - 30 pontos
- Prova Prática - 30 pontos
- Exercícios em aula - 30 pontos
- Participação - 10 pontos

## Formulário de Avaliação do Professor/Disciplina
- [Link para o formulário de avaliação](https://forms.gle/VsXj3GuBgqW8aMTm6)

## Links dos repositórios utilizados em aula
(!) Todos esses exercícios devem ser entregues para compor a nota de "Exercícios em Aula"
- Data de Entrega: 03/04/2024: [https://github.com/ricardoej/tiposdadosav-calculadora](https://github.com/ricardoej/tiposdadosav-calculadora)
- Data de Entrega: 03/04/2024: [https://github.com/ricardoej/tiposdadosav-analisevendas](https://github.com/ricardoej/tiposdadosav-analisevendas)

## Passos para desenvolvimento e entrega
- Clonar o respositório na pasta de workspace do eclipse
```
cd ~/eclipse-workspace
git clone <link_do_repositorio>
```
- Criar uma nova branch de entrega com o padrão "feature/<primeiro_nome>-<sobrenome>". Ex.: feature/ricardo-julio
```
git checkout -b feature/<primeiro_nome>-<sobrenome>
```
- Importar o projeto no Eclipse: File -> Import -> General -> Existing Projects into Workspace. Clicar em "Next", escolher a pasta que você fez o clone do projeto e clicar em "Finish"
- Desenvolver o problema fazendo com que todos os testes unitários passem sem erros
- Fazer o commit do código desenvolvido
```
cd ~/eclipse-workspace/<nome_da_pasta_do_rpojeto>
git add .
git commit -m "<Seu nome completo aqui>"
git push origin feature/<primeiro_nome>-<sobrenome>
```
- Verificar no github, no repositório do exercício se a entrega foi feita. Acessar o repositório, onde está escrito "main" no canto superior esquerdo, mudar para a sua branch e verificar se o código subiu certinho
