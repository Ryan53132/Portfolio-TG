# Ryan Araújo dos Santos

## Introdução

Sou estudante do curso de Análise e Desenvolvimento de Sistemas da Fatec São José dos Campos. Durante a graduação, participei de quatro projetos da Aprendizagem por Projetos Integrados (API) na Equipe Echo, trabalhando com front-end e design, integração de Inteligência Artificial, automação de versionamento e processamento de arquivos técnicos. Antes da Fatec, cursei o ensino técnico em Análise e Desenvolvimento de Sistemas (ADS) na ETEC, onde tive meu primeiro contato com a programação.

![Foto de Ryan Araújo dos Santos](imagens/foto.jpeg)

## Contatos
* [GIT](https://github.com/Ryan53132)
* [LinkedIn](https://www.linkedin.com/in/ryan-araujo-dos-santos-8391b927b)

## Meus Principais Conhecimentos

* **Python:** leitura e processamento de arquivos DXF com a biblioteca ezdxf e geração de dados estruturados em JSON.
* **Front-end e design de interfaces:** Bootstrap, HTML e CSS, com prototipação de telas e definição de identidade visual.
* **Integração com Inteligência Artificial:** uso de modelos de linguagem locais com o Ollama (Qwen2.5-Coder), com ajuste de desempenho.
* **Git e GitHub:** versionamento, trabalho em equipe e automação de commits com token de acesso pessoal.
* **Metodologia ágil (Scrum):** atuação como Scrum Team, Product Owner e desenvolvedor.


## Meus Projetos

### Em 2024-2

**Projeto: EasyScrum** | Função na equipe: Scrum Team

**Empresa parceira.** O projeto foi desenvolvido para um cliente interno, representado pela própria Fatec, que precisava treinar e acompanhar o desempenho de seus funcionários no método Scrum. 

**Problema.** Funcionários novos, pessoas que aprendem melhor com imagens e pessoas com deficiência visual tinham dificuldade de acessar o mesmo material sobre o método Scrum, e faltava uma forma de fixar o conteúdo e de acompanhar o desempenho de cada funcionário.

**Solução.** Desenvolvemos o EasyScrum, um site informativo e educacional que ensina o método Scrum de forma simples. Ele reúne conteúdo organizado em tópicos, imagens e áudios como recursos de mídia, material de apoio, um teste de fixação do conteúdo, manual do usuário e uma página "Quem Somos".

**Entregue pela equipe.** Ao longo do Kick Off e de três sprints, entregamos o site funcional, apresentado na Feira de Soluções em 12/12/2024.

[GIT](https://github.com/EquipeEcho/EasyScrum)

[![Demonstração do EasyScrum](https://img.youtube.com/vi/RhitfLJMUBE/0.jpg)](https://youtu.be/RhitfLJMUBE)

#### Tecnologias Utilizadas
* **Python e Flask:** base do back-end do site.
* **HTML, CSS e JavaScript:** estrutura, estilo e comportamento das páginas.
* **Bootstrap:** framework de interface que garantiu um layout responsivo e consistente.
* **Jira e Notion:** planejamento das sprints, backlog e documentação.
* **GitHub e VS Code:** versionamento e desenvolvimento do código.
* **Discord:** comunicação da equipe.

#### Contribuições Pessoais
Desenvolvi a página inicial (home) do site com o framework Bootstrap. Utilizei o componente **navbar** para a navegação principal e o **accordion** para organizar os tópicos do método Scrum em caixas de conteúdo expansíveis, o que permite aprofundar cada assunto sem sobrecarregar a página. Também apliquei as classes utilitárias de espaçamento do framework (padding e margin) para manter o alinhamento e o ritmo visual consistentes. Esse trabalho atende às histórias de usuário de interface intuitiva e de home organizada do backlog.

#### Hard Skills
* Bootstrap (navbar, accordion e utilitários de espaçamento) - Sei fazer com autonomia
* HTML e CSS - Sei fazer com autonomia
* Git e GitHub - Sei fazer com autonomia
* Scrum (como Scrum Team) - Sei fazer e posso ensinar

#### Soft Skills
* Colaboração e gerenciamento de tempo - Para cumprir os prazos das sprints, dividi as tarefas com a equipe, de modo que a home ficasse pronta a tempo de se integrar ao restante do site.
* Adaptabilidade - Ajustei o layout da home após o feedback da equipe e do cliente, sem perder a consistência visual entre as páginas.
* Proatividade - Aprendi o Bootstrap rapidamente para entregar a home dentro da sprint.

---

### Em 2025-1

**Projeto: botEcho** | Função na equipe: Product Owner

**Empresa parceira.** Os professores da Fatec atuaram como parceiros e clientes do projeto.

**Problema.** Desenvolvedores perdem tempo para revisar, entender e documentar código, e nem sempre aplicam boas práticas de programação.

**Solução.** Desenvolvemos o botEcho, uma IDE com suporte a Inteligência Artificial que analisa e otimiza o código, explica trechos, gera documentação automática, recomenda boas práticas e executa o código no próprio ambiente. Na Sprint 3, a IDE foi integrada ao GitHub para versionamento, ganhou uma versão executável e uma interface refinada e personalizável.

**Entregue pela equipe.** Ao longo de três sprints, entregamos a IDE funcional com IA integrada, versionamento via GitHub e executável para uso por outras pessoas.

[GIT](https://github.com/EquipeEcho/botEcho)

#### Tecnologias Utilizadas
* **Java:** linguagem em que a IDE foi desenvolvida.
* **Ollama:** execução local do modelo de IA, sem depender de serviços externos.
* **Qwen2.5-Coder:** modelo de linguagem voltado a código, usado nas funções de análise, explicação e documentação.
* **Git e GitHub:** versionamento do projeto e destino dos commits automáticos da IDE.
* **Jira e Notion:** gestão das sprints e documentação.
* **VS Code e Discord:** desenvolvimento e comunicação da equipe.

#### Contribuições Pessoais
**Integração da IA.** Integrei a Inteligência Artificial à IDE por meio do Ollama, com o modelo Qwen2.5-Coder. A comunicação entre a IDE e o modelo é feita via linha de comando (CMD), e a IA passou a oferecer as funções de análise de código, explicação de trechos, geração de documentação e recomendações de boas práticas. O principal desafio foi o tempo de resposta, que estava alto. A solução foi adotar uma versão menor do modelo, equilibrando velocidade e qualidade das respostas.

**Envio automático de commits.** Implementei o envio automático de commits, parte da integração da IDE com o GitHub (a história de maior estimativa do backlog, com 21 pontos). A autenticação é feita por token de acesso pessoal (PAT), e os comandos Git (add, commit e push) são executados via linha de comando a partir da IDE. O principal desafio foi a autenticação com o GitHub, necessária para que o push funcionasse sem intervenção manual.

#### Hard Skills
* Integração com IA local (Ollama e Qwen2.5-Coder) - Sei fazer e posso ensinar
* Java - Sei fazer com ajuda
* Automação de Git via linha de comando e token de acesso - Sei fazer com ajuda

#### Soft Skills
* Resiliência - Precisei lidar com a lentidão da IA e com a falha na autenticação do GitHub, testando alternativas (modelo menor, token de acesso) até chegar a uma solução funcional.
* Gestão de projetos - Como Product Owner, priorizei o backlog junto com a equipe e alinhei as entregas de cada sprint com os objetivos do projeto.
* Tomada de decisão - Quando surgiram problemas, como a lentidão da IA, decidi com a equipe a solução a seguir (modelo menor).
* Foco e liderança - Mantive a equipe concentrada nas histórias de maior prioridade, como a integração com o GitHub.

---

### Em 2025-2

**Projeto: EchoNova (Radar Entrenova)** | Função na equipe: Desenvolvedor

**Empresa parceira.** A Entrenova, empresa do ramo de treinamentos corporativos e audiovisual, que busca validar produtos de treinamento online e atender às demandas do mercado.

**Problema.** A Entrenova precisava entender as necessidades de treinamento das empresas e gerar dados estratégicos para sustentar suas ofertas, enquanto as empresas precisavam enxergar rapidamente o valor da plataforma.

**Solução.** Desenvolvemos o Radar Entrenova, uma plataforma de diagnóstico inteligente de treinamentos. A empresa responde a um questionário simplificado e recebe um diagnóstico inicial e sugestões de trilha. Depois, escolhe um plano, paga a adesão, se cadastra e responde a um questionário aprofundado, que gera um relatório detalhado. A Entrenova acompanha tudo em um dashboard.

**Entregue pela equipe.** Entregamos, em três sprints, o questionário geral, a geração de diagnósticos personalizados com envio por e-mail, a tela de planos e pagamento, o cadastro e o dashboard do cliente.

[GIT](https://github.com/EquipeEcho/EchoNova)

[![Sprint 1](https://img.youtube.com/vi/B-3Zbw5OlP4/0.jpg)](https://www.youtube.com/watch?v=B-3Zbw5OlP4)
[![Sprint 2](https://img.youtube.com/vi/7-NhXobXGko/0.jpg)](https://www.youtube.com/watch?v=7-NhXobXGko)
[![Sprint 3](https://img.youtube.com/vi/i7YsbaNFY7E/0.jpg)](https://www.youtube.com/watch?v=i7YsbaNFY7E)

#### Tecnologias Utilizadas
* **React e TypeScript:** construção da interface e tipagem do código.
* **JavaScript e Node.js:** lógica da aplicação e back-end.
* **JWT (JSON Web Token):** autenticação dos usuários no login.
* **Python e Ollama:** geração do diagnóstico inteligente com IA offline.
* **Jira, Notion e GitHub:** gestão das sprints, documentação e versionamento.

#### Contribuições Pessoais
**Design.** Criei o design da aplicação a partir de um protótipo feito no Paint. Desenvolvi os cards da área de planos, os cards de resultado do relatório e o tema de fundo do site, adotando cores vivas em alinhamento ao segmento audiovisual da Entrenova, definidas em acordo com a equipe. Também fiz o design do dashboard de RH e da Entrenova, apresentado na Sprint 3.

**Login e cadastro.** Desenvolvi o sistema de login e cadastro com autenticação JWT, inicialmente em modal e depois em página independente, em parceria com a colega Bruna Matsunaga, além da integração do login à página inicial.

**Fluxo de planos e PDF.** Ajustei os dados exibidos após a escolha do plano e implementei a lógica de geração do PDF do diagnóstico enviado por e-mail.

#### Hard Skills
* Design de interfaces e prototipação - Sei fazer com autonomia
* Autenticação com JWT - Sei fazer com ajuda
* Geração de PDF - Sei fazer com ajuda

#### Soft Skills
* Colaboração - Trabalhei em dupla com a Bruna Matsunaga no sistema de login e cadastro, dividindo as tarefas e integrando o código nos commits compartilhados.
* Comunicação - Alinhei com a equipe a identidade visual do site para atender ao perfil audiovisual da Entrenova e expliquei as minhas decisões de design aos colegas.
* Adaptabilidade - Ajustei o design conforme o feedback do cliente.

---

### Em 2026-1

**Projeto: EchoCAD** | Função na equipe: Desenvolvedor

**Empresa parceira.** O Exército, por meio da Guarnição de Caçapava.

**Problema.** A elaboração do memorial de cálculo e das especificações técnicas a partir de plantas CAD é um processo manual, demorado e sujeito a erros de quantificação de materiais.

**Solução.** Desenvolvemos o EchoCAD, um sistema web que extrai as informações de uma planta CAD e gera automaticamente a documentação técnica, com apoio de IA para filtrar os dados por layers e validar cálculos. O sistema entrega o memorial de cálculo e as especificações técnicas conforme as normas ABNT/NBR, em PDF, XLSX e DOCX, além de uma planilha com os gastos de materiais.

**Entregue pela equipe.** Entregamos a geração do memorial de cálculo básico (Sprint 1) e a documentação e exportação de documentos, com login, formulário do projeto, dashboard, histórico e manuais (Sprint 3). A Sprint 2, dedicada ao assistente de IA e às especificações técnicas, consta como não concluída no repositório.

[GIT](https://github.com/EquipeEcho/EchoCAD)

[![Sprint 1](https://img.youtube.com/vi/TYSAJDFz9T0/0.jpg)](https://youtu.be/TYSAJDFz9T0)
[![Sprint 3](https://img.youtube.com/vi/uGvk_viRp7I/maxresdefault.jpg)](https://www.youtube.com/watch?v=uGvk_viRp7I)

#### Tecnologias Utilizadas
* **Python:** linguagem do módulo de leitura e cálculo dos arquivos CAD.
* **ezdxf:** biblioteca para ler os arquivos DXF e acessar layers, linhas e blocos.
* **JSON:** formato de saída dos materiais extraídos, usado pelo restante do sistema.
* **React, TypeScript, JavaScript e Node.js:** interface e back-end do sistema.
* **MySQL:** armazenamento dos dados e dos documentos gerados.
* **Ollama:** IA para filtrar os dados extraídos da planta.
* **Jira, Notion e GitHub:** gestão das sprints, documentação e versionamento.

#### Contribuições Pessoais
Desenvolvi o módulo que lê os arquivos DXF do AutoCAD, em Python com a biblioteca ezdxf, e transcreve os materiais do projeto em formato JSON, organizado por categorias como alvenaria e hidráulica. A identificação dos itens é feita pelos layers do desenho. Os quantitativos são calculados a partir do comprimento das linhas (como paredes e tubulações) e, para os elementos em bloco, a partir da altura e da distância, estimando a quantidade média de material necessária, como os tijolos. Para o concreto, desenvolvi uma fórmula de estimativa simplificada, que pode ser calibrada com normas técnicas em trabalhos futuros.

O principal desafio foi construir um sistema capaz de interpretar o DXF e distinguir cada elemento do projeto, como uma parede, uma janela ou uma tubulação de 3/4", para associá-lo ao material correto.

#### Hard Skills
* Python - Sei fazer e posso ensinar
* ezdxf e leitura de arquivos DXF - Sei fazer com ajuda
* Modelagem de dados em JSON e cálculo de quantitativos de materiais - Sei fazer com ajuda

#### Soft Skills
* Resiliência - A interpretação dos arquivos DXF exigiu várias abordagens até o sistema identificar corretamente cada item do projeto, e segui o prazo das sprints mesmo com um problema técnico difícil.
* Pensamento crítico - Reconheci a limitação da fórmula do concreto e a registrei como ponto de melhoria, em vez de apresentá-la como definitiva.
* Comunicação - Alinhei com a equipe o formato do JSON usado pelo restante do sistema.
