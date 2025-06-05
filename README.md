## Projeto My Pet

### Descrição

**O Projeto My Pet é uma plataforma completa para gerenciamento de informações e serviços relacionados a animais de estimação. Ele abrange desde o registro de animais e seus tutores até o agendamento de serviços veterinários e acompanhamento de saúde. O sistema visa facilitar a vida dos donos de pets, clínicas veterinárias e outros profissionais do setor, oferecendo uma solução centralizada e eficiente.**

**O projeto será desenvolvido pela ****ArtCodeS** e terá como foco o desenvolvimento do código e da infraestrutura da plataforma. A **MyPet** será a marca e o nome do projeto, responsável pelo marketing, identidade visual e experiência do usuário. A ArtCodeS será mencionada no rodapé do site, juntamente com a IA, como desenvolvedora da plataforma.

### Funcionalidades Principais

* **Registro de animais e tutores**
* **Agendamento de consultas e serviços veterinários**
* **Histórico de saúde dos animais**
* **Controle de vacinação e vermifugação**
* **Gestão de estoque de produtos e medicamentos**
* **Emissão de relatórios e estatísticas**
* **Comunicação entre clínicas, veterinários e tutores**
* **Plataforma de e-commerce para produtos pet (futuro)**
* **Integração com serviços de telemedicina (futuro)**
* **Acompanhamento nutricional e de bem-estar (futuro)**

### Tecnologias Utilizadas

* **Frontend:** React, Vite, TypeScript, MAUI Blazor
* **Backend:** C# API (.NET 9 Core)
* **Banco de Dados:** A definir (SQL Server, PostgreSQL, MongoDB)
* **Mobile:** MAUI Blazor (multiplataforma iOS, Android, Windows, macOS)
* **IoT:** Raspberry Pi 3 (para projetos especiais de monitoramento e automação)
* **Documentação:** Markdown, Swagger/OpenAPI

### Estrutura do Projeto

**Para melhor organização e para garantir a independência e os direitos de cada parte, propomos a seguinte estrutura de pastas:**

```
ArtCodeS/ # Raiz do projeto, contendo o desenvolvimento da plataforma
├── MyPet/ # Pasta específica da MyPet, focada em marketing e identidade visual
│   ├── design/ # Arquivos de design, logos, identidade visual
│   │   ├── logo/
│   │   ├── brandbook/
│   │   └── ...
│   ├── marketing/ # Materiais de marketing, campanhas, etc.
│   │   ├── social_media/
│   │   ├── advertising/
│   │   └── ...
│   ├── docs/ # Documentação específica da MyPet
│   └── ...
├── src/ # Código-fonte da plataforma (React, C#, etc.)
│   ├── client/ # Frontend
│   │   ├── src/
│   │   ├── public/
│   │   └── ...
│   ├── server/ # Backend
│   │   ├── Controllers/
│   │   ├── Models/
│   │   └── ...
│   ├── shared/ # Código compartilhado
│   └── ...
├── maui/ # Aplicação MAUI Blazor (se aplicável)
├── raspberrypi/ # Projetos Raspberry Pi (se aplicável)
└── docs/ # Documentação geral do projeto


```

### Projetos Legados e Backups

**Para garantir a acessibilidade e a organização, projetos mais antigos ou históricos relacionados ao projeto My Pet, se necessário para revisão ou consulta, podem ser encontrados e abertos no ****Google** Drive do ** projeto geral** **. Esta prática é fundamental e oferece os seguintes benefícios:**

* **Acesso Simplificado:** Facilita a localização e o acesso a bases de código anteriores, mesmo que não estejam ativamente no repositório principal.
* **Experiência Agradável:** Uma organização clara e backups confiáveis transformam a experiência de lidar com legados em algo mais eficiente e menos frustrante.
* **Backup Confiável:** Garante que o histórico de desenvolvimento esteja seguro e acessível, protegendo contra perdas de dados.
* **Otimização do Repositório:** Mantém o repositório principal do Git focado apenas no código ativo e relevante, evitando o inchaço com arquivos grandes ou históricos desnecessários para o dia a dia.

### Tarefas Atuais

