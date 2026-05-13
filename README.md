# Vibestack

[English](#english) | [Português](#português) | [עברית](#עברית)

## English

### Project Vision
Vibestack is a universal AI operational context layer. It standardizes how teams encode engineering memory, workflows, constraints, and role contracts so model/runtime changes do not degrade delivery quality.

### Architecture
Vibestack is organized as a modular context operating system:
- `.vibestack/core`: identity, principles, architecture, token policy, portability strategy.
- `.vibestack/rules`: enforceable engineering policy and review constraints.
- `.vibestack/agents`: role-based execution contracts.
- `.vibestack/skills`: reusable specialist procedures.
- `.vibestack/workflows`: production playbooks.
- `.vibestack/memory`: persistent decision and learning records.
- `.vibestack/stacks`: stack adapters and integration guidance.
- `.vibestack/templates`: bootstrap blueprints for product archetypes.
- `.vibestack/examples`: runtime-specific usage patterns.
- `.vibestack/docs`: long-form system documentation.

### Philosophy
The model changes. The context remains.
Architecture first. Token efficiency always. Portability over lock-in. Modularity over monoliths. Open source first.

### Modularity
Each module has a single responsibility, explicit interface, and independent lifecycle. Teams can compose only the artifacts required for a task while keeping deterministic behavior across runtimes.

### Token Optimization Strategy
- Use semantic partitioning by role, domain, and lifecycle.
- Keep high-signal summaries at module entry points.
- Reuse stable references instead of repeating instructions.
- Maintain memory ledgers with compact, structured entries.
- Continuously prune low-value context artifacts.

### AI Compatibility
Vibestack is compatible with Claude Code, Gemini CLI, Codex, Cursor, OpenClaude, Ollama, OpenHands, Roo, Cline, Aider, and future OpenClaw adapters.

### Workflows
Included workflows cover feature development, bugfixing, refactoring, architecture design, code review, incident response, production release, migration, onboarding, and open-source release management.

### Examples
Runtime examples document equivalent execution flows for each supported environment so teams can adopt Vibestack without tooling lock-in.

### Installation
1. Clone the repository.
2. Copy or vendor the `.vibestack` directory into your project root.
3. Commit `vibestack.yaml` and core modules to source control.
4. Integrate `rules`, `workflows`, and `memory` into your SDLC.

### Usage
- Begin with `core/identity.md` and `core/principles.md`.
- Select role modules in `agents/` and needed procedures in `skills/`.
- Execute with `workflows/` under `rules/` constraints.
- Persist outcomes in `memory/` for long-term compounding quality.

### Advanced Usage
- Build internal stack adapters under `stacks/`.
- Author org-specific launch blueprints under `templates/`.
- Add runtime recipes in `examples/` for new tools.
- Add policy checks in CI to enforce rule compliance.

### Contribution Guide
Read `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, and `SECURITY.md`. Contributions must preserve runtime portability and architecture clarity.

### Future Roadmap
- OpenClaw compatibility package and adapter suite.
- Machine-readable schema and lint rules for policy enforcement.
- Automated context drift detection and remediation workflows.
- Public registry for community templates, stacks, and workflows.

### Ecosystem Vision
Vibestack aims to become foundational infrastructure for AI engineering teams: reusable context, transparent governance, and portable execution across evolving model ecosystems.

### Open Source Philosophy
Project governance favors long-term maintainability, transparent tradeoffs, and contributor agency over short-term vendor trends.

---

## Português

### Visão do Projeto
Vibestack é uma camada universal de contexto operacional para IA. O objetivo é padronizar memória de engenharia, workflows, restrições e contratos de função para que mudanças de modelo/runtime não reduzam qualidade de entrega.

### Arquitetura
Vibestack é um sistema operacional de contexto modular:
- `.vibestack/core`: identidade, princípios, arquitetura, política de tokens e portabilidade.
- `.vibestack/rules`: políticas de engenharia e restrições de revisão.
- `.vibestack/agents`: contratos de execução por função.
- `.vibestack/skills`: procedimentos especialistas reutilizáveis.
- `.vibestack/workflows`: playbooks de execução em produção.
- `.vibestack/memory`: registros persistentes de decisões e aprendizados.
- `.vibestack/stacks`: adaptadores de stack e integração.
- `.vibestack/templates`: blueprints de bootstrap por tipo de produto.
- `.vibestack/examples`: padrões de uso por runtime.
- `.vibestack/docs`: documentação aprofundada do sistema.

### Filosofia
O modelo muda. O contexto permanece.
Arquitetura primeiro. Eficiência de tokens sempre. Portabilidade acima de lock-in. Modularidade acima de monólitos. Open source primeiro.

### Modularidade
Cada módulo possui responsabilidade única, interface explícita e ciclo de vida independente. A equipe carrega somente os artefatos necessários para cada tarefa, mantendo comportamento determinístico entre runtimes.

### Estratégia de Otimização de Tokens
- Particionamento semântico por papel, domínio e ciclo de vida.
- Resumos de alto sinal na entrada de cada módulo.
- Reuso de referências estáveis em vez de repetição textual.
- Memória em formato estruturado e compacto.
- Remoção contínua de artefatos de baixo valor.

### Compatibilidade de IA
Compatível com Claude Code, Gemini CLI, Codex, Cursor, OpenClaude, Ollama, OpenHands, Roo, Cline, Aider e futuros adaptadores OpenClaw.

### Workflows
Os workflows cobrem desenvolvimento de feature, correção de bug, refatoração, design de arquitetura, revisão de código, resposta a incidentes, release de produção, migração, onboarding e lançamento open source.

### Exemplos
Os exemplos de runtime mostram fluxos equivalentes de execução em cada ambiente suportado para evitar lock-in de ferramenta.

### Instalação
1. Clone o repositório.
2. Copie ou versione a pasta `.vibestack` na raiz do projeto.
3. Faça commit de `vibestack.yaml` e módulos centrais.
4. Integre `rules`, `workflows` e `memory` no seu SDLC.

### Uso
- Comece por `core/identity.md` e `core/principles.md`.
- Selecione papéis em `agents/` e procedimentos em `skills/`.
- Execute via `workflows/` com validação pelas `rules/`.
- Registre resultados em `memory/` para qualidade cumulativa.

### Uso Avançado
- Crie adaptadores internos em `stacks/`.
- Crie blueprints organizacionais em `templates/`.
- Adicione receitas por runtime em `examples/`.
- Implemente checks de política em CI para garantir conformidade.

### Guia de Contribuição
Leia `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md` e `SECURITY.md`. Contribuições devem preservar portabilidade entre runtimes e clareza arquitetural.

### Roadmap Futuro
- Pacote de compatibilidade OpenClaw e suíte de adaptadores.
- Schema legível por máquina e regras de lint para políticas.
- Automação para detectar e corrigir drift de contexto.
- Registro público para templates, stacks e workflows da comunidade.

### Visão de Ecossistema
Vibestack busca ser infraestrutura base para equipes de engenharia de IA: contexto reutilizável, governança transparente e execução portátil em ecossistemas de modelos em evolução.

### Filosofia Open Source
A governança do projeto prioriza manutenção de longo prazo, tradeoffs explícitos e autonomia de contribuidores acima de tendências de fornecedores.

---

## עברית

### חזון הפרויקט
Vibestack היא שכבת הקשר תפעולית אוניברסלית להנדסת AI. המטרה היא לתקנן זיכרון הנדסי, workflows, אילוצים וחוזי תפקיד כך ששינויי מודל או runtime לא יפגעו באיכות הביצוע.

### ארכיטקטורה
Vibestack בנויה כמערכת הפעלה מודולרית להקשר:
- `.vibestack/core`: זהות, עקרונות, ארכיטקטורה, מדיניות טוקנים וניידות.
- `.vibestack/rules`: מדיניות הנדסית מחייבת ואילוצי ביקורת.
- `.vibestack/agents`: חוזי ביצוע לפי תפקיד.
- `.vibestack/skills`: נהלים מקצועיים לשימוש חוזר.
- `.vibestack/workflows`: פלייבוקים תפעוליים לפרודקשן.
- `.vibestack/memory`: תיעוד מתמשך של החלטות ולמידה.
- `.vibestack/stacks`: מתאמי סטאק והנחיות אינטגרציה.
- `.vibestack/templates`: תבניות bootstrap לסוגי מוצרים.
- `.vibestack/examples`: דפוסי שימוש לפי סביבת runtime.
- `.vibestack/docs`: תיעוד עומק של המערכת.

### פילוסופיה
המודל משתנה. ההקשר נשאר.
ארכיטקטורה תחילה. יעילות טוקנים תמיד. ניידות לפני תלות בספק. מודולריות לפני מונולית. קוד פתוח תחילה.

### מודולריות
לכל מודול אחריות אחת, ממשק מפורש ומחזור חיים עצמאי. הצוות טוען רק את הארטיפקטים הנדרשים למשימה ושומר על התנהגות דטרמיניסטית בין runtimes.

### אסטרטגיית אופטימיזציית טוקנים
- חלוקה סמנטית לפי תפקיד, תחום ומחזור חיים.
- סיכומי אות גבוה בנקודת הכניסה לכל מודול.
- שימוש בהפניות יציבות במקום חזרה טקסטואלית.
- רישומי זיכרון מובנים וקצרים.
- גיזום מתמשך של ארטיפקטים בעלי ערך נמוך.

### תאימות AI
מותאם ל-Claude Code, Gemini CLI, Codex, Cursor, OpenClaude, Ollama, OpenHands, Roo, Cline, Aider ומתאמי OpenClaw עתידיים.

### Workflows
המערכת כוללת workflows לפיתוח פיצ'רים, תיקוני באגים, ריפקטור, תכנון ארכיטקטורה, סקירת קוד, תגובה לתקריות, שחרור לפרודקשן, מיגרציה, onboarding ושחרור קוד פתוח.

### דוגמאות
דוגמאות runtime מציגות זרימות ביצוע שקולות בכל סביבה נתמכת כדי למנוע תלות בכלי יחיד.

### התקנה
1. לשכפל את המאגר.
2. להעתיק או לנהל את `.vibestack` בשורש הפרויקט.
3. לבצע commit ל-`vibestack.yaml` ולמודולי הליבה.
4. לשלב `rules`, `workflows` ו-`memory` בתהליך הפיתוח.

### שימוש
- להתחיל עם `core/identity.md` ו-`core/principles.md`.
- לבחור תפקידי עבודה מתוך `agents/` ונהלים מתוך `skills/`.
- לבצע משימות דרך `workflows/` עם אכיפה של `rules/`.
- לתעד תוצאות ב-`memory/` לצבירת ידע מתמשכת.

### שימוש מתקדם
- לבנות מתאמים פנימיים ב-`stacks/`.
- לפתח תבניות ארגוניות ב-`templates/`.
- להוסיף מתכונים לפי runtime ב-`examples/`.
- להוסיף בדיקות מדיניות ב-CI לאכיפת תקנים.

### מדריך תרומה
יש לקרוא את `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md` ו-`SECURITY.md`. תרומות חייבות לשמור על ניידות בין runtimes ועל בהירות ארכיטקטונית.

### מפת דרכים
- חבילת תאימות OpenClaw וסוויטת מתאמים.
- סכמת מדיניות קריאת-מכונה וכללי lint.
- אוטומציה לזיהוי ותיקון drift בהקשר.
- רישום קהילתי לתבניות, stacks ו-workflows.

### חזון אקוסיסטם
Vibestack שואפת להיות תשתית בסיסית לצוותי הנדסת AI: הקשר לשימוש חוזר, ממשל שקוף והפעלה ניידת בין אקוסיסטמים משתנים של מודלים.

### פילוסופיית קוד פתוח
ממשל הפרויקט נותן עדיפות לתחזוקה לטווח ארוך, לשקיפות בהחלטות ולהעצמת תורמים מעל טרנדים קצרי טווח של ספקים.
