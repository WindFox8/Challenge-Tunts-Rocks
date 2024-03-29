# Resolução do desafio:

O desafio deixava livre a escolha da linguagem para o desafio, dando a documentação do google sheets como uma referencia e guia para a realização do mesmo, existindo assim varios meios de realizar-lo, a maioria configurando uma api e a consumindo atraves de alguma linguagem, também sendo possivel usar o sheetDB para tranformar a planilha num BD, mas através da documentação nota-se que a maneira mais prática e eficiente é desenvolver um script pelo google apps script e executa-lo diretamenta na planilha atraves da implementação do script por meio de um botão, sendo esse o meio que escolhi para realizar o desafio, o resultado pode ser conferido no gif abaixo sendo o codigo do script encontrado nesse repositorio com o nome de "code_challenge_tunts_rocks".

Link para planilha: https://docs.google.com/spreadsheets/d/1hTOrEE8Imt9QYWPxyrkoB-HemPH0kPwlzmCb4rgI7jM/edit?usp=sharing
É necessario estar logado numa conta google e aceitar um termo para que o botão tenha permissao de executar o script.

![imagem da página](https://github.com/WindFox8/Challenge-Tunts-Rocks/blob/main/tunts_rocks.gif)



# Sobre o Google Apps Script (GAS):

O Google Apps Script é uma plataforma de desenvolvimento de scripts baseada na nuvem oferecida pelo Google. Essa plataforma permite que os usuários criem automações, extensões e aplicativos personalizados que interagem com os produtos do Google, como o Google Sheets, Google Docs, Google Drive e outros serviços do ecossistema Google Workspace, utiliza uma linguagem de script baseada em JavaScript, o que facilita para aqueles familiarizados com JavaScript começarem a desenvolver.


# Desafio:

OBJETIVO 

Parte integrante do processo seletivo da Tunts.Rocks, o desafio de programação tem como objetivo  principal a avaliação das habilidades de programação do candidato. Levando em conta não  apenas o êxito de implementação da funcionalidade desejada, mas também uma análise da  solução de forma estrutural, semântica e performática.

CRITÉRIOS DE AVALIAÇÃO 

• Bom entendimento do problema a ser resolvido; 

• Êxito na implementação da funcionalidade; 

• Estrutura do código fonte; 

• Documentação e utilização de boas práticas; 

• Utilização de ferramentas de desenvolvimento básicas. 

DESAFIO 

Criar uma aplicação em uma linguagem de programação de sua preferência (caso esteja se  candidatando a uma vaga de linguagem de programação específica, exemplo: programador  node.js, utilizar a linguagem/tecnologia específica da vaga). A aplicação deve ser capaz de ler  uma planilha do google sheets, buscar as informações necessárias, calcular e escrever o  resultado na planilha. 

Primeiro passo: crie uma cópia da planilha para você: 

Acesse a planilha: https://docs.google.com/spreadsheets/d/1XvWJcRLj2WAeXO3ULQ_GxGm9---3SZkjMbGcXMJtt70/edit#gid=0

Use a função de fazer cópia:

Modifique o nome da planilha para Engenharia de Software – Desafio [SEU NOME]:

Depois deixe a planilha pública para edição para qualquer um com acesso ao link:

Utilize a planilha recém criada (cópia) para realizar o teste. 

REGRAS: 

Calcular a situação de cada aluno baseado na média das 3 provas (P1, P2 e P3), conforme a  tabela: 

Média (m) Situação:

m<5  - Reprovado por Nota

5<=m<7  - Exame Final

m>=7  - Aprovado

Caso o número de faltas ultrapasse 25% do número total de aulas o aluno terá a situação  "Reprovado por Falta", independente da média.  Caso a situação seja "Exame Final" é necessário calcular a "Nota para Aprovação Final"(naf) de  cada aluno de acordo com seguinte fórmula: 

5 <= (m + naf)/2

Caso a situação do aluno seja diferente de "Exame Final", preencha o campo "Nota para  Aprovação Final" com 0. 

Arredondar o resultado para o próximo número inteiro (aumentar) caso necessário. Utilizar linhas de logs para acompanhamento das atividades da aplicação. 

Os textos do código fonte (atributos, classes, funções, comentários e afins) devem ser escritos  em inglês, salvo os identificadores e textos pré-definidos nesse desafio. 

O candidato deve especificar os comandos que devem ser utilizados para execução da  aplicação. Exemplo de uma aplicação node.js: 

1. npm install 

2. npm start 

O candidato deve publicar o código fonte em um repositório git de sua preferência (exemplo:  github, gitlab, bitbucket e etc). 



ENTREGÁVEIS 

Link público do repositório git escolhido; 
Comandos para rodar a aplicação; 
Link público da planilha copiada. 

REFERÊNCIA 

Documentação da Google Sheets: https://developers.google.com/sheets/api/guides/concepts

Certifique-se de reservar tempo suficiente para fazer o teste.
Caso você saia do teste sem finalizá-lo, o teste será considerado como concluído e você não poderá fazer novamente.




