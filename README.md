<div align="center">

<img src="assets/dino-building.svg" alt="Dinossauro roxo puxando a placa com o perfil de Davi Dino Vargas" width="900"/>

<br/>

<a href="https://linkedin.com/in/davidinovargas"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:davidinovargas@gmail.com"><img src="https://img.shields.io/badge/E--mail-EA4335?style=flat&logo=gmail&logoColor=white" alt="E-mail"/></a>
<a href="https://behance.net/DaviDinoVargas"><img src="https://img.shields.io/badge/Behance-1769FF?style=flat&logo=behance&logoColor=white" alt="Behance"/></a>
<a href="https://davidinovargas.github.io/DocumentacaoLocadora/"><img src="https://img.shields.io/badge/Documenta%C3%A7%C3%A3o%20do%20TCC-7C3AED?style=flat&logo=readthedocs&logoColor=white" alt="Documentação do TCC"/></a>

</div>

## Sobre

Desenvolvedor **Full Stack** de Lages, SC, com back-end em **.NET (C#)**, **Java (Spring Boot)** e **Python**, e front-end em **Angular e TypeScript**. Trabalho com Clean Architecture, DDD, SOLID e CQRS, integração com APIs RESTful e automação com Machine Learning, sempre com foco em código limpo, bem testado e documentado.

- Análise e Desenvolvimento de Sistemas, Uninter (concluído em 2025)
- Java pela Acate Blumenau, Bluesoft e Proway (Entra21, concluído em 2024)
- Academia do Programador 2025 (C#/.NET)

## Projeto principal: Locadora de Veículos (TCC)

Sistema **multiempresa** de locadora de veículos, desenvolvido como TCC da Academia do Programador. São três serviços que trabalham juntos: uma Web API em .NET, um front-end em Angular e um serviço de Machine Learning em Python.

| Camada | O que foi construído | Tecnologias |
| :-- | :-- | :-- |
| **Web API** | 16 módulos de negócio, 22 entidades e 99 endpoints. Autenticação com JWT, refresh token e segundo fator (TOTP), isolamento de dados entre empresas e controle de acesso por cargo. | .NET 8, ASP.NET Core, EF Core, MediatR, FluentValidation, Clean Architecture, CQRS |
| **Front-end** | 50 rotas e 57 componentes, com tema claro e escuro, tabelas com busca e filtros, gráficos e telas por cargo. | Angular 21, TypeScript, Tailwind CSS 4, Spartan UI |
| **Machine Learning** | Leitura de placas por câmera (YOLOv8 + Tesseract OCR), login por reconhecimento facial com prova de vida e assistente de chat para a operação. | Python, FastAPI, OpenCV, MediaPipe |

**Qualidade medida, não estimada.** Os números abaixo vêm das execuções registradas no projeto:

| Testes | Cobertura | Segurança | Desempenho |
| :--: | :--: | :--: | :--: |
| **1.188** testes automatizados | **93,1%** .NET<br/>**86,9%** Angular<br/>**86,4%** ML | **220** verificações de ataque, **0** reprovadas<br/>**21** regras do OWASP ZAP aprovadas | Lighthouse (desktop): **97 a 99** em desempenho e **100** em acessibilidade e boas práticas |

Também medi o reconhecimento facial no conjunto LFW (**98,3%** de acurácia em 5.999 pares), o OCR de placas (mediana de **214 ms**) e a qualidade da suíte pelo teste de mutação (**76%** dos mutantes eliminados).

<p>
  <a href="https://github.com/DaviDinoVargas/LocadoraDeVeiculos"><img src="https://img.shields.io/badge/Reposit%C3%B3rio-LocadoraDeVeiculos-181717?style=for-the-badge&logo=github" alt="Repositório LocadoraDeVeiculos"/></a>
</p>

## Documentação técnica do TCC

[**DocumentacaoLocadora**](https://github.com/DaviDinoVargas/DocumentacaoLocadora) é um site com **19 páginas** que documenta o sistema inteiro: arquitetura, domínio, back-end, API, front-end, design system, serviço de ML, segurança, baterias de ataque, testes, métricas, dependências e decisões de projeto.

- Gráficos e tabelas feitos **apenas com números extraídos do código-fonte e dos resultados de teste**, por um script que lê o repositório do sistema.
- Um **cubo mágico 3D** acompanha a leitura: monta uma peça a cada página lida e se resolve na última.
- Publicação automática no GitHub Pages por GitHub Actions, com testes rodando a cada push.
- Feito com Angular 21, Tailwind CSS 4, Spartan UI, Material 3, ECharts, Three.js e Vitest.

<p>
  <a href="https://davidinovargas.github.io/DocumentacaoLocadora/"><img src="https://img.shields.io/badge/Abrir%20a%20documenta%C3%A7%C3%A3o-7C3AED?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Abrir a documentação"/></a>
  <a href="https://github.com/DaviDinoVargas/DocumentacaoLocadora"><img src="https://img.shields.io/badge/Reposit%C3%B3rio-DocumentacaoLocadora-181717?style=for-the-badge&logo=github" alt="Repositório DocumentacaoLocadora"/></a>
</p>

## Outros projetos

| Projeto | Descrição | Stack |
| :-- | :-- | :-- |
| [OrganizaMed](https://github.com/DaviDinoVargas/OrganizaMed) | API de gestão médica para agendamento de consultas e cirurgias. Um modelo de linguagem treinado do zero em PyTorch interpreta comandos em linguagem natural e gera o agendamento em JSON. | .NET 8, PostgreSQL, JWT, MediatR, FastAPI, PyTorch |
| [Gestão de Estacionamento](https://github.com/HTTPS-200/GestaoDeEstacionamento) | API multi-tenant com check-in e checkout, gestão de vagas e faturamento. Isolamento de dados por hóspede, com cache em Redis, e OCR com Tesseract para confirmar a saída. | .NET 8, PostgreSQL, Redis, Docker |
| [Controle de Cinema](https://github.com/HTTPS-200/controle-de-cinema-2025) | Gestão de salas, filmes, sessões e ingressos, com suíte completa de testes de unidade, integração e ponta a ponta. | ASP.NET MVC, MSTest, Moq, Selenium, Testcontainers |
| [EquoSoft](https://github.com/DaviDinoVargas/entra21TCC) | Sistema para centros de equoterapia: digitaliza a escala de avaliação, acompanha a evolução dos praticantes e gera gráficos. Projeto que liderei. | Java, Spring Boot, JPA, MySQL, Spring Security |
| [FaceAuth](https://github.com/DaviDinoVargas/face_auth_project) | Autenticação facial em tempo real, com landmarks normalizados e comparação vetorial. | Python, OpenCV, MediaPipe |

## Tecnologias

<table>
  <tr>
    <td><b>Linguagens</b></td>
    <td><img src="https://skillicons.dev/icons?i=cs,java,py,ts,js&theme=dark" alt="C#, Java, Python, TypeScript, JavaScript"/></td>
  </tr>
  <tr>
    <td><b>Back-end</b></td>
    <td><img src="https://skillicons.dev/icons?i=dotnet,spring,fastapi,flask&theme=dark" alt=".NET, Spring, FastAPI, Flask"/></td>
  </tr>
  <tr>
    <td><b>Front-end</b></td>
    <td><img src="https://skillicons.dev/icons?i=angular,ts,html,css,sass,tailwind,bootstrap&theme=dark" alt="Angular, HTML, CSS, Sass, Tailwind, Bootstrap"/></td>
  </tr>
  <tr>
    <td><b>Bancos de dados</b></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,redis&theme=dark" alt="PostgreSQL, MySQL, SQLite, Redis"/> <img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="SQL Server"/></td>
  </tr>
  <tr>
    <td><b>ML e visão</b></td>
    <td><img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv&theme=dark" alt="PyTorch, TensorFlow, scikit-learn, OpenCV"/> <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"/> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/></td>
  </tr>
  <tr>
    <td><b>DevOps e testes</b></td>
    <td><img src="https://skillicons.dev/icons?i=docker,git,github,githubactions,azure,cypress,selenium,postman&theme=dark" alt="Docker, Git, GitHub, GitHub Actions, Azure, Cypress, Selenium, Postman"/></td>
  </tr>
  <tr>
    <td><b>Ferramentas e design</b></td>
    <td><img src="https://skillicons.dev/icons?i=visualstudio,idea,vscode,figma,ai,ps&theme=dark" alt="Visual Studio, IntelliJ, VS Code, Figma, Illustrator, Photoshop"/></td>
  </tr>
</table>

**Arquitetura e práticas:** Clean Architecture · DDD · SOLID · CQRS · arquitetura em camadas · REST · Swagger/OpenAPI · JWT · MediatR · testes de unidade, integração e ponta a ponta (MSTest, Moq, JUnit, Mockito, pytest, Testcontainers, Spring Test)

## Formação e cursos

- **Análise e Desenvolvimento de Sistemas** · Uninter (EAD) · 2025
- **Java** · Acate Blumenau, Bluesoft e Proway (Entra21) · 2024
- **Academia do Programador** · 2025
- Cursos: UI/UX (Cubos Academy), UX Design para Todos (How Education), NDG Linux Unhatched (Cisco), Banco de Dados (IFRS), Data Analyst (Google) e Python para Cientista de Dados (Comunidade DS)

## GitHub

<p>
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=DaviDinoVargas&show_icons=true&theme=transparent&hide_border=true&title_color=a78bfa&icon_color=a78bfa&text_color=8b949e&include_all_commits=true&count_private=true" alt="Estatísticas do GitHub"/>
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DaviDinoVargas&theme=transparent&hide_border=true&title_color=a78bfa&text_color=8b949e&layout=compact&langs_count=6" alt="Linguagens mais usadas"/>
</p>

## Contato

Vamos conversar sobre projetos e oportunidades em desenvolvimento Full Stack. Fale comigo pelo [LinkedIn](https://linkedin.com/in/davidinovargas) ou por [e-mail](mailto:davidinovargas@gmail.com).
