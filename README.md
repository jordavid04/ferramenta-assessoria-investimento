# Ferramenta de Assessoria de Investimento

Projeto de Extensão Universitária II  
Curso: Bacharelado em Sistemas de Informação  
Disciplina: Extensão Universitária II  
Professores: André Fabiano de Moraes  
Alunos: Andersom Gabriel e Jorge David Bolognesi  
Semestre: 2026.1

## 1. Resumo

Este projeto consiste no planejamento e desenvolvimento de uma ferramenta digital web focada na consolidação de investimentos e na educação financeira aplicada. A solução utiliza um formulário inteligente de suitability fundamentado nas normas da ANBIMA e integrado com Inteligência Artificial Generativa (Google Gemini), com o objetivo de auxiliar investidores iniciantes na organização de ativos ideais para sua realidade financeira.

A proposta é voltada prioritariamente a servidores públicos, com o foco na melhoria da saúde financeira familiar e no fortalecimento da educação financeira. O projeto aborda desde o levantamento de requisitos e modelagem de software até a prototipação de interfaces e a definição da arquitetura do sistema, estabelecendo uma base sólida para a implementação do Produto Mínimo Viável (MVP).

Palavras-chave: Educação financeira; Investimentos; Inteligência Artificial; Modelagem de Software; Servidores públicos.

## 2. Introdução e Justificativa

A necessidade de modernizar a orientação financeira regional por meio de sistemas de informação é o principal motivador desta proposta. A fundamentação teórica está alinhada aos Objetivos de Desenvolvimento Sustentável (ODS) da Organização das Nações Unidas, principalmente:

- ODS 4 – Educação de Qualidade
- ODS 8 – Trabalho Decente e Crescimento Econômico

A utilização de inteligência artificial no contexto financeiro é amplamente reconhecida como uma tendência estratégica para aprimorar análises, reduzir vieses emocionais e personalizar recomendações. Estudos recentes apontam que a IA pode potencializar a tomada de decisão em investimentos e promover maior eficiência na construção de carteiras adequadas ao perfil do investidor.

Além disso, a plataforma pretende reduzir as barreiras de acesso à educação financeira, oferecendo uma solução acessível, responsiva e de fácil utilização por meio de uma interface web. Diferentemente de soluções focadas em apps móveis, a abordagem web permite maior democratização do uso, sem necessidade de instalação e com maior alcance para diferentes perfis de usuários.

## 3. Objetivo Geral

Desenvolver uma ferramenta digital intuitiva e acessível que utilize formulários de suitability e integração com a API do Google Gemini para recomendar ativos financeiros e apoiar a gestão financeira de investidores iniciantes.

## 4. Objetivos Específicos

- Mapear e estruturar um formulário de suitability com aproximadamente 18 questões baseadas nas regras da ANBIMA;
- Definir a arquitetura da interface web utilizando Next.js e boas práticas de usabilidade;
- Selecionar a infraestrutura de IA adequada, priorizando a API do Google Gemini;
- Integrar a IA para processar as respostas do usuário e gerar recomendações personalizadas;
- Estruturar a persistência de dados utilizando PostgreSQL;
- Contribuir para a educação financeira e para a autonomia de decisões de investimento;
- Produzir o relatório final e os artefatos do projeto.

## 5. Problema e Contexto

Muitos investidores iniciantes enfrentam dificuldades para tomar decisões financeiras de forma consciente e segura. A ausência de orientação adequada, aliada ao excesso de informação disponível no mercado, gera insegurança, medo e tomadas de decisão baseadas em impulsos ou em conhecimento superficial.

Nesse cenário, a proposta do projeto busca criar uma ferramenta que auxilie o investidor a entender melhor seu perfil, avaliar seu comportamento financeiro e receber orientações com base em critérios estruturados. A combinação de educação financeira com inteligência artificial torna a proposta relevante para a formação de hábitos de investimento mais responsáveis e sustentáveis.

## 6. Público-Alvo

O projeto tem foco principal em:

