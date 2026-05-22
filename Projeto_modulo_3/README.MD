
# Projeto Módulo 3 - Low Code/No Code/Vibecode

## Desafio Escolhido
O desafio selecionado pelo grupo foi o desenvolvimento de uma aplicação web voltada para o controle de finanças pessoais. A ferramenta foi projetada para resolver a desorganização financeira individual, permitindo o gerenciamento centralizado de múltiplas fontes de receita e despesas. O sistema possibilita que o usuário registre o seu salário fixo e inclua fontes de renda variável (como ganhos de motoristas de aplicativo/Uber). Além disso, conta com um módulo robusto para gestão de cartões de crédito, onde é possível cadastrar o nome de cada cartão, suas respectivas datas de fechamento e vencimento, e o limite disponível, centralizando tudo o que é essencial para o uso pessoal cotidiano.

## Protótipo
O protótipo funcional da aplicação pode ser acessado e executado localmente através dos arquivos estruturais hospedados externamente, enquanto o mapeamento visual está documentado diretamente neste repositório de acordo com as diretrizes exigidas.

* **Link para download dos arquivos de execução:** (https://1drv.ms/f/c/7faf486a2ae3d77d/IgBRZ6pDBJwJQoll5z7vUc1SAV1mP6rbVd8pfIxLqoRJLOY?e=X6ejKX)

### Instruções para Execução:
1. Acesse o link do OneDrive acima e realize o download dos arquivos.
2. Extraia a pasta baixada no seu computador e localize o arquivo principal denominado `index.html`.
3. Dê um duplo clique ou abra o arquivo `index.html` diretamente através de um navegador web (como Microsoft Edge, Google Chrome, etc.).

### Evidências no Repositório (Pasta `/docs`):
* O print da tela principal da interface está disponível no arquivo: `docs/prototipo.png`
* O detalhamento completo das funcionalidades e mapeamento do fluxo está disponível no arquivo: `docs/relatorio.pdf`

## Plataforma Utilizada
* **Ferramenta:** Antigravity (Versão Paga)
* **Justificativa:** A plataforma foi escolhida por centralizar múltiplos modelos de Inteligência Artificial em um único ecossistema. Isso viabilizou uma abordagem puramente baseada em desenvolvimento **No Code**, na qual toda a estrutura de software e lógica de programação foram geradas e manipuladas pelas IAs, sem a necessidade de escrita manual de código por parte da equipe.

## Vantagens Identificadas
A abordagem No Code apoiada pelo ecossistema Antigravity trouxe benefícios expressivos para o desenvolvimento do ecossistema financeiro:
1. **Velocidade de Desenvolvimento (Time-to-Market):** A criação do site ocorreu de forma extremamente acelerada se comparada ao desenvolvimento tradicional, permitindo materializar ideias e fluxos complexos em tempo recorde.
2. **Abstração da Curva de Aprendizado Técnico:** Eliminou-se a necessidade de domínio prévio ou escrita manual em JavaScript, HTML, CSS ou outras linguagens de programação, democratizando a construção do software.
3. **Cocriação Assistida por IA (Proatividade do Sistema):** O processo não se limitou apenas a executar comandos; as próprias Inteligências Artificiais integradas atuaram como consultoras, sugerindo melhorias, novas regras de negócios e funcionalidades pertinentes para o contexto de finanças pessoais que enriqueceram o escopo final.

## Limitações Encontradas
Durante o ciclo de desenvolvimento iterativo através das IAs, a equipe mapeou os seguintes pontos críticos e dificuldades da plataforma:
1. **Efeito Colateral em Cadeia (Regressão de Código):** Diversas vezes, ao solicitar a implementação de uma nova funcionalidade ou melhoria através de prompts, a IA introduzia, inadvertidamente, quebras e bugs em áreas do sistema que já estavam funcionando perfeitamente.
2. **Dependência Crítica da Assertividade do Prompt:** A plataforma exige instruções extremamente minuciosas; a falta de especificidade em um comando resultava em lógicas inconclusivas ou layouts desalinhados.
3. **Perda de Contexto em Conversas Longas:** Conforme o projeto crescia, as IAs contidas na plataforma demonstravam dificuldade em correlacionar o histórico completo de modificações, gerando respostas redundantes.

## Reflexão Crítica
Para mitigar os bugs gerados pelas respostas em cadeia da IA e garantir a estabilidade do site de finanças, a equipe adotou uma postura de engenharia de prompt rigorosa. Toda vez que uma inconsistência era identificada, os prompts eram refatorados e ajustados. 

Como solução criativa de contorno, implementamos a técnica **OODE** (onde instruímos a IA a sempre retornar ao início do escopo original, verificar o contexto macro e autoavaliar se alguma regra ou código pré-existente foi esquecido ou corrompido antes de entregar o resultado final). Essa abordagem sistemática permitiu "educar" os agentes geradores e estabilizar a aplicação.

## Colaboração
A equipe dividiu a execução das tarefas e responsabilidades de forma estratégica para maximizar a eficiência do fluxo No Code:
* **Evellyn:** Responsável pela concepção da ideia do projeto, engenharia inicial de prompts e publicação/gerenciamento do repositório no GitHub.
* **Gabriel:** Responsável pela análise técnica, refinamento e refatoração dos prompts para correção de bugs e aplicação da metodologia OODE.
* **Pedro:** Responsável pela confecção, estruturação e revisão dos documentos acadêmicos do projeto.
* **Guilherme:** Responsável pela confecção, estruturação e mapeamento visual dos documentos contidos na pasta `/docs`.

## Registro da Aula
Informações referentes à atividade prática de desenvolvimento do projeto:
* **Data:** 11/05/2026
* **Atividade:** Discussão crítica + mini-projeto de aplicação
* **Local:** Laboratório de informática / Quadro branco
* **Professor(a):** Kadidja Valéria

## Próximos Passos
Como visão de futuro e propostas de evolução para o encerramento do Projeto Final da Unidade 3, listamos as seguintes melhorias:
* Implementar um módulo de **previsibilidade financeira**, utilizando gráficos visuais para projetar gastos futuros (especialmente parcelamentos e despesas lançadas no cartão de crédito para o próximo mês).
* Integração com APIs bancárias para conciliação automática de extratos.
* Sistema de autenticação de usuários (Login/Senha) para garantir a privacidade dos dados financeiros locais.
