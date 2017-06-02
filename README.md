# gcm-listaSegundoBimestre

# 1) na gestão de mudanças, quais são as características dos tipos de mudança Abaixo?

Mudança padrão é uma mudança que é pré-autorizada pelo Gerenciamento de Mudanças e que se tornou rotineira, já tendo um script de procedimento para execução. Por este motivo, geralmente o fluxo para execução desta alteração é mais ágil.
Mudança normal é uma mudança para a qual não existe um script já pronto, e precisa passar pelo fluxo mais extenso para ser autorizada e planejada antes de sua execução.
Mudança emergencial é aquela que precisa ser implementada rapidamente para resolver falhas (incidentes). Neste caso, nem sempre será possível realizar todos os testes. Este tipo de mudança é tratado pelo Comitê Consultivo de Mudanças Emergenciais.

# 2) quem são os participantes de um comitê consultivo de mudanças?

Fornecedores. Gerente de Problemas. Gerente de Nível de Serviço. Equipe de relações com o cliente.

# 3) dê 3 exemplos de regras usuais para que os desenvolvedores realizem Mudanças nas funcionalidades de um software.

Recebe, registra e aloca a prioridade adequada para todas as mudanças. Rejeita as mudanças que julga serem improcedentes. Efetua a revisão após a implementação de todas as mudanças.

# 4) cite 4 exemplos de ferramentas de controle de versão de código-fonte.

Redmine Bugzilla Jira Trac IBM Rational ClearQuest Microsoft Team Foundation

# 5) O que é integração contínua?

É uma prática de desenvolvimento de software onde membros de um time integram seu trabalho frequentemente. Cada integração é verificada por um build automatizado (incluindo a execução de testes) para detectar erros o mais cedo possível.

# 6) quais são os benefícios da integração contínua?

Muitas equipes acreditam que esta abordagem reduz problemas de integração e permite que o software seja desenvolvido de forma rápida e coesa.

# 7) cite 2 exemplos de ferramentas de software que podem dar apoio à gestãode mudanças.

-Redmine -Bugzilla

# 8) cite 2 exemplos de ferramentas de software para a realização de
Integração contínua.

Jenkins Bamboo Travis CI Buildbot Strider Go Integrity

# 9) no que consiste fazer o gerenciamento de releases?

Consiste no empacotamento de um sistema para promovê-lo de desenvolvimento para QA (Quality Assurance) e, posteriormente, para produção.

# 10) cite 3 princípios do gerenciamento de releases.

Releases devem ser identificados por um identificador (ID) de versão imutável. Releases devem ser empacotados com todas as suas dependências. O empacotamento de releases deve ser automatizado e desenhado para evitar erros humanos.
O gerenciamento de releases deve ser rápido e confiável para facilitar o desenvolvimento iterativo.
Deve haver um mecanismo para conduzir uma auditoria de um release para verificar todos os seus itens de configuração.
O conteúdo de um release deve ser bem compreendido, incluindo o rastreamento de requisitos.
O gerenciamento de releases deve ser uma fonte de informação no status de todos os releases, idealmente através de um dashboard.

# 11) explique como é feita a identificação de um release utilizando o versionamento semântico, e qual é o significado de cada parte desta identificação.

Uma versão é identificada por uma sequência de 3 números: MAJOR.MINOR.PATCH
O identificador MAJOR deve ser alterado somente quando as alterações tornam a API incompatível com versões anteriores.
O identificador MINOR deve ser alterado quando as alterações são realizadas para adicionar funcionalidade, mantendo a compatibilidade com versões anteriores.
O identificador PATCH deve ser alterado quando as alterações são realizadas para corrigir bugs, mantendo a compatibilidade com versões anteriores

# 12) dê um exemplo de identificação de um release utilizando o versionamento semântico.

Exemplo: 1.2.14

# 13) cite um benefício obtido com a utilização de uma ferramenta como o Codenvy.

Um dos grandes benefícios é a capacidade de integração do código com o GitHub e é uma ferramenta gratuíta para a implatação de um aplicativo.

# 14) cite um benefício obtido com a utilização de uma ferramenta como o Heroku.

Com o heroku você possui uma plataforma open source para manejar seu aplicativo