1. **Definir o banco de dados:** Escolher e configurar o banco de dados (SQL Server, PostgreSQL, MongoDB ou outro).
2. **Implementar a API:** Desenvolver os controllers, models e serviços da API C# para as funcionalidades principais (CRUD de animais, tutores, consultas, etc.).
3. **Desenvolver o Frontend:** Criar as páginas e componentes do React para a interface do usuário, consumindo a API desenvolvida.
4. **Implementar o Mobile (MAUI Blazor):** Desenvolver o aplicativo mobile para iOS, Android, Windows e macOS, utilizando o MAUI Blazor.
   * **Sugestão:** Iniciar com uma página de currículos/resume, utilizando Bootstrap 5.3.x para estruturação e estilização.
5. **Projetos IoT (Raspberry Pi):** Iniciar o desenvolvimento de projetos de IoT com o Raspberry Pi 3, como monitoramento de saúde animal ou automação de clínicas.
6. **Documentação:** Manter a documentação atualizada em cada pasta (client/docs, server/docs, maui/docs, raspberrypi/docs), seguindo os padrões definidos.
7. **Testes:** Implementar testes unitários para o Backend (C# API).
8. **Deploy:** Configurar o deploy da aplicação para um ambiente de produção.
9. **Reuniões:** Realizar reuniões periódicas para alinhamento da equipe e acompanhamento do projeto.
10. **Blog:** Criar conteúdo para o blog do projeto ( **MyPet Blog** **), documentando o desenvolvimento, as tecnologias utilizadas e os desafios encontrados.**
11. **Currículo:** Atualizar o currículo com as tecnologias e experiências do projeto.
12. **Protótipo de Frontend (Sara):** Desenvolver um protótipo de frontend utilizando Bootstrap 5.3.x, com os componentes listados abaixo e integrando os endpoints da API C# desenvolvida por Eduardo.
    * **Navbar**
    * **Carousel**
    * **Cards**
    * **Formulários**
    * **Tabelas**
    * **Botões**
    * **Modais**
    * **Paginação**
    * **Alertas**
    * **Tooltip**
    * **Popovers**
    * **Toast**
    * **Upload de arquivos**
    * **Gráficos**
    * **Calendário**
    * **Timeline**
    * **Chat**
    * **Google Maps**
    * **Integração de todos os endpoints da API C#**
13. **Posicionamento da Marca:** Definir o posicionamento da marca ArtCodeS e MyPet no site.
    * ArtCodeS será mencionada no rodapé do site, juntamente com a IA, como desenvolvedora da plataforma.
    * MyPet será a marca principal, com destaque no conteúdo e design do site.

### Próximos Passos

* **Definir o escopo detalhado de cada funcionalidade.**
* **Distribuir as tarefas entre os membros da equipe.**
* **Criar um cronograma de desenvolvimento.**
* **Configurar o ambiente de desenvolvimento (banco de dados, servidores, etc.).**
* **Começar o desenvolvimento do Backend e Frontend em paralelo.**
* **Documentar cada etapa do desenvolvimento.**
* **Implementar scripts C# para automatizar tarefas de configuração e deploy, facilitando o uso da estrutura de pastas definida.**

### Sugestões de Scripts C# para Automatização

**Para auxiliar na implementação da estrutura de pastas e automatizar tarefas comuns, o Eduardo pode criar alguns scripts C#. Seguem algumas sugestões:**

#### 1. Criação de Pastas Iniciais

* **Descrição:** Este script cria a estrutura de pastas inicial do projeto, conforme definido na seção "Estrutura do Projeto".
* **Funcionalidade:** O script recebe o caminho da pasta raiz do projeto como argumento e cria as pastas `<span class="selected">ArtCodeS</span>`, `<span class="selected">MyPet</span>`, `<span class="selected">src</span>`, `<span class="selected">maui</span>`, `<span class="selected">raspberrypi</span>` e `<span class="selected">docs</span>` dentro dela. Em seguida, cria as subpastas necessárias dentro de cada uma.
* **Exemplo de uso:**
  ```
  dotnet run --project CriarPastas.csproj -- "/caminho/para/a/pasta/raiz"

  ```
* **Código C#:**
  ```
  using System;
  using System.IO;

  public class CriarPastas
  {
      public static void Main(string[] args)
      {
          if (args.Length != 1)
          {
              Console.WriteLine("Uso: dotnet run --project CriarPastas.csproj -- <caminho_da_pasta_raiz>");
              return;
          }

          string pastaRaiz = args[0];

          CriarPastaSeNaoExiste(pastaRaiz, "ArtCodeS");
          CriarPastaSeNaoExiste(pastaRaiz + "/ArtCodeS", "MyPet");
          CriarPastaSeNaoExiste(pastaRaiz + "/ArtCodeS/MyPet", "design");
          CriarPastaSeNaoExiste(pastaRaiz + "/ArtCodeS/MyPet", "marketing");
          CriarPastaSeNaoExiste(pastaRaiz + "/ArtCodeS/MyPet", "docs");
          CriarPastaSeNaoExiste(pastaRaiz + "/ArtCodeS", "src");
          CriarPastaSeNaoExiste(pastaRaiz + "/ArtCodeS/src", "client");
          CriarPastaSeNaoExiste(pastaRaiz + "/ArtCodeS/src", "server");
          CriarPastaSeNaoExiste(pastaRaiz + "/ArtCodeS/src", "shared");
          CriarPastaSeNaoExiste(pastaRaiz, "maui");
          CriarPastaSeNaoExiste(pastaRaiz, "raspberrypi");
          CriarPastaSeNaoExiste(pastaRaiz, "docs");

          Console.WriteLine("Estrutura de pastas criada com sucesso!");
      }

      private static void CriarPastaSeNaoExiste(string caminhoPai, string nomePasta)
      {
          string caminhoCompleto = Path.Combine(caminhoPai, nomePasta);
          if (!Directory.Exists(caminhoCompleto))
          {
              Directory.CreateDirectory(caminhoCompleto);
              Console.WriteLine($"Pasta criada: {caminhoCompleto}");
          }
          else
          {
              Console.WriteLine($"Pasta já existe: {caminhoCompleto}");
          }
      }
  }


  ```

#### 2. Criação de Arquivos de Documentação Padrão

* **Descrição:** Este script cria os arquivos de documentação padrão (README.md, geral.md, etc.) dentro das pastas do projeto.
* **Funcionalidade:** O script recebe o caminho da pasta raiz do projeto como argumento e cria os arquivos padrão em cada pasta, com conteúdo inicial (títulos, cabeçalhos, etc.).
* **Exemplo de uso:**
  ```
  dotnet run --project CriarDocumentos.csproj -- "/caminho/para/a/pasta/raiz"


  ```
* **Código C#:**
  ```
  using System;
  using System.IO;

  public class CriarDocumentos
  {
      public static void Main(string[] args)
      {
          if (args.Length != 1)
          {
              Console.WriteLine("Uso: dotnet run --project CriarDocumentos.csproj -- <caminho_da_pasta_raiz>");
              return;
          }

          string pastaRaiz = args[0];

          CriarDocumentoSeNaoExiste(pastaRaiz, "README.md", "# Projeto My Pet\n\nDocumentação geral do projeto.");
          CriarDocumentoSeNaoExiste(pastaRaiz + "/ArtCodeS/MyPet", "README.md", "# MyPet\n\nDocumentação específica da MyPet.");
          CriarDocumentoSeNaoExiste(pastaRaiz + "/ArtCodeS/MyPet/docs", "geral.md", "# Documentação Geral da MyPet\n\n");
          CriarDocumentoSeNaoExiste(pastaRaiz + "/ArtCodeS/MyPet/design", "README.md", "# Design\n\nDocumentação da parte de Design.");
          CriarDocumentoSeNaoExiste(pastaRaiz + "/ArtCodeS/MyPet/marketing", "README.md", "# Marketing\n\nDocumentação da parte de Marketing.");
          CriarDocumentoSeNaoExiste(pastaRaiz + "/ArtCodeS/src/client/docs", "geral.md", "# Frontend\n\nDocumentação Geral do Frontend.");
          CriarDocumentoSeNaoExiste(pastaRaiz + "/ArtCodeS/src/client/docs", "componentes.md", "# Componentes do Frontend\n\n");
          CriarDocumentoSeNaoExiste(pastaRaiz + "/ArtCodeS/src/client/docs", "api.md", "# API do Frontend\n\nDocumentação da API consumida pelo Frontend.");
          CriarDocumentoSeNaoExiste(pastaRaiz + "/ArtCodeS/src/server/docs", "geral.md", "# Backend\n\nDocumentação Geral do Backend.");
          CriarDocumentoSeNaoExiste(pastaRaiz + "/ArtCodeS/src/server/docs", "controllers.md", "# Controllers do Backend\n\n");
          CriarDocumentoSeNaoExiste(pastaRaiz + "/ArtCodeS/src/server/docs", "models.md", "# Models do Backend\n\n");
          CriarDocumentoSeNaoExiste(pastaRaiz + "/ArtCodeS/src", "README.md", "# Código Fonte\n\nDocumentação do código fonte.");
          CriarDocumentoSeNaoExiste(pastaRaiz + "/ArtCodeS/src/client", "README.md", "# Frontend\n\nDocumentação do código fonte do Frontend.");
          CriarDocumentoSeNaoExiste(pastaRaiz + "/ArtCodeS/src/server", "README.md", "# Backend\n\nDocumentação do código fonte do Backend.");
          CriarDocumentoSeNaoExiste(pastaRaiz + "/maui", "README.md", "# MAUI Blazor\n\nDocumentação da aplicação MAUI Blazor.");
          CriarDocumentoSeNaoExiste(pastaRaiz + "/maui/docs", "geral.md", "# MAUI Blazor\n\nDocumentação geral da aplicação MAUI Blazor.");
          CriarDocumentoSeNaoExiste(pastaRaiz + "/raspberrypi", "README.md", "# Raspberry Pi\n\nDocumentação dos projetos Raspberry Pi.");
          CriarDocumentoSeNaoExiste(pastaRaiz + "/raspberrypi/docs", "geral.md", "# Raspberry Pi\n\nDocumentação geral dos projetos.");

          Console.WriteLine("Arquivos de documentação criados com sucesso!");
      }

      private static void CriarDocumentoSeNaoExiste(string caminhoPasta, string nomeArquivo, string conteudo)
      {
          string caminhoCompleto = Path.Combine(caminhoPasta, nomeArquivo);
          if (!File.Exists(caminhoCompleto))
          {
              File.WriteAllText(caminhoCompleto, conteudo);
              Console.WriteLine($"Arquivo criado: {caminhoCompleto}");
          }
          else
          {
              Console.WriteLine($"Arquivo já existe: {caminhoCompleto}");
          }
      }
  }


  ```

#### 3. Script de Deploy para Produção

* **Descrição:** Este script automatiza o processo de deploy da aplicação para um ambiente de produção.
* **Funcionalidade:** O script recebe o tipo de deploy (web, mobile) e o ambiente de destino (produção, staging) como argumentos. Em seguida, executa os passos necessários para compilar a aplicação, copiar os arquivos para o servidor de produção e reiniciar o serviço.
* **Exemplo de uso:**
  ```
  dotnet run --project DeployApp.csproj -- web production
  dotnet run --project DeployApp.csproj -- mobile staging


  ```
* **Código C#:**
  ```
  using System;
  using System.Diagnostics;
  using System.IO;

  public class DeployApp
  {
      public static void Main(string[] args)
      {
          if (args.Length != 2)
          {
              Console.WriteLine("Uso: dotnet run --project DeployApp.csproj -- <tipo_deploy (web, mobile)> <ambiente (producao, staging)>");
              return;
          }

          string tipoDeploy = args[0];
          string ambiente = args[1];

          Console.WriteLine($"Iniciando deploy da aplicação {tipoDeploy} para o ambiente {ambiente}...");

          // 1.  Compilar a aplicação
          Console.WriteLine("Compilando a aplicação...");
          Process processoCompilacao = new Process();
          processoCompilacao.StartInfo.FileName = "dotnet"; // Ou o comando para o seu sistema de build
          processoCompilacao.StartInfo.Arguments = "build --configuration Release"; // Ajuste conforme necessário
          processoCompilacao.StartInfo.UseShellExecute = false;
          processoCompilacao.StartInfo.RedirectStandardOutput = true;
          processoCompilacao.StartInfo.RedirectStandardError = true;
          processoCompilacao.Start();
          processoCompilacao.WaitForExit();

          if (processoCompilacao.ExitCode != 0)
          {
              Console.WriteLine("Erro ao compilar a aplicação:");
              Console.WriteLine(processoCompilacao.StandardError.ReadToEnd());
              return;
          }

          Console.WriteLine(processoCompilacao.StandardOutput.ReadToEnd());
          Console.WriteLine("Aplicação compilada com sucesso!");

          // 2.  Copiar os arquivos para o servidor de produção
          Console.WriteLine("Copiando arquivos para o servidor de produção...");
          // Aqui você usaria comandos como scp, rsync, ou ferramentas de deploy específicas da sua infraestrutura
          // Exemplo (usando um comando fictício 'deploy'):
          string comandoDeploy = $"deploy --tipo={tipoDeploy} --ambiente={ambiente} --origem=./bin/Release --destino=/var/www/mypet";
          Process processoDeploy = new Process();
          processoDeploy.StartInfo.FileName = "/bin/bash";  // Ou o shell que você usa
          processoDeploy.StartInfo.Arguments = $"-c \"{comandoDeploy}\"";
          processoDeploy.StartInfo.UseShellExecute = false;
          processoDeploy.StartInfo.RedirectStandardOutput = true;
          processoDeploy.StartInfo.RedirectStandardError = true;
          processoDeploy.Start();
          processoDeploy.WaitForExit();

          if (processoDeploy.ExitCode != 0)
          {
              Console.WriteLine("Erro ao copiar arquivos para o servidor:");
              Console.WriteLine(processoDeploy.StandardError.ReadToEnd());
              return;
          }

          Console.WriteLine(processoDeploy.StandardOutput.ReadToEnd());
          Console.WriteLine("Arquivos copiados com sucesso!");

          // 3.  Reiniciar o serviço da aplicação
          Console.WriteLine("Reiniciando o serviço da aplicação...");
          // Aqui você usaria comandos como systemctl restart, service restart, ou comandos específicos do seu servidor web
          // Exemplo (usando systemctl):
          Process processoRestart = new Process();
          processoRestart.StartInfo.FileName = "sudo"; // Se precisar de privilégios
          processoRestart.StartInfo.Arguments = $"systemctl restart mypet-{tipoDeploy}.service";
          processoRestart.StartInfo.UseShellExecute = false;
          processoRestart.StartInfo.RedirectStandardOutput = true;
          processoRestart.Start();
          processoRestart.WaitForExit();

          if (processoRestart.ExitCode != 0)
          {
              Console.WriteLine("Erro ao reiniciar o serviço:");
              Console.WriteLine(processoRestart.StandardError.ReadToEnd());
              return;
          }

          Console.WriteLine(processoRestart.StandardOutput.ReadToEnd());
          Console.WriteLine("Serviço reiniciado com sucesso!");

          Console.WriteLine("Deploy concluído com sucesso!");
      }
  }


  ```

### Contribuição

**Contribuições são bem-vindas! Se você tiver alguma sugestão, encontrar algum problema ou quiser ajudar no desenvolvimento, sinta-se à vontade para abrir uma issue ou enviar um pull request.**

## Estrutura de Menus do Blog Diário

**A tabela abaixo detalha a estrutura de menus proposta para o blog diário, considerando a organização do projeto ArtCodeS e MyPet.**

| **Menu Principal** | **Submenu**       | **Tipo de Página** | **Tecnologias** | **Descrição**                                                                 |
| ------------------------ | ----------------------- | ------------------------- | --------------------- | ------------------------------------------------------------------------------------- |
| **ArtCodeS**       | **Institucional** | **Estática**       | **HTML**        | **Página sobre a empresa ArtCodeS, sua história, missão, visão e valores.** |

**|**
