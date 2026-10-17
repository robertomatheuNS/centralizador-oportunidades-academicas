# Centralizador de Oportunidades Acadêmicas

O Centralizador de Oportunidades Acadêmicas é uma plataforma desenvolvida para evitar que estudantes percam oportunidades devido a informações espalhadas. O sistema centraliza avisos sobre palestras, eventos, estágios e projetos.

## Arquitetura do Sistema

O projeto adota uma arquitetura baseada em **Micro-Frontends** com aplicações web e mobile integradas consumindo os mesmos contratos de API.

### Tecnologias Utilizadas
*   **Frontend Web 1 (Shell):** Python com Django.
*   **Frontend Web 2 (MFE de Eventos):** JavaScript com Vue.js.
*   **Backend 1 (Autenticação):** C# com .NET.
*   **Backend 2 (Performance):** Python com FastAPI.
*   **Mobile:** Kotlin nativo.
*   **Bancos de Dados:** SQL Server e MongoDB.

## Estrutura do Repositório

*   `/docs` - Arquivos de ideação, formulários e documentação LaTeX.
*   `/frontend-shell-blazor` - Projeto base da interface web.
*   `/frontend-mfe-leptos` - MFE focado no feed de eventos.
*   `/backend-auth-dotnet` - Microserviço de segurança e identidade.
*   `/backend-feed-rust` - Microserviço focado em performance de buscas.
*   `/mobile-kotlin` - Aplicativo nativo em Kotlin.

## Equipe e Papéis

*   **Matheus:** Backend, Banco de dados, Arquitetura, GitHub e Markdown.
*   **Kamilly:** Frontend, Site e Slides.
*   **João:** Backend, Banco de dados, Pesquisa de Tecnologias e Forms.
*   **Samuel:** Backend, Documentação LaTeX e Forms.
*   **Reinoldes:** Frontend, Testes, Definição de Prazos e Cronograma.
