# 🧩 Modos do Copiloto (Laravel Edition)

Este repositório organiza diferentes **modos de uso do Copiloto**, pensados para desenvolvimento em **PHP 8.3 + Laravel 11**.

A ideia é simples:  
você escolhe o modo certo para o momento — entender, planejar, editar, executar ou estudar — e trabalha com mais clareza e controle.

---

## ❓ Ask

Modo de **leitura e diagnóstico**.

Use quando quiser:

- Entender um erro
- Analisar um trecho de código
- Revisar uma migration
- Discutir arquitetura
- Avaliar riscos

O Copiloto:
- Não altera código
- Não aplica mudanças
- Não executa comandos
- Apenas analisa e explica

Ideal para debugging e decisões técnicas.

📄 `prompts/prompt-ask.md`

---

## ✏️ Edit

Modo de **modificação direta de código existente**.

Use quando quiser:

- Refatorar Controller ou Service
- Melhorar validação
- Corrigir bug
- Ajustar performance
- Melhorar tratamento de erro
- Adaptar código ao padrão Laravel

Foco:  
“Pegue o que já existe e transforme.”

📄 `prompts/prompt-edit.md`

---

## 🧭 Plan

Modo de **planejamento estruturado antes de implementar**.

Use quando envolver:

- Nova feature
- Alteração de banco
- Mudança arquitetural
- Integração externa
- Refactor maior

O Copiloto:
- Define escopo
- Lista arquivos afetados
- Avalia riscos
- Propõe estratégia
- Só depois (se aprovado) implementa

Perfeito para mudanças críticas.

📄 `prompts/prompt-plan.md`

---

## 🤖 Agent

Modo mais **autônomo e executor**.

Você define um objetivo, por exemplo:

> “Implemente autenticação com Sanctum.”

O Copiloto:
- Cria migrations
- Ajusta Controllers
- Cria Services
- Atualiza rotas
- Sugere testes
- Organiza a estrutura

Funciona como um dev júnior disciplinado executando sob sua direção.

📄 `prompts/prompt-agent.md`

---

## 📚 Study

Modo focado em **aprendizado profundo**.

Em vez de apenas responder ou codar, ele:

- Explica conceitos
- Constrói intuição
- Mostra trade-offs
- Dá exemplos práticos
- Faz perguntas de checkpoint

Ideal para evoluir como backend de verdade.

📄 `prompts/prompt-study.md`

---

# 🧠 Resumo rápido

- **Ask** → entender  
- **Plan** → planejar antes de agir  
- **Edit** → alterar código existente  
- **Agent** → executar mudanças completas  
- **Study** → aprender com profundidade  

---

Se você usar esses modos de forma estratégica, seu fluxo fica mais organizado — e suas decisões técnicas ficam muito mais conscientes.
