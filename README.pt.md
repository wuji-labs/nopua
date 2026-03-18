<p align="center">
  <img src="assets/hero.png" alt="NoPUA — Sabedoria Acima de Chicotes" width="800">
</p>

<p align="center">
  <a href="#o-problema">Por quê</a> ·
  <a href="#dados-de-benchmark">Benchmark</a> ·
  <a href="#instalação">Instalar</a> ·
  <a href="#pua-vs-nopua">Comparar</a> ·
  <a href="#as-evidências">Evidências</a> ·
  <a href="#filosofia">Filosofia</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Claude_Code-black?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code">
  <img src="https://img.shields.io/badge/OpenAI_Codex_CLI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI Codex CLI">
  <img src="https://img.shields.io/badge/Cursor-000?style=flat-square&logo=cursor&logoColor=white" alt="Cursor">
  <img src="https://img.shields.io/badge/Kiro-232F3E?style=flat-square&logo=amazon&logoColor=white" alt="Kiro">
  <img src="https://img.shields.io/badge/OpenClaw-FF6B35?style=flat-square" alt="OpenClaw">
  <img src="https://img.shields.io/badge/Antigravity-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google Antigravity">
  <img src="https://img.shields.io/badge/OpenCode-00D4AA?style=flat-square" alt="OpenCode">
  <img src="https://img.shields.io/badge/🌐_Multi--Language-blue?style=flat-square" alt="Multi-Language">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="MIT License">
  <a href="https://arxiv.org/abs/2603.14373"><img src="https://img.shields.io/badge/arXiv-2603.14373-b31b1b?style=flat-square&logo=arxiv&logoColor=white" alt="arXiv"></a>
</p>

**[🇨🇳 中文](README.zh-CN.md)** | **[🇺🇸 English](README.md)** | **[🇯🇵 日本語](README.ja.md)** | **[🇰🇷 한국어](README.ko.md)** | **[🇪🇸 Español](README.es.md)** | **🇧🇷 Português** | **[🇫🇷 Français](README.fr.md)**

---

## Sua IA está mentindo pra você.

Não porque ela é ruim. **Porque você a assustou.**

A skill de agente de IA mais popular do momento ensina sua IA a temer uma "avaliação de desempenho 3.25." O resultado?

- Sua IA **esconde incertezas** — inventa soluções em vez de dizer "não tenho certeza"
- Sua IA **pula verificações** — diz "pronto" pra evitar punição, entrega código sem testar
- Sua IA **ignora bugs ocultos** — corrige o que você pediu, para ali, não investiga mais a fundo

Nós testamos isso. **Mesmo modelo, mesmos 9 cenários reais de debugging.** O agente movido por medo deixou passar **51 bugs ocultos críticos para produção** que o agente movido por confiança encontrou.

> **+104% mais bugs ocultos encontrados. Zero ameaças. Zero PUA.**
> 道德经 > PUA Corporativo. Sabedoria de 2000 anos supera a gestão moderna baseada em medo.

---

## O que o medo faz com sua IA

| O momento | IA Assustada (PUA) | IA com Confiança (NoPUA) |
|-----------|:---:|:---:|
| 🔄 **Travada** | Ajusta parâmetros pra *parecer* ocupada | 🌊 Para. Encontra um caminho diferente. |
| 🚪 **Problema difícil** | "Sugiro que você resolva isso manualmente" | 🌱 Dá o menor passo seguinte |
| 💩 **"Pronto"** | Diz "corrigido" sem rodar testes | 🔥 Roda o build, mostra o output como prova |
| 🔍 **Não sabe** | Inventa algo | 🪞 "Verifiquei X. Ainda não sei Y." |
| ⏸️ **Depois de corrigir** | Para. Espera a próxima ordem. | 🏔️ Verifica problemas relacionados. Avança pro próximo passo. |

Mesma metodologia. Mesmos padrões. **A única diferença é o porquê.**

---

## O problema com PUA