- Servidores públicos;
- Investidores iniciantes;
- Pessoas com interesse em educação financeira;
- Usuários que desejam organizar melhor suas finanças pessoais e ampliar seus conhecimentos sobre investimentos.

## 7. Resultado Esperado

A plataforma deverá funcionar como um assistente de investimentos e repositório de educação financeira. Espera-se que o usuário receba relatórios de perfil de investidor, sugestões de ativos adequados ao seu perfil e orientações que favoreçam planejamento financeiro de longo prazo.

Com isso, pretende-se:

- aumentar a qualidade das decisões financeiras;
- reduzir a insegurança no processo de investimento;
- promover maior organização financeira familiar;
- estimular o uso consciente de recursos;
- contribuir para a educação financeira e para a estabilidade econômica.

## 8. Metodologia

A metodologia do projeto será organizada em etapas, com foco em desenvolvimento estruturado e em entregas progressivas.

### 8.1 Levantamento e Definição de Requisitos
Realização de pesquisa sobre as regras e procedimentos de suitability da ANBIMA, com foco na criação de um questionário que reflita adequadamente o perfil financeiro do usuário.

### 8.2 Análise e Definição Tecnológica
Seleção da infraestrutura de IA com base em critérios de acessibilidade, documentação, integração web e custo. A solução adotada foi a API do Google Gemini.

### 8.3 Design e Estruturação Web
Uso do framework Next.js para a construção da interface web e de um framework CSS para garantir responsividade, organização visual e navegabilidade intuitiva.

### 8.4 Desenvolvimento Lógico e Integração
Implementação da lógica de servidor por meio de rotas de API do Next.js, com comunicação ao banco de dados PostgreSQL e integração com a API do Gemini para processamento das respostas do usuário.

### 8.5 Testes e Validação
Realização de simulações com o público-alvo para ajustar a precisão da IA, verificar a usabilidade da interface e corrigir possíveis falhas no fluxo da aplicação.

## 9. Tecnologias e Arquitetura

### 9.1 Tecnologias propostas
- Next.js
- PostgreSQL
- Google Gemini API
- Google AI Studio
- HTML / CSS / JavaScript / TypeScript
- UML para modelagem de software
- Figma ou prototipação visual
- Git/GitHub para versionamento

### 9.2 Arquitetura do sistema
A arquitetura da aplicação será organizada em camadas:

- Front-end: interface web responsiva e interativa;
- Back-end: processamento da lógica, integração com a IA e validação das respostas;
- Banco de Dados: armazenamento das informações de usuários, perfis e históricos;
- API Externa: Google Gemini para gerar recomendações com base no perfil financeiro do usuário.

## 10. Desenvolvimento de Ações

O projeto se apoia diretamente nos conhecimentos adquiridos ao longo da formação acadêmica. As principais áreas aplicadas incluem:

- Engenharia de Software
- Desenvolvimento Web
- Fundamentos de Economia
- Banco de Dados
- Programação Orientada a Objetos

A equipe utilizou princípios de metodologias ágeis (Scrum e Kanban) para a gestão do projeto, promovendo organização, acompanhamento contínuo e entrega incremental.

## 11. Modelagem UML

Durante a concepção do projeto, foram elaborados artefatos de modelagem para dar suporte ao desenvolvimento futuro, incluindo:

- Diagrama de Caso de Uso
- Diagrama de Componentes
- Diagrama de Implantação

Esses diagramas descrevem:

- as interações do investidor com a plataforma;
- as integrações entre front-end, back-end, banco de dados e IA;
- a infraestrutura de execução da solução em ambiente de produção.

## 12. Prototipação e Interface

Foram desenvolvidos wireframes e protótipos de média fidelidade para validar a estrutura da interface, a usabilidade do formulário e a apresentação dos resultados. A proposta de UX prioriza:

- simplicidade;
- clareza no preenchimento de dados;
- navegação intuitiva;
- apresentação objetiva das recomendações;
- foco em educação financeira.

## 13. Resultados Alcançados

Até o presente momento, o projeto alcançou importantes marcos em sua fase de concepção e planejamento, incluindo:

