# 🤝 Contribuindo com o Framework A.P.A.S.

Obrigado por sua contribuição! Este repositório visa estabelecer o padrão de interação entre humanos e IA para desenvolvimento de software.

Se você encontrou uma forma de tornar o "Agente" mais eficiente ou o "Estudo" mais aprofundado, sua contribuição é valiosa.

---

## 🚀 Como você pode ajudar?

Existem três formas principais de contribuir para o ecossistema A.P.A.S.:

### 1. Refinamento do Core (Prompt Mestre)

Ajuste as instruções do `system_prompt.md` se a IA estiver "pulando" o planejamento ou sendo superficial na fase de estudo.

*   **Foco:** Clareza, redução de tokens e assertividade.

### 2. Criação de "Módulos de Especialidade"

Crie prompts específicos que herdem o protocolo A.P.A.S.:

*   `APAS-Mobile.md`: Focado em Flutter/React Native e ciclo de vida de apps.
*   `APAS-DevOps.md`: Focado em CI/CD, Docker e Terraform.
*   `APAS-Security.md`: Focado em Pentest e auditoria de código.

### 3. Casos de Teste (Benchmark)

Adicione exemplos de interações reais na pasta `/examples`. Isso ajuda novos usuários a entenderem o poder do framework.

---

## 🛠️ O Processo de Pull Request

Siga este processo para garantir a qualidade das atualizações:

1.  Faça um **Fork** do projeto.
2.  **Crie uma Branch** para sua modificação:

    ```bash
    git checkout -b feature/melhoria-estudo
    ```

3.  **Teste o Prompt:** Valide a alteração em pelo menos duas IAs diferentes (ex: GPT-4o, Claude 3.5 Sonnet, Gemini 1.5 Pro) antes de enviar.
4.  **Commit:** Use mensagens claras.
5.  **Abra um Pull Request** descrevendo:

    *   O que mudou?
    *   Por que essa mudança melhora a saída da IA?
    *   **Evidência:** Print ou log de um exemplo de "Antes vs. Depois".

---

## 📜 Critérios de Qualidade

Mantenha estes princípios para manter o framework coeso:

> \[!IMPORTANT]
>
> **1. Modularidade:** O prompt deve funcionar independentemente da linguagem de programação.
>
> **2. Densidade de Informação:** Evite "enchimento". Cada frase do prompt deve ter um propósito.
>
> **3. Abordagem Pedagógica:** O pilar **S (Study)** nunca deve ser negligenciado. O objetivo é que o desenvolvedor aprenda.

---

## 💬 Discussões e Ideias

Para transformar ideias em prompts, abra uma Issue com a tag `[Idea]`.

---

**Vamos construir o melhor copiloto do mundo, um prompt por vez. 🚀**
