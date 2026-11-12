<div style="display: flex; justify-content: flex-end; align-items: center; gap: 8px; margin: 10px 0;">
  <span style="font-size: 14px; color: #555; font-weight: bold;">Tamanho do texto:</span>
  <button onclick="diminuirFonte()" title="Diminuir texto" style="padding: 6px 12px; font-weight: bold; cursor: pointer; border: 1px solid #ccc; border-radius: 4px; background: #f8f9fa;">A-</button>
  <button onclick="resetarFonte()" title="Tamanho normal" style="padding: 6px 12px; font-weight: bold; cursor: pointer; border: 1px solid #ccc; border-radius: 4px; background: #f8f9fa;">A</button>
  <button onclick="aumentarFonte()" title="Aumentar texto" style="padding: 6px 12px; font-weight: bold; cursor: pointer; border: 1px solid #ccc; border-radius: 4px; background: #f8f9fa;">A+</button>
  
  <button onclick="window.print()" style="background-color: #0056b3; color: white; padding: 6px 16px; border: none; border-radius: 5px; font-size: 14px; cursor: pointer; box-shadow: 0 2px 4px rgba(0,0,0,0.2); margin-left: 10px;">
    🖨️ Imprimir ou baixar esta página
  </button>
</div>

# GUIA 01 — SISTEMA DE GESTÃO DE ACESSO (SGA)

**Encontre sua situação. Veja a orientação. Faça a ação indicada.**

---

!!! note "PÚBLICO-ALVO"
    * Usuários
    * Central de Atendimento 
    * Órgãos e entidades que acessam o Sistema Integrado de Administração de Serviços Gerais (SIASG)/Compras.gov.br
    * Gestores e operadores de estados e municípios.

---

<h2 id="como-usar-esta-cartilha">Como usar esta cartilha</h2>

Escolha no menu lateral ou nos links abaixo a pergunta que mais se aproxima da sua situação. Cada uma delas é uma seção que traz a resposta, o que conferir, o que fazer e quando pedir ajuda. Os destaques mostram os cuidados necessários, as exigências e os dados que você nunca deve enviar ao atendimento.

---

<h2 id="para-comecar">Para Começar</h2>

<h3 id="o-que-o-sga-faz">O que o SGA faz</h3>

O **Sistema de Gestão de Acesso (SGA)** é a ferramenta eletrônica usada para formalizar a adesão ao SIASG e gerenciar os acessos aos sistemas de compras do governo. No SGA, o responsável formaliza o Termo de Acesso, cadastra usuários e solicita perfis. Também acompanha solicitações e pendências.

Segundo a página oficial do SGA, o processo que antes levava cerca de 1 a 2 semanas passa a ser concluído em poucas horas após a validação da documentação apresentada.

!!! note "Termo de Acesso ou Termo de Adesão?"
    **Nota:** Nesta cartilha, **Termo de Acesso** é o nome do documento utilizado no SGA. Em orientações e comunicações mais antigas, ele pode aparecer como *Termo de Adesão*. Os dois nomes se referem ao documento usado para formalizar o acesso do órgão ou entidade ao SIASG.

---

<h3 id="quem-e-quem">Quem é quem</h3>

Conheça os principais papéis e suas funções:

* **Responsável do órgão:** Cadastra as informações e acompanha as solicitações.
* **Usuário:** Recebe os perfis necessários às atividades que realizará.
* **Administrador do SGA:** Analisa a solicitação e os documentos.

---

<h3 id="visao-geral-do-processo">Visão geral do processo</h3>

Antes de entrar nos detalhes, veja o caminho completo. Cada etapa corresponde a uma seção desta cartilha.

