# miniguia-estudos-java-notebooklm

Estrutura de estudos Java com NotebookLM



\# Miniguia de Estudos Java com NotebookLM



Caderno de estudos criado como parte do desafio da DIO. Usei o NotebookLM como ferramenta de aprendizagem ativa para estudar Java enquanto construia meu primeiro projeto pratico.



O projeto pratico esta disponivel aqui: https://github.com/HebertKevelin/clinica-agendamento



\## Contexto e Objetivos



Escolhi Java porque quero entender como sistemas reais sao organizados por dentro. O objetivo foi usar o NotebookLM para aprofundar os conceitos que apareceram durante o desenvolvimento do projeto, transformando duvidas reais em aprendizado documentado.



\## Fontes Utilizadas no NotebookLM



\- Documentacao oficial do Java: https://docs.oracle.com/en/java/

\- Guia do Maven: https://maven.apache.org/guides/

\- Documentacao do Git: https://git-scm.com/doc



\## Engenharia de Prompts e Dificuldades



\### Pergunta 1: O que e arquitetura MVC em Java e como ela organiza o codigo?



Resposta do NotebookLM: A arquitetura MVC organiza o codigo em tres componentes. O Model gerencia os dados e a logica de negocio sem saber como serao exibidos. A View exibe os dados e envia comandos do usuario. O Controller atua como intermediario recebendo as entradas, processando as solicitacoes e decidindo qual View apresentar. Essa separacao facilita a manutencao pois permite alterar a interface sem modificar a logica de dados.



Dificuldade: As fontes nao definiam MVC diretamente. O NotebookLM identificou o conceito de aplicacoes multicamadas no Java EE e complementou com conhecimento externo. Aprendi que nem sempre a fonte responde tudo e que saber interpretar o que ela oferece tambem e parte do estudo.



\---



\### Pergunta 2: O que e encapsulamento em Java e por que ele e importante?



Resposta do NotebookLM: Encapsulamento e a tecnica de esconder os detalhes internos de um objeto e proteger seus dados declarando variaveis como private e fornecendo metodos publicos getters e setters para acesso controlado. E importante porque garante seguranca e controle dos dados, protege contra alteracoes acidentais e facilita a manutencao sem quebrar o restante do sistema.



Dificuldade: As fontes focavam em infraestrutura e o conceito nao estava descrito diretamente. Aprendi a reformular a pergunta para extrair o maximo da ferramenta mesmo quando a fonte nao cobre o tema de forma direta.



\---



\### Pergunta 3: Como o Maven organiza um projeto Java?



Resposta do NotebookLM: O Maven organiza o projeto atraves do arquivo POM que contem todas as configuracoes e dependencias. Utiliza um Layout de Diretorio Padrao que define onde cada tipo de arquivo deve ficar. Trabalha com convencoes e padroes de nomenclatura para simplificar a estrutura e usa repositorios para gerenciar bibliotecas externas.



Dificuldade: Antes desse estudo eu nao entendia porque o PATH do Maven precisava apontar para a pasta bin especificamente. Depois de estudar o layout padrao ficou claro que o Maven so funciona quando o sistema sabe exatamente onde estao seus executaveis.



\---



\## Resumo do Projeto Pratico



Construi um sistema de agendamento de consultas medicas em Java que notifica pacientes quando faltam 15 ou 7 dias para a consulta. O sistema pergunta se confirmam a presenca e atualiza o status automaticamente. Toda a logica foi organizada seguindo a arquitetura MVC.



\## Glossario



\*\*MVC\*\* - Organiza o codigo em tres camadas: Model cuida dos dados, Controller coordena as acoes e View exibe o resultado.



\*\*Encapsulamento\*\* - Protege os dados de uma classe usando private. O acesso so e permitido atraves de getters e setters.



\*\*LocalDate\*\* - Classe do Java para trabalhar com datas de forma segura.



\*\*Maven\*\* - Ferramenta que organiza o projeto atraves do arquivo POM com todas as configuracoes e dependencias.



\*\*Git\*\* - Sistema que registra cada mudanca feita no codigo ao longo do tempo.



\*\*PATH\*\* - Lista que o Windows consulta quando um comando e digitado. Se o programa nao estiver nessa lista o sistema nao o encontra.



\*\*NotebookLM\*\* - Ferramenta do Google que permite estudar documentos e fontes usando IA como apoio.



\## Prompts Reutilizaveis



\- "Explica o que e \[conceito] em Java com exemplo pratico"

\- "Porque esta dando esse erro: \[colar o erro]"

\- "Revisa esse codigo: \[colar o codigo]"

\- "Qual a diferenca entre \[conceito A] e \[conceito B] em Java?"

\- "Como funciona \[metodo ou classe] com um exemplo real?"



\## Tecnologias



\- Java 21

\- Maven 3.9.15

\- IntelliJ IDEA 2026

\- Git e GitHub

\- NotebookLM



\---



Desenvolvido por Heber Kevelin - primeiro projeto, muitos erros, muito aprendizado.