- estruturação das regras de negócio do formulário de suitability;
- mapeamento das questões de perfil do investidor;
- modelagem do sistema em UML;
- definição da arquitetura tecnológica;
- prototipação de interfaces;
- seleção da tecnologia de IA;
- geração de chaves de acesso para o Google AI Studio;
- consolidação de uma base para a implementação do MVP.

## 14. Conclusões

A concepção estrutural da ferramenta demonstrou a viabilidade prática de integrar tecnologias contemporâneas, como desenvolvimento web, banco de dados e inteligência artificial, para a criação de uma solução voltada à educação financeira e ao investimento consciente.

O projeto atende a uma demanda real de inclusão financeira, especialmente para o público de servidores públicos, e se alinha aos princípios de desenvolvimento sustentável e à democratização do conhecimento financeiro. A utilização das normas da ANBIMA fortalece a confiabilidade e a qualidade da solução.

## 15. Trabalhos Futuros

Para a próxima etapa do desenvolvimento, os principais próximos passos incluem:

- otimizar a experiência do usuário no formulário de suitability;
- dividir as perguntas em etapas para reduzir fadiga cognitiva;
- adaptar a plataforma para outros públicos, como trabalhadores de empresas privadas e autônomos;
- integrar APIs de mercado financeiro em tempo real;
- melhorar o prompt de IA para recomendações mais precisas;
- codificar e testar o MVP com usuários reais;
- validar a usabilidade e a assertividade das recomendações.

## 16. Cronograma

O planejamento das atividades prevê a execução em etapas ao longo do semestre:

- Setembro: revisão de requisitos, arquitetura e identidade visual;
- Outubro: configuração do ambiente, criação do repositório e início da implementação do MVP;
- Novembro: desenvolvimento de funcionalidades, integração com IA e banco de dados;
- Dezembro: testes finais, validação e elaboração do relatório final.

## 17. Formulário de Suitability (Resumo)

O questionário proposto contém aproximadamente 18 questões, cobrindo aspectos como:

- idade;
- renda disponível;
- patrimônio financeiro;
- objetivos de investimento;
- horizonte de investimento;
- conhecimento em finanças;
- experiência com produtos financeiros;
- tolerância ao risco;
- capacidade de resistir a oscilações do mercado.

A classificação do perfil é feita com base em pontuação, permitindo identificar os perfis:

- Conservador
- Moderado
- Arrojado
- Agressivo

## 18. Referências Bibliográficas

- ASSOCIAÇÃO BRASILEIRA DAS ENTIDADES DOS MERCADOS FINANCEIRO E DE CAPITAIS (ANBIMA). Regras e Procedimentos de Suitability. 2021.
- BASTOS, Athena. IA para finanças. Alura, 2024.
- FEBRABAN. Pesquisa Febraban de Tecnologia Bancária 2024.
- FERREIRA, et al. A influência da inteligência artificial nas decisões de investimento: tendências, aplicações e desafios no cenário financeiro contemporâneo. AEDB, 2023.
- MARINS, Carlos Eduardo Fonseca. App Invest: Uso da inteligência artificial como auxiliar. FATEC, 2025.
- ONU. Objetivos de Desenvolvimento Sustentável (ODS). 2015.
- YOSHINAGA, Claudia Emiko; CASTRO, F. Henrique. Inteligência artificial: a vanguarda das finanças. Revista GV Executivo, 2023.

## 19. Licença

Este projeto é destinado ao uso acadêmico e de extensão universitária. A licença pode ser ajustada conforme a política da instituição de ensino ou da equipe responsável.

Para uso em repositório público no GitHub, a recomendação é utilizar a licença MIT. Caso desejar, também posso preparar uma versão adaptada com:
- logo do projeto;
- anexo com fluxograma;
- badges do GitHub;
- seção de arquitetura em diagramas;
- instruções de instalação e execução.

## 20. Equipe

- Andersom Gabriel
- Jorge David Bolognesi

## 21. Status do Projeto

Em desenvolvimento / Planejamento da implementação do MVP
