# Desafio Analista de Qualidade

Parabéns por ter chegado nesta fase!
Agora queremos te conhecer melhor, te conhecer tecnicamente. Para isso desenvolvemos essa prova com o intuito de avaliar seu desempenho.

# A Prova

Imagine que você é um analista de qualidade da equipe de desenvolvimento do Trello (trello.com), e foi incumbido de testar a funcionalidade de criação de quadros, listas e cartões.

Como o Trello tem diversas funcionalidades, você irá testar somente os seguintes itens:

 - Criar Quadros
 - Remover Quadros
 - Criar Listas
 - Remover Listas
 - Criar Cartões
 - Remover Cartões
 - Descrever um cartão
 - Adicionar um etiqueta ao um cartão
 - Adicionar um checklist ao um cartão

Tendo os itens a serem testados, a prova possui fases a serem cumpridas, que são:

 1. Criação de cenários de teste
 2. Relatório de validação de cenários de teste
 3. Desenvolvimento de testes automatizados dos cenários de teste
 4. Relatório de desenvolvimento da prova

O não comprimento de alguma fase **não** implica em desclassificação, somente irá somará pontos caso faça.

## Fase de Criação de Cenários de Teste

Nesta fase da prova, você irá descrever quais cenários de testes que você irá testar mediante as funcionalidades que foram citadas acima.

Exemplo: 
No Trello existe a possibilidade de Adicionar membro a um cartão e um exemplo de cenário seria: 
	Pré-Condições: No quadro deve haver pelo menos um membro, uma lista e um cartão previamente existentes.
	Cenário: 
 1. Clicar no cartão
 2. Clicar em Membros
 3. Escolher Membro
 
 Pós-Condições: O cartão deve ter um membro associado.

Seus cenários devem estar na pasta **Cenarios** que esta no repositório.

## Fase de Validação dos Cenários

Esta etapa consiste em testar os cenários levantados na etapa anterior e redigir um relatório comprovando que as funcionalidades estão atendendo conforme solicitado.

O relatório deve ser incluído na pasta **Validacao**

## Fase Desenvolvimento de Testes Automatizados

Neste momento com os cenários em mãos e a garantia que as funcionalidades estão funcionando conforme esperado, você irá desenvolver testes automatizados para que não precise mais testar de forma manual estas funcionalidades, com isso garantindo qualidade nas entregas.

Uma dica para essa fase, utilizar frameworks de teste de integração como selenium ou cypress.
Os códigos de testes devem estar na pasta **Testes**.

## Fase Relatório de Desenvolvimento

Nesta fase final você irá redigir um relatório de como foi o seu desenvolvimento durante a prova, quais foram as dificuldades encontradas, o que você aprendeu de novo, quais decisões você tomou para entregar a prova.

Queremos saber o quanto você evoluiu nesta prova, pois trabalhar na Before envolve constante evolução.

O relatório deve ser incluído na pasta **Relatorio**

## Duração da prova

A prova poderá ser entregue até:

**04/01/2023 às 23:59:59**

## Como entregar a prova

**Caso esteja familiarizado com GIT:**
Antes de começar seus testes, faça um fork do repositório do avaliador e faça um clone do repositório forkeado no seu ambiente.
Após terminar os testes, submeta sua prova ao repositório forkeado e abra uma Pull Request solicitando a inclusão dos seuus arquivos no repositório do avaliador.
Resumindo:

1. Fork
2. Clone
3. Testes
4. Push para o Fork
5. Pull Request do Fork para o repositório do seu Avaliador

**Caso não esteja familiarizado com GIT:**
Antes de começar seus testes, faça um fork do repositório do avaliador. No seu ambiente local, crie uma estrutura de pastas identicas para facilitar sua organização, faça todos seus testes. Após finalizar você poderá fazer upload de arquivos direto pelo git, ao entrar em uma pasta verá a opção Add file -> Upload files, onde poderá fazer o envio dos arquivos de sua prova nas pastas solicitadas.
Ao finalizar o envio dos arquivos, você poderá abrir uma Pull Request para o repositório do avaliador.
Resumindo:

1. Fork
2. Estrutura de pastas e testes no local
3. Upload de arquivos para seu fork
4. Pull Request do Fork para o repositório do seu Avaliador

## Dicas

 1. Não se preocupe em entregar com uma fase faltando, o importante é você tentar e mostrar o quanto conseguiu desenvolver.
 2. Caso tenha dúvida, pergunte!
 3. Ao final da prova não esqueça de verificar se todos os arquivos estão no repositório.

👊 Boa Prova!