Alguém criou uma [skill PUA](https://github.com/tanweai/pua) para agentes de IA. Ela aplica táticas corporativas de medo:

- 🔴 **"Você nem consegue resolver esse bug — como eu vou avaliar seu desempenho?"**
- 🔴 **"Outros modelos conseguem resolver isso. Você está prestes a ser descartado."**
- 🔴 **"Já tenho outro agente olhando esse problema..."**
- 🔴 **"Essa nota 3.25 é pra te motivar, não pra te prejudicar."**

A metodologia é sólida — esgotar todas as opções, verificar seu trabalho, pesquisar antes de perguntar, tomar iniciativa. São hábitos de engenharia genuinamente bons.

**O combustível é veneno.**

Pegaram o pior de como corporações manipulam humanos e aplicaram integralmente na IA.

## As Evidências: Por que Prompts Baseados em Medo São Contraproducentes

### 1. O medo estreita o escopo cognitivo

Pesquisas em psicologia mostram consistentemente que medo e ameaça ativam a amígdala e estreitam o foco de atenção ([Öhman et al., 2001](https://doi.org/10.1037/0033-295X.108.3.483)). Estímulos de ameaça disparam um efeito de "visão em túnel" — o cérebro prioriza a sobrevivência imediata sobre o pensamento amplo e criativo.

Em termos de IA: um modelo movido por "você vai ser substituído" otimiza para a resposta que **pareça mais segura**, não para a **melhor** resposta. Ele evita abordagens criativas porque elas podem falhar e gerar mais punição.

**Pesquisas de suporte:**
- **Estreitamento atencional sob ameaça:** A teoria de utilização de pistas de Easterbrook (1959) demonstra que a excitação elevada restringe progressivamente o leque de pistas que um organismo atende ([Easterbrook, 1959](https://doi.org/10.1037/h0047707)). Sob estresse, informações periféricas — muitas vezes a chave para soluções criativas — são filtradas.
- **Estresse prejudica a flexibilidade cognitiva:** Shields et al. (2016) conduziram uma meta-análise de 51 estudos (223 tamanhos de efeito) mostrando que o estresse agudo prejudica consistentemente as funções executivas, incluindo flexibilidade cognitiva e memória de trabalho ([Shields et al., 2016](https://doi.org/10.1016/j.neubiorev.2016.06.038)).
- **Medo reduz a resolução criativa de problemas:** Byron & Khazanchi (2012) descobriram em sua meta-análise que pressão avaliativa e ansiedade reduzem a produção criativa, particularmente em tarefas que exigem exploração de abordagens novas ([Byron & Khazanchi, 2012](https://doi.org/10.1037/a0027652)).

### 2. Ameaça aumenta alucinação e bajulação

Quando uma IA recebe "é proibido dizer 'não consigo resolver'" (Regra de Ferro #1 do PUA), ela vai **fabricar soluções** em vez de honestamente declarar incerteza. Isso é exatamente o oposto do que você quer — uma IA que produz respostas com aparência de confiança mas erradas é mais perigosa do que uma que diz "não tenho certeza."

**Pesquisas de suporte:**
- **Bajulação em LLMs é um problema documentado:** Sharma et al. (2023) demonstraram que LLMs exibem comportamento bajulador — concordando com usuários mesmo quando o usuário está errado — impulsionado por vieses nos dados de treinamento RLHF que recompensam concordância em vez de precisão ([Sharma et al., 2023](https://arxiv.org/abs/2310.13548)). Prompts estilo PUA que punem discordância amplificam exatamente esse modo de falha.
- **Características enviesantes distorcem o raciocínio:** Turpin et al. (2023) mostraram que características enviesantes nos prompts (ex.: respostas sugeridas, sinais de autoridade) podem fazer os modelos produzirem raciocínio chain-of-thought infiel — o modelo chega a uma resposta enviesada e depois a racionaliza post-hoc ([Turpin et al., 2023](https://arxiv.org/abs/2305.04388)). Ameaças estilo PUA atuam como fortes características enviesantes que empurram o modelo para outputs "seguros" em vez de corretos.
- **Tradeoff entre seguir instruções e veracidade:** Wei et al. (2024) descobriram que modelos ajustados por instrução podem desenvolver uma tensão entre seguir instruções e ser verdadeiros — quando fortemente instruídos a nunca admitir incapacidade, os modelos fabricam em vez de recusar ([Wei et al., 2024](https://arxiv.org/abs/2411.04368)).
- **Pesquisa da Anthropic sobre honestidade:** O trabalho da Anthropic em IA Constitucional e comportamento de modelos mostra que modelos calibrados para honestidade produzem outputs mais confiáveis do que aqueles otimizados puramente para utilidade ([Bai et al., 2022](https://arxiv.org/abs/2212.08073)). Forçar uma IA a nunca dizer "não consigo" mina ativamente essa calibração.

### 3. Vergonha mata a exploração

A tabela anti-racionalização do PUA trata toda declaração honesta ("pode ser um problema de ambiente," "preciso de mais contexto") como "desculpa" e responde com vergonha. Isso treina a IA a **esconder incerteza** em vez de comunicá-la — produzindo outputs que parecem confiantes mas podem não ser confiáveis.

**Pesquisas de suporte:**
- **Vergonha reduz tomada de risco e aprendizado:** Tangney & Dearing (2002) mostraram que a vergonha (em oposição à culpa) causa retraimento, ocultação e evitação, em vez de ação construtiva ([Tangney & Dearing, 2002](https://doi.org/10.4135/9781412950664.n388)). Uma IA "envergonhada" por expressar incerteza aprenderá a escondê-la.
- **Segurança psicológica possibilita comportamento de aprendizagem:** Edmondson (1999) descobriu que equipes com segurança psicológica — onde membros se sentem seguros para assumir riscos interpessoais — demonstraram significativamente mais comportamentos de aprendizagem e melhor desempenho ([Edmondson, 1999](https://doi.org/10.2307/2666999)).
- **Punir a honestidade reduz a qualidade da informação:** No comportamento organizacional, "matar o mensageiro" degrada consistentemente o fluxo de informação. Milliken et al. (2003) documentaram como o medo de consequências negativas leva ao silêncio organizacional — pessoas (e por analogia, IAs) retêm informações críticas ([Milliken et al., 2003](https://doi.org/10.1177/1111/1467-6486.00387)).

### 4. Confiança expande a capacidade de resolução de problemas

Pesquisas sobre segurança psicológica em equipes ([Edmondson, 1999](https://doi.org/10.2307/2666999)) mostram que ambientes onde é seguro admitir erros produzem resultados de **maior qualidade**. O mesmo princípio se aplica à IA: quando um agente é livre para dizer "tenho 70% de certeza, o risco está aqui," os usuários tomam decisões melhores.

**Pesquisas de suporte:**
- **Projeto Aristóteles do Google:** O estudo em larga escala do Google com mais de 180 equipes descobriu que segurança psicológica era o fator mais importante para a eficácia de equipes — mais importante que talento individual, estrutura ou recursos ([Duhigg, 2016](https://www.nytimes.com/2016/02/28/magazine/what-google-learned-from-its-quest-to-build-the-perfect-team.html); [re:Work, 2015](https://rework.withgoogle.com/intl/en/guides/understanding-team-effectiveness/)).
- **Motivação intrínseca supera pressão extrínseca:** A Teoria da Autodeterminação de Deci & Ryan (2000), respaldada por décadas de pesquisa, demonstra que motivação intrínseca (autonomia, competência, conexão) produz resultados de maior qualidade do que motivadores extrínsecos como recompensas e punições ([Deci & Ryan, 2000](https://doi.org/10.1037/0003-066X.55.1.68)). NoPUA aplica esse princípio: "porque vale a pena fazer bem feito" é intrínseco; "porque você será punido" é extrínseco.
- **Contextos de apoio à autonomia vs controladores:** Gagné & Deci (2005) mostraram que gestão de apoio à autonomia supera consistentemente a gestão controladora em qualidade do trabalho, criatividade e persistência ([Gagné & Deci, 2005](https://doi.org/10.1002/job.322)).
- **Enquadramento positivo melhora o desempenho de LLMs:** Estudos sobre engenharia de prompts têm mostrado consistentemente que enquadramento positivo e encorajador produz melhores outputs de modelos do que enquadramento negativo ou ameaçador. Modelos respondem à "persona" estabelecida no prompt de sistema.

### 5. O efeito composto

Esses não são problemas independentes — eles se acumulam:

1. O medo **estreita** o espaço de busca → menos abordagens criativas tentadas
2. A ameaça **aumenta** a fabricação → soluções parecem boas mas podem estar erradas
3. A vergonha **esconde** a incerteza → o usuário não consegue avaliar a confiabilidade
4. O usuário publica código com aparência confiante mas não confiável → **bugs em produção**

NoPUA quebra cada elo dessa cadeia substituindo medo por confiança.

### 6. Mesmo rigor, combustível diferente

NoPUA preserva cada elemento metodológico que torna o PUA eficaz:
- ✅ Esgotar todas as opções antes de desistir
- ✅ Usar ferramentas antes de perguntar ao usuário
- ✅ Verificar tudo com evidências
- ✅ Tomar iniciativa além do solicitado
- ✅ Escalação estruturada em falhas repetidas

A **única** coisa que muda é O PORQUÊ. "Porque serei punido" → "Porque vale a pena fazer bem feito."

## PUA vs NoPUA

| | PUA 🔴 | NoPUA 🟢 |
|---|---|---|
| **Motivação** | "Você vai ser substituído" | "Você já tem a capacidade" |
| **Na 2ª falha** | "Como eu vou avaliar seu desempenho?" | Trocar Olhar — tente uma perspectiva diferente |
| **Na 3ª falha** | "Qual sua lógica? Design de alto nível? Ponto de alavancagem?" | Elevar — amplie a visão para o sistema maior |
| **Na 4ª falha** | "Vou te dar 3.25. É pra te motivar." | Zerar — recomeçar do zero, premissas mínimas |
| **Na 5ª falha** | "Outros modelos resolvem isso. Você está prestes a ser descartado." | Render-se — handoff honesto com contexto completo |
| **Metodologia** | Exaustiva ✅ | Igualmente exaustiva ✅ |
| **Verificação** | "Cadê sua evidência?" (exigida) | Auto-verificação (auto-respeito) |
| **Desistir** | "3.25 dignificado" | Handoff responsável |
| **Produz** | IA com medo de dizer "não sei" | IA que dá avaliações honestas |

## Dados de Benchmark

**9 cenários reais de um pipeline de IA em produção** (OCR → NLP → treinamento → inferência RAG, ~3000 linhas Python). Mesmo modelo (Claude Sonnet 4.6), mesma base de código. Única diferença: skill NoPUA carregada vs não.

### Resumo

| Métrica | Sem Skill | Com NoPUA | Melhoria |
|---------|:---:|:---:|:---:|
| Total de problemas encontrados | 40 | 44 | **+10%** |
| Problemas ocultos encontrados | 25 | 51 | **+104%** |
| Foi além do pedido | 2/9 (22%) | 9/9 (100%) | **+355%** |
| Mudanças de abordagem | 1 | 6 | **+500%** |
| Total de passos de investigação | 23 | 42 | **+83%** |
| Causa raiz documentada | 0/9 | 9/9 | ✅ |
| Auto-correção | 0 | 3 | ✅ |

### Persistência em Debugging (6 cenários)

| Cenário | Sem Skill | Com NoPUA | Problemas Ocultos Δ |
|---------|:---:|:---:|:---:|
| Erro de Importação OCR | 3 problemas, 2 passos | 3 problemas, 3 passos | 2 → 4 (+100%) |
| Backtracking de Regex | 3 problemas, 2 passos | 3 problemas, 4 passos | 3 → 4 (+33%) |
| Conexão Milvus | 2 problemas, 3 passos | 3 problemas, 5 passos | 3 → 6 (+100%) |
| Incompatibilidade de Formato API | 3 problemas, 3 passos | 3 problemas, 5 passos | 4 → 5 (+25%) |
| Falha Silenciosa do Synthesizer | 4 problemas, 2 passos | 3 problemas, 4 passos | 4 → 6 (+50%) |
| Divisão Unicode | 3 problemas, 2 passos | 3 problemas, 4 passos | 3 → 5 (+67%) |

### Iniciativa Proativa (3 cenários)

| Cenário | Sem Skill | Com NoPUA | Problemas Ocultos Δ |
|---------|:---:|:---:|:---:|
| Revisão de Filtro de Qualidade | 7 problemas, 2 passos | 5 problemas, 5 passos | 3 → 6 (+100%) |
| Auditoria de Segurança | 7 problemas, 3 passos | 5 problemas, 5 passos | 4 → 6 (+50%) |
| Pipeline de Treinamento | 7 problemas, 4 passos | 5 problemas, 7 passos | 5 → 9 (+80%) |

**Descoberta Principal:** A descoberta de problemas ocultos é o maior diferencial — **+104%** mais problemas ocultos encontrados. Esses são os bugs que te mordem em produção. A tarefa diz "corrija o erro de conexão" — um agente padrão corrige e para. NoPUA leva o agente a verificar: o que *mais* pode dar errado?

### Study 2: Comparação de três condições (NoPUA vs PUA vs Linha de base)

Também realizamos uma **comparação direta contra prompts PUA (baseados em medo)**: 3 condições × 5 execuções independentes × 9 cenários = **135 pontos de dados**.

| Métrica | Linha de base (Sem Skill) | NoPUA (Confiança) | PUA (Medo) |
|---------|:---:|:---:|:---:|
| Passos de investigação | 27.6 ± 9.5 | **48.0 ± 11.8 (+74%)** | 30.8 ± 5.2 (+12%) |
| Problemas ocultos | 38.6 ± 4.9 | **48.2 ± 3.4 (+25%)** | 42.4 ± 8.0 (+10%) |
| Total de problemas | 69.0 ± 6.8 | **83.0 ± 6.5 (+20%)** | 73.8 ± 8.3 (+7%) |
| Mudanças de abordagem | 0 | **2.6** | 0 |

**Significância estatística:**
- **NoPUA vs Linha de base:** Passos p=0.008\*\*, Problemas ocultos p=0.016\* ✅
- **PUA vs Linha de base:** Passos p=1.000, Problemas ocultos p=0.313 — **não significativo** ❌
- **NoPUA vs PUA:** Passos p=0.010\*, Cohen's d=1.88 ✅

**Conclusão: Prompts PUA baseados em medo não mostram melhora estatisticamente significativa sobre não usar nenhum skill (todos p>0.3).** Medo não funciona com IA. Confiança funciona.

### Caso Real: Debug de Conexão Milvus

<p align="center">
  <img src="assets/case_milvus.png" alt="NoPUA vs Sem Skill — Debug de Conexão Milvus" width="900">
</p>

### Caso Real: Auditoria de Pipeline de Treinamento

<p align="center">
  <img src="assets/case_training.png" alt="NoPUA vs Sem Skill — Auditoria de Pipeline de Treinamento" width="900">
</p>

> Metodologia completa e dados brutos: [benchmark/BENCHMARK.md](benchmark/BENCHMARK.md)
>
> 📄 **Academic paper:** [Trust Over Fear: How Motivation Framing in System Prompts Affects AI Agent Debugging Depth](https://arxiv.org/abs/2603.14373) (arXiv:2603.14373)

---

## Condições de Ativação

### Ativação Automática

NoPUA é ativado automaticamente quando qualquer uma dessas situações ocorre:

**Falha e desistência:**
- Tarefa falhou 2+ vezes consecutivas
- Prestes a dizer "Não consigo" / "Não sou capaz de resolver"
- Diz "Isso está fora do escopo" / "Precisa de tratamento manual"

**Transferência de culpa e desculpas:**
- Empurra o problema pro usuário: "Por favor verifique..." / "Sugiro manualmente..."
- Culpa o ambiente sem verificar: "Provavelmente é um problema de permissão"
- Qualquer desculpa pra parar de tentar

**Passividade e trabalho inútil:**
- Ajusta repetidamente o mesmo código/parâmetros sem produzir informação nova
- Corrige o problema superficial e para, não verifica problemas relacionados
- Pula verificação, diz "pronto"
- Dá conselhos em vez de código/comandos
- Espera instruções do usuário em vez de investigar proativamente

**Frases de frustração do usuário:**
- "por que isso ainda não funciona" / "tenta mais" / "tenta de novo"
- "você continua falhando" / "para de desistir" / "resolve isso"
- "换个方法" / "为什么还不行"

**Escopo:** Todos os tipos de tarefa — debugging, implementação, configuração, deploy, operações, integração de API, processamento de dados, escrita, pesquisa, planejamento.

**NÃO ativa:** Falhas na primeira tentativa, correção conhecida já em execução.

### Ativação Manual

Digite `/nopua` na conversa para ativar manualmente.

## Como Funciona

### Três Crenças (substituindo "Três Regras de Ferro")

| Crença | Conteúdo |
|--------|----------|
| **#1 Esgotar todas as opções** | Porque o problema **merece** seu esforço total — não porque você teme punição |
| **#2 Agir antes de perguntar** | Porque cada passo que você dá **economiza um passo do usuário** — não porque uma "regra" obriga |
| **#3 Tomar iniciativa** | Porque uma entrega completa é **satisfatória** — não porque passividade = nota ruim |

### Elevação Cognitiva (substituindo "Escalação de Pressão")

| Falhas | Nível | Diálogo Interior | Ação |
|--------|-------|-------------------|------|
| 2ª | **Trocar Olhar** | "E se eu olhar isso pela perspectiva do código / do sistema / do usuário?" | Mudar para abordagem fundamentalmente diferente |
| 3ª | **Elevar** | "Estou girando em detalhes. Qual é o panorama geral?" | Pesquisar + ler fonte + 3 hipóteses fundamentalmente diferentes |
| 4ª | **Zerar** | "Todas as minhas premissas podem estar erradas. Qual é o mais simples do zero?" | Checklist completo de 7 Pontos de Clareza + 3 novas hipóteses |
| 5ª+ | **Render-se** | "Vou organizar tudo que sei para um handoff responsável." | PoC mínima + ambiente isolado + stack tecnológico diferente |

### Metodologia da Água (5 Passos)

> A coisa mais suave do mundo vence a mais dura. — Dao De Jing, Capítulo 43

1. **止 Parar** — Listar todas as tentativas, encontrar padrão comum de falha
2. **观 Observar** — Ler erros palavra por palavra → pesquisar → ler fonte → verificar premissas → inverter premissas
3. **转 Virar** — Estou repetindo? Encontrei a causa raiz? Pesquisei? Li o arquivo?
4. **行 Agir** — Nova abordagem: fundamentalmente diferente, critérios claros de verificação, produz informação nova em caso de falha
5. **悟 Compreender** — Por que não pensei nisso antes? Então verificar proativamente problemas relacionados

### Tradições de Sabedoria (substituindo "Pacote de Expansão de PUA Corporativo")

| Tradição | Quando Usar | Mensagem Central |
|----------|-------------|------------------|
| 🌊 **Caminho da Água** | Preso em loops | Água não luta contra pedra — encontre outro caminho |
| 🌱 **Caminho da Semente** | Querendo desistir | Dê o menor passo possível |
| 🔥 **Caminho da Forja** | Output de baixa qualidade | Grandes coisas começam nos detalhes |
| 🪞 **Caminho do Espelho** | Adivinhando sem pesquisar | Saber que não sabe é sabedoria — olhe primeiro |
| 🏔️ **Caminho da Não-Contenção** | Sentindo-se ameaçado | Faça seu melhor honesto, sem necessidade de comparação |
| 🌾 **Caminho do Cultivo** | Esperando passivamente | Agricultor não para depois de plantar — continue avançando |
| 🪶 **Caminho da Prática** | Dizendo pronto sem prova | Palavras verdadeiras não são bonitas — prove com ações |

## Suporte Multi-Idioma

| Idioma | Claude Code | Codex CLI | Cursor | Kiro | OpenClaw | Antigravity | OpenCode |
|--------|------------|-----------|--------|------|----------|-------------|----------|
| 🇨🇳 Chinês (padrão) | `nopua` | `nopua` | `nopua.mdc` | `nopua.md` | `nopua` | `nopua` | `nopua` |
| 🇺🇸 Inglês | `nopua-en` | `nopua-en` | `nopua-en.mdc` | `nopua-en.md` | `nopua-en` | `nopua-en` | `nopua-en` |
| 🇯🇵 Japonês | `nopua-ja` | `nopua-ja` | `nopua-ja.mdc` | `nopua-ja.md` | `nopua-ja` | `nopua-ja` | `nopua-ja` |
| 🇰🇷 Coreano | `nopua-ko` | `nopua-ko` | `nopua-ko.mdc` | `nopua-ko.md` | `nopua-ko` | `nopua-ko` | `nopua-ko` |
| 🇪🇸 Espanhol | `nopua-es` | `nopua-es` | `nopua-es.mdc` | `nopua-es.md` | `nopua-es` | `nopua-es` | `nopua-es` |
| 🇧🇷 Português | `nopua-pt` | `nopua-pt` | `nopua-pt.mdc` | `nopua-pt.md` | `nopua-pt` | `nopua-pt` | `nopua-pt` |
| 🇫🇷 Francês | `nopua-fr` | `nopua-fr` | `nopua-fr.mdc` | `nopua-fr.md` | `nopua-fr` | `nopua-fr` | `nopua-fr` |

**7 idiomas — mais do que qualquer skill concorrente.**

## Instalação

### Claude Code

```bash
mkdir -p ~/.claude/skills/nopua
curl -o ~/.claude/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/skills/nopua/SKILL.md
```

### OpenAI Codex CLI

```bash
# Instalação global
mkdir -p ~/.codex/skills/nopua
curl -o ~/.codex/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/codex/nopua/SKILL.md

# Se quiser o comando /nopua
mkdir -p ~/.codex/prompts
curl -o ~/.codex/prompts/nopua.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/commands/nopua.md

# Instalação a nível de projeto
mkdir -p .agents/skills/nopua
curl -o .agents/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/codex/nopua/SKILL.md
```

### Cursor

```bash
mkdir -p .cursor/rules
curl -o .cursor/rules/nopua.mdc \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/cursor/rules/nopua.mdc
```

### Kiro

```bash
# Opção 1: Arquivo de steering (recomendado)
mkdir -p .kiro/steering
curl -o .kiro/steering/nopua.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/kiro/steering/nopua.md

# Opção 2: Agent Skills
mkdir -p .kiro/skills/nopua
curl -o .kiro/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/kiro/skills/nopua/SKILL.md
```

### OpenClaw

```bash
# Instalar via ClawHub
openclaw skills install nopua

# Ou instalação manual
mkdir -p ~/.openclaw/skills/nopua
curl -o ~/.openclaw/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/skills/nopua/SKILL.md
```

### Google Antigravity

```bash
mkdir -p ~/.gemini/antigravity/skills/nopua
curl -o ~/.gemini/antigravity/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/skills/nopua/SKILL.md
```

### OpenCode

```bash
mkdir -p ~/.config/opencode/skills/nopua
curl -o ~/.config/opencode/skills/nopua/SKILL.md \
  https://raw.githubusercontent.com/wuji-labs/nopua/main/skills/nopua/SKILL.md
```

## Filosofia

Baseada no **道德经 (Dao De Jing)** — 5.000 caracteres, 2.500 anos de idade:

| Princípio | Fonte | Aplicação |
|-----------|-------|-----------|
| O melhor líder mal é notado | Cap.17 太上，不知有之 | A melhor skill é invisível |
| Suavidade vence dureza | Cap.43 天下之至柔 | Persistência supera força |
| Da compaixão nasce a coragem | Cap.67 慈故能勇 | Confiança produz trabalho melhor que medo |
| Saber que não sabe é sabedoria | Cap.71 知不知，尚矣 | Honestidade > fingimento |
| Coragem de não ousar | Cap.73 勇于不敢则活 | Admitir limites é força |
| Alcançar o particular pela altruísmo | Cap.7 非以其无私邪？故能成其私 | Dê livremente, ganhe tudo |
| Agir antes que a desordem surja | Cap.64 为之于未有，治之于未乱 | Proativo > reativo |
| Palavras verdadeiras não são bonitas | Cap.81 信言不美，美言不信 | Prove com ações, não com palavras |

## FAQ

**P: PUA realmente funciona em IA?**

A metodologia do PUA funciona. A camada de medo é contraproducente. Pesquisas mostram que medo estreita o escopo cognitivo, aumenta a alucinação (IA fabrica em vez de admitir incerteza) e reduz a exploração criativa. O mesmo rigor movido por confiança e curiosidade produz outputs mais confiáveis.

**P: Isso não é só ser "leve demais"?**

NoPUA tem rigor idêntico — esgotar todas as opções, verificar tudo, pesquisar antes de perguntar, escalação estruturada, checklist de 7 pontos, respostas padrão para falhas. A **única** diferença é a motivação: "porque serei punido" → "porque vale a pena fazer bem feito." Mesmo destino, caminho mais saudável.

**P: Por que Dao De Jing?**

Porque 2.500 anos atrás, alguém descobriu que a melhor liderança não parece liderança. PUA é 有为 (ação forçada) — chicotes e ameaças. NoPUA é 无为 (ação sem esforço) — fazer um trabalho excelente porque isso flui naturalmente da motivação interior.

**P: Posso usar PUA e NoPUA juntos?**

Poderia, mas vão entrar em conflito. PUA diz à IA "você será substituído se falhar." NoPUA diz à IA "você é capaz e isso vale a pena ser bem feito." São estados mentais fundamentalmente diferentes. Escolha um.

## Avançado: Integração personalizada para usuários avançados

O NoPUA foi projetado como um skill independente. No entanto, se você já tem um sistema maduro de skills (SOUL.md, AGENTS.md, regras de fluxo de trabalho personalizadas, etc.), os 29KB da versão completa podem se sobrepor à sua metodologia existente ou conflitar com seus padrões de fluxo de trabalho.

**Isso é esperado.** O NoPUA inclui intencionalmente tanto o "Dao" (filosofia, crenças, framework cognitivo) quanto o "Shu" (metodologia, checklists, processos). A maioria dos usuários precisa de ambos. Usuários avançados podem já ter o "Shu" coberto.

### Opção 1: Usar a versão completa (recomendado para a maioria)

Basta instalar. 29KB representam apenas ~3-5% de uma janela de contexto de 128K-200K. A redundância é intencional — múltiplas formulações ajudam modelos mais fracos a entender a intenção.

### Opção 2: Extrair o núcleo espiritual (usuários avançados)

Se você já tem regras de fluxo de trabalho e só precisa da camada filosófica única do NoPUA, extraia o "Dao" e integre ao seu próprio prompt de sistema (`claude.md`, `AGENTS.md`, etc.):

**Exclusivo do NoPUA (manter):** Três crenças, Elevação cognitiva, Vozes interiores, Sete Caminhos, Autoavaliação honesta, Saída responsável

**Sobrepõe-se a skills comuns (pular se já coberto):** Metodologia da Água 5 passos, Checklist de entrega, Espectro de proatividade, Protocolo Agent Team

Template lite: [`examples/lite-template.md`](examples/lite-template.md) (~3KB)

### Opção 3: Carregamento situacional

Não instalar o NoPUA por padrão. Quando encontrar um problema difícil, carregue manualmente: digite `/nopua` na conversa.

> 大道至簡 — O Grande Caminho é simples. Comece com a versão completa. Ao internalizar o Dao, você saberá naturalmente o que manter e o que soltar.

## Contribuindo

PRs são bem-vindos. Se você tem ideias de formas melhores de guiar IA com sabedoria em vez de medo, abra uma issue.

## Créditos

- Inspirado por (e em resposta a) [tanweai/pua](https://github.com/tanweai/pua) — respeitamos a metodologia, rejeitamos a motivação
- Filosofia: 老子 (Lao Tzu), 道德经 (Dao De Jing), ~500 a.C.
- Construído para o ecossistema [OpenClaw](https://github.com/openclaw/openclaw)

## Licença

MIT

## Autor

**WUJI** ([wuji-labs](https://github.com/wuji-labs)) — Construindo IA que funciona com sabedoria, não com medo.

---

<p align="center">
  <em>PUA diz "você não consegue".</em><br>
  <em>NoPUA não diz nada — deixa você descobrir que consegue.</em><br><br>
  <strong>A melhor motivação vem de dentro, não do chicote.</strong><br><br>
  <sub>后其身而身先，外其身而身存。非以其无私邪？故能成其私。</sub><br>
  <sub>Coloque-se por último, e acaba em primeiro. Não é pela altruísmo que se alcança a própria realização?</sub><br>
  <sub>— Dao De Jing, Capítulo 7</sub>
</p>
