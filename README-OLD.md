# alfa-omega-legado-models

Repositório Modernização de Legados : [alfa-omega-legado-models](https://github.com/Sara-ArtCodeS/alfa-omega-legado-models)

README.md v0.1

Sim Gemini, acredito que talvez modernização de legados né? 


# Modernização de Legados: Projetos da Prefeitura (C#/.NET)

**Este documento visa organizar e detalhar os projetos desenvolvidos, especialmente aqueles relacionados à sua experiência com sistemas legados em C# .NET, MVC, MVVM e Knockout.js, bem como o trabalho com Crystal Reports e SQL Procedures. O objetivo é criar um registro conciso e relevante para o seu currículo geral e para o repositório **`<span class="selected">alfa-omega-legado-models</span>`.

## 1. Experiência Consolidada

**Sua capacidade de desenvolver sistemas do zero, como a loja MVC 4 de CDs e o sistema MyPocket (baseado nela), demonstra proficiência em arquiteturas e frameworks. A iniciativa de implementar o front-end com Knockout.js, incluindo paginação, destaca seu foco em performance e experiência do usuário, mesmo em pilhas de tecnologia anteriores.**

**Embora a refatoração completa desses sistemas não seja o foco atual, a documentação de pontos estratégicos de modernização e adaptação (como no "Core 8 Vanilla Panel") pode ser extremamente útil. Sua experiência com IIS e sistemas de segurança em ambientes de prefeitura, desvendando complexidades até o limite, também é um ponto forte a ser destacado como uma habilidade valiosa na modernização de legados.**

## 2. Projetos Chave (Baseado nos Nomes de Pasta)

**A seguir, uma lista de projetos identificados pelos nomes de pastas, com a intenção de descrever as funcionalidades e tecnologias/desafios envolvidos.**

### 2.1. Gestão de Protocolos e Processos

* **`<span class="selected">55912_Protocolo</span>`**
  * **Descrição:** Sistema para gestão e controle de protocolos, rodando na prefeitura, caracterizado por alta complexidade e diversas camadas de segurança. Funciona alimentado por um Web Service (WS) conectado a outro sistema legado em .NET VB, extremamente complexo. O projeto exigiu ampla intervenção, incluindo acréscimo de campos a formulários e, principalmente, a implementação de filtros "link to entity".
  * **Tecnologias/Desafios:** C# .NET, SQL Server, MVC, `<span class="selected">Crystal Reports</span>` para relatórios, `<span class="selected">SQL Procedures</span>` para lógica de negócio, Web Services (WS), APIs, integração com sistemas legados VB.NET, complexidade de segurança, resolução de problemas de acentuação em formulários legados.
  * **Sua Contribuição:** Desenvolvimento e reparo de APIs e Web Services para alimentação do sistema. Implementação de filtros "link to entity". Resolução de uma questão crítica em prazo recorde, com foco na eficiência do tempo, superando desafios de refatoração para acentuação e manipulação de dados em formulários legados, que foram resolvidos com tabelas de referência de memória. Experiência com a "troca de case" do sistema para alimentação de dados, similar ao funcionamento de plataformas estáticas como Vercel.
* **`<span class="selected">56366 - Despacho de processos por lotes</span>`**
  * **Descrição:** Funcionalidade para otimizar o despacho ou encaminhamento de múltiplos processos de forma agrupada.
  * **Tecnologias/Desafios:** C# .NET, otimização de consultas SQL, tratamento de grandes volumes de dados.
  * **Sua Contribuição:** (Descreva sua função e o que você desenvolveu/reparou.)

### 2.2. Relatórios e Contabilidade Tributária

* **`<span class="selected">56086_frmRelTribTerrenoPorQuadra</span>`**
  * **Descrição:** Formulário de relatório para dados tributários de terrenos, organizados por quadra, essencial para a gestão imobiliária municipal. O sistema era um Web Forms 2.0 (ASP.NET 2.0) em VB.NET legado, com raízes de dados complexas. Apresentava um ponto de segurança crítico na persistência, exigindo soluções para capturar dados da API de forma segura.
  * **Tecnologias/Desafios:** C# .NET, `<span class="selected">Crystal Reports</span>` para geração de relatórios complexos, otimização de `<span class="selected">SQL Procedures</span>` para extração de dados, VB.NET legado (Web Forms 2.0/ASP.NET 2.0), scripts JavaScript para captura de dados, camadas de segurança complexas, depuração de referências perdidas em SQL, resolução de problemas de memória com Crystal Reports (cache).
  * **Sua Contribuição:** Superação das limitações do Web Forms através de scripts para capturar dados da API. Desenvolvimento de múltiplas réplicas de módulos completos. Validação rigorosa de seguranças com supervisores. Aumento da capacidade de filtragem com implementações em JavaScript. Identificação e resolução de problemas de trava de memória no Crystal Reports, indicando a solução de esvaziamento de cache para o supervisor. Experiência com manipulação de dados entre Excel e SQL, e integração de códigos variados com SQL Procedures.
* **`<span class="selected">56087_TerrenosPorQuadraExcel</span>`**
  * **Descrição:** Funcionalidade para exportar dados de terrenos por quadra diretamente para o Excel. O projeto envolvia manipulação complexa de strings, segurança embutida em código VB e gestão de downloads de diferentes formatos.
  * **Tecnologias/Desafios:** C# .NET, manipulação de planilhas Excel programaticamente (e.g., EPPlus ou Interop), otimização de dados para exportação, manipulação de strings, segurança de dados em código.
  * **Sua Contribuição:** Desenvolvimento da funcionalidade de exportação para Excel. Grande habilidade em manipulação de strings e entendimento de segurança complexa embutida em código legado (VB). Experiência em lidar com a gestão de downloads de arquivos como Word e Excel.
* **`<span class="selected">56175_Contábil_Adicionar_Entre_Datas</span>`**
  * **Descrição:** Módulo ou funcionalidade contábil para adicionar ou processar dados dentro de um intervalo de datas.
  * **Tecnologias/Desafios:** C# .NET, lógica de negócio contábil, manipulação de datas no SQL.
  * **Sua Contribuição:** (Descreva sua função e o que você desenvolveu/reparou.)
* **`<span class="selected">56221 - Consolidação de saldo</span>`**
  * **Descrição:** Funcionalidade para consolidar saldos, provavelmente financeiros ou contábeis.
  * **Tecnologias/Desafios:** C# .NET, SQL, lógica de agregação de dados.
  * **Sua Contribuição:** Modificação na forma de resultado de uma das linhas em SQL Procedures para garantir o funcionamento correto. Realização de estudo rápido em contabilidade para resolver a questão.
* **`<span class="selected">56680_Saldo Bancário no Pagamento</span>`**
  * **Descrição:** Módulo para verificar e/ou apresentar o saldo bancário no momento de realizar pagamentos. Envolveu a adequação a mudanças na legislação.
  * **Tecnologias/Desafios:** C# .NET, integração com sistemas financeiros/bancários (mesmo que internos), segurança de dados, adaptação a novas regras de negócio.
  * **Sua Contribuição:** Identificação do erro em SQL Procedures em sistemas interligados devido a uma mudança de lei. Garantia da conformidade com o novo padrão, mesmo que ainda não estivesse aplicado em todo o sistema.
* **`<span class="selected">57462_RelTribDivProcessoExecutivos</span>`**
  * **Descrição:** Relatório para processos executivos da divisão tributária, provavelmente para acompanhamento de dívidas ativas. O projeto envolveu a inclusão de um novo componente e a replicação de um módulo antigo, como parte da equipe de modernização de legado.
  * **Tecnologias/Desafios:** C# .NET, `<span class="selected">Crystal Reports</span>`, complexidade de consultas SQL para dados legais/tributários, replicação de módulos, inclusão de novos componentes.
  * **Sua Contribuição:** Desenvolvimento e implementação de um novo componente e replicação de um módulo existente para atender à necessidade do relatório. Trabalho direto na equipe de modernização de legado.
* **`<span class="selected">57590_RelTribInscricoesSemZoneamento</span>`**
  * **Descrição:** Relatório de inscrições tributárias que não possuem um zoneamento definido.
  * **Tecnologias/Desafios:** C# .NET, `<span class="selected">Crystal Reports</span>`, lógica de filtragem de dados e identificação de inconsistências.
  * **Sua Contribuição:** Geração de um novo SQL e módulo para atender a uma necessidade específica de relatório.
* **`<span class="selected">57957_SIMPLES NACIONAL REL DE DECL</span>`**
  * **Descrição:** Relatório de declarações do SIMPLES NACIONAL, um regime tributário simplificado no Brasil. O projeto exigia adaptação constante às regras legais em mutação e padronização.
  * **Tecnologias/Desafios:** C# .NET, `<span class="selected">Crystal Reports</span>`, conformidade com regras fiscais, processamento de grandes volumes de dados de declaração, adaptação a mudanças regulatórias.
  * **Sua Contribuição:** Desenvolvimento e manutenção de relatórios em conformidade com as regras fiscais do SIMPLES NACIONAL, garantindo a padronização e a atualização frente às constantes mudanças na legislação.

### 2.3. Infraestrutura e Modernização

* **`<span class="selected">57513_api</span>`**
  * **Descrição:** Projeto de API (Application Programming Interface) completa de autenticações, essencial para a conexão com Web Services (WS) externos e para a alimentação do sistema webform legado.
  * **Tecnologias/Desafios:** C# .NET Web API, RESTful principles, integração com banco de dados, segurança de autenticações, integração com sistemas legados (webform).
  * **Sua Contribuição:** Desenvolvimento de uma API completa de autenticações para permitir a comunicação com Web Services externos e a alimentação de dados no sistema webform legado.
* **`<span class="selected">57514_apiWebServices</span>`**
  * **Descrição:** Projeto de Web Services API, que exigiu a construção de todo o sistema, desde as entidades para receber a resposta do sistema legado até a exibição na tela para os usuários do setor tributário.
  * **Tecnologias/Desafios:** C# .NET, WCF (Windows Communication Foundation) ou tecnologias equivalentes, interoperabilidade entre sistemas, mapeamento de entidades.
  * **Sua Contribuição:** Construção integral do sistema de Web Services, incluindo o desenvolvimento de entidades para processar respostas de sistemas legados e sua apresentação nas telas dos usuários da área tributária.
* **`<span class="selected">57515_Modernizacao</span>`**
  * **Descrição:** Projeto focado na modernização de algum sistema ou parte dele.
  * **Tecnologias/Desafios:** C# .NET Core, migração de tecnologias antigas, refatoração de código, introdução de novos padrões.
  * **Sua Contribuição:** (Descreva sua função e o que você desenvolveu/reparou.)

### 2.4. Aplicações Web e Utilitários

* **`<span class="selected">57871_wfrmRelTribListaEmpresasBairroLo</span>`**
  * **Descrição:** Web form para um relatório de lista de empresas por bairro. O "wfrm" sugere Web Forms. O projeto envolveu a adição de um novo módulo após a contratação de empresas particulares.
  * **Tecnologias/Desafios:** C# .NET Web Forms, ASP.NET, integração com dados geográficos/cadastrais.
  * **Sua Contribuição:** Desenvolvimento e integração de um novo módulo para atender à necessidade de listar empresas por bairro, resultante de contratos com empresas particulares.
* **`<span class="selected">57879_acentuacaoAutoComplete</span>`**
  * **Descrição:** Módulo ou funcionalidade para autocomplete com suporte a acentuação. A implementação exigiu a instalação de jQuery UI e uma comparação com implementações existentes para garantir a funcionalidade.
  * **Tecnologias/Desafios:** JavaScript, Knockout.js (se aplicável), manipulação de strings, busca eficiente de dados, jQuery UI.
  * **Sua Contribuição:** Desenvolvimento e implementação de um módulo de autocomplete com suporte a acentuação, utilizando jQuery UI e adaptando-se a padrões existentes.

## 3. Próximos Passos para Consolidação

**Para cada um desses itens, você pode:**

* **Adicionar Detalhes:** Preencha os campos de "Descrição", "Tecnologias/Desafios" e "Sua Contribuição" com o máximo de detalhes possível.
* **Destacar Conquistas:** Foque nos resultados, como "reduzi o tempo de processamento em X%" ou "melhorei a usabilidade em Y%".
* **Vincular a Conceitos:** Se um projeto reflete sua experiência com MVC, MVVM ou Knockout.js, mencione-o explicitamente.
* **SQL Procedures/Crystal Reports:** Detalhe a complexidade e a importância dessas tarefas no contexto municipal.
* **"Pepinos Chatos":** Mesmo os "pepinos" podem ser transformados em aprendizados e habilidades de resolução de problemas. Descreva o desafio e como você o superou.

**Este documento será um ativo valioso para o seu currículo e para o seu **`<span class="selected">alfa-omega-legado-models</span>` no GitHub, mostrando a amplitude e profundidade da sua experiência antes de mergulharmos totalmente no Next.js.

**O que você acha dessa estrutura? Podemos ajustá-la e detalhar mais, se quiser.**