<style>
  .fluxo-processo {
    display: flex;
    align-items: center;
    gap: 8px;
    flex-wrap: wrap;
    margin: 16px 0;
  }
  .fluxo-etapa {
    padding: 8px 14px;
    border-radius: 4px;
    color: #ffffff;
    text-align: center;
    font-size: 0.85em;
    line-height: 1.2;
  }
  .fluxo-etapa strong { display: block; font-size: 1em; }
  .fluxo-azul { background-color: #0047bb; }
  .fluxo-verde { background-color: #008020; }
  .fluxo-seta { color: #666666; font-size: 0.9em; }
</style>

<div class="fluxo-processo">
  <div class="fluxo-etapa fluxo-azul"><strong>1. Formulário</strong><span>dados do órgão</span></div>
  <span class="fluxo-seta">▶</span>
  <div class="fluxo-etapa fluxo-azul"><strong>2. Usuários</strong><span>e perfis</span></div>
  <span class="fluxo-seta">▶</span>
  <div class="fluxo-etapa fluxo-azul"><strong>3. Termo</strong><span>gerar e assinar</span></div>
  <span class="fluxo-seta">▶</span>
  <div class="fluxo-etapa fluxo-azul"><strong>4. Análise</strong><span>administrador</span></div>
  <span class="fluxo-seta">▶</span>
  <div class="fluxo-etapa fluxo-azul"><strong>5. UASG</strong><span>e habilitação</span></div>
  <span class="fluxo-seta">▶</span>
  <div class="fluxo-etapa fluxo-verde"><strong>Finalizado</strong><span>novos pedidos</span></div>
</div>

Se o administrador encontrar algo que precisa ser corrigido, ele devolve a solicitação ao responsável. Após a correção, o processo continua a partir da etapa 3. Veja a <a href="06-solicitacao-voltou-como-corrigir.md#secao-6">seção 6: MINHA SOLICITAÇÃO VOLTOU. COMO CORRIGIR?</a>

---

<h3 id="antes-de-comecar">Antes de começar</h3>

Tenha em mãos antes de iniciar qualquer ação:

* [x] Dados do órgão ou entidade e do dirigente máximo (ou representante legal).
* [x] Dados do responsável: nome, CPF, cargo, telefone, data de nascimento e e-mail.
* [x] Conta Gov.br ativa do responsável (usada para entrar no SGA).
* [x] Dados de cada usuário: nome, CPF, telefone, matrícula e e-mail.
* [x] Atos de nomeação (ou Termo de Posse) para os perfis que exigem documento.
* [x] Meio de assinatura (física ou digital) pela autoridade máxima. O arquivo anexado deve estar em PDF, com até 20 MB.

---

## SUMÁRIO DE NAVEGAÇÃO

### Parte 1: Guia Prático do Usuário e do Gestor

!!! note "Quem deve ler esta parte"
    **Nota:** Servidores, gestores e colaboradores de órgãos e entidades que precisam solicitar a adesão ao SGA, cadastrar usuários ou gerenciar perfis de acesso.

1. [Seção 1 — Meu órgão precisa aderir ao SGA?](01-meu-orgao-precisa-aderir.md)
2. [Seção 2 — Quem é o responsável pelo SGA?](02-quem-e-o-responsavel.md)
3. [Seção 3 — Como cadastrar um usuário?](03-como-cadastrar-usuario.md)
4. [Seção 4 — Qual perfil devo solicitar?](04-qual-perfil-devo-solicitar.md)
5. [Seção 5 — Como gerar e encaminhar o termo?](05-como-gerar-e-encaminhar-termo.md)
6. [Seção 6 — Minha solicitação voltou. Como corrigir?](06-solicitacao-voltou-como-corrigir.md)
7. [Seção 7 — O que significa o status?](07-o-que-significa-o-status.md)
8. [Seção 8 — Como solicitar novos usuários?](08-como-solicitar-novos-usuarios.md)
9. [Seção 9 — Posso alterar usuários, perfis e responsáveis?](09-alterar-usuarios-perfis-responsaveis.md)
10. [Seção 10 — Quando procurar a Central?](10-quando-procurar-a-central.md)
11. [Seção 11 — Erros mais comuns e como evitá-los](11-erros-mais-comuns.md)
* [Perguntas Rápidas](12-perguntas-rapidas.md)
* [Checklist de Verificação](13-checklist-de-verificacao.md)
* [Glossário e Referências](14-glossario-e-referencias.md)

---

### Parte 2: Roteiro de Apoio para a Central de Atendimento

!!! note "Quem deve ler esta parte"
    **Nota:** Atendentes e integrantes da Central de Atendimento (0800), para padronizar as orientações prestadas aos usuários.

12. [Seção 12 — Roteiro de apoio para a Central de Atendimento (0800)](15-roteiro-central-atendimento.md)

---

<br>
<div style="text-align: right; margin: 10px 0;">
  <button onclick="window.print()" style="background-color: #0056b3; color: white; padding: 10px 20px; border: none; border-radius: 5px; font-size: 16px; cursor: pointer; box-shadow: 0 2px 4px rgba(0,0,0,0.2);">
    🖨️ Imprimir esta página
  </button>
</div>
