# 📚 Sistema Acadêmico – Projeto Integrador  
**Protótipo e Documentação – Entrega 2**

Este repositório contém a documentação, diagramas e protótipos relacionados ao Sistema Acadêmico desenvolvido na disciplina de Projeto Integrador.  
A entrega inclui: prototipação das telas, casos de uso, diagramas UML e estrutura do sistema definida na primeira fase.

---

# 👥 Integrantes do Grupo
STEVEN MACHADO OLIVEIRA PAN BARREDA
LEONARDO AMARAL DE SOUZA
GERSON DA SILVA COSTA
JOHAN PINTO TRAPP
PEDRO SOUZA BRANDAO
LUCAS FILIPE FERREIRA RODRIGUES
THAIS ISABELLE DOS SANTOS CHAGAS

> **Substitua pelos nomes reais da equipe.**

---

# 🧭 Sobre o Sistema

Este projeto representa um **Sistema Acadêmico Completo**, permitindo que diferentes tipos de usuários realizem operações específicas:

- Funcionário: rotina de trabalho  
- Professor: controle de aulas  
- Aluno: acesso a disciplinas, aulas e materiais  
- Fornecedor: acesso ao depósito e gestão de pedidos  
- Administrador: gestão acadêmica, administrativa e de recursos  

Os protótipos foram desenvolvidos com base nos casos de uso e na modelagem UML criada na Etapa 1.

---

# 📂 Estrutura do Repositório

```
/docs/diagramas/      → imagens dos diagramas UML (Entrega 1)
/docs/prototipos/     → imagens das telas do protótipo (Entrega 2)
/figma/               → arquivo .fig exportado
README.md             → documentação geral
```

---

# 🎯 Casos de Uso (Etapa 1)

A seguir, os casos de uso formalizados na fase anterior.  
As imagens dos diagramas estarão na pasta: `/docs/diagramas/`.

## ✔ Caso 01 – Fazer Login  
Atores: Funcionário, Fornecedor, Professor, Aluno, Administrador  
Pré-condição: possuir credenciais válidas  
Pós-condição: acesso liberado ao sistema  

**Fluxo principal:**  
1. Sistema solicita login e senha  
2. Usuário informa credenciais  
3. Sistema valida e concede acesso  

**Fluxos alternativos:**  
- Credenciais inválidas → erro  
- Esqueceu a senha → tela de recuperação  

---

## ✔ Caso 02 – Abrir Rotina (Funcionário)
O funcionário visualiza suas tarefas do dia.  
Pode haver tarefas pendentes ou não.

---

## ✔ Caso 03 – Controle de Aula (Professor)
Permite:  
- Entrar na sala de aula  
- Gerenciar materiais  
- Realizar aula ao vivo  
- Consultar histórico  

---

## ✔ Caso 04 – Acessar Depósito (Fornecedor)
O fornecedor pode:  
- Visualizar pedidos  
- Realizar entrega  
- Cancelar entrega  
- Emitir nota fiscal  

---

## ✔ Caso 05 – Acessar Aulas (Aluno)
O aluno visualiza as disciplinas e pode:  
- Assistir aula ao vivo/gravada  
- Baixar material  

---

## ✔ Caso 06 – Gestão Acadêmica (Administrador)
Inclui:  
- Gerenciar Cursos  
- Gerenciar Disciplinas  
- Gerenciar Professores  

---

## ✔ Caso 07 – Gestão de Recursos (Administrador)
Inclui:  
- Gerenciar Materiais  
- Gerenciar Pedidos  
- Controle de Estoque  

---

## ✔ Caso 08 – Gestão Administrativa (Administrador)
Inclui:  
- Gerenciar Usuários  
- Gerenciar Permissões  
- Gerenciar Fornecedores  

---

# 🖼 Protótipos (Etapa 2)

Todos os protótipos foram criados no **Figma**, seguindo a estrutura definida nos casos de uso.

### 🔗 Link para o protótipo no Figma (visualização ao vivo):
https://www.figma.com/proto/gYHeAAPxZSTaMT0Iq0XM2v/Untitled?node-id=0-1&t=UhhyRwrwI3yR5hYl-1

### 📌 Telas incluídas no protótipo:
- Tela de Login  
- Dashboard Funcionário  
- Dashboard Fornecedor  
- Dashboard Professor  
- Dashboard Aluno  
- Dashboard Administrador  
- Cadastro de Pessoa Física  
- Cadastro de Pessoa Jurídica  
- Cadastro de Professores  
- Cadastro de Fornecedores  
- Cadastro de Alunos  

> As imagens PNG das telas estão disponíveis em `/docs/prototipos/`.

---

# 🛠 Ferramentas Utilizadas

- **Figma** → prototipação das telas  
- **Miro / Figma** → diagramas UML  
- **GitHub** → versionamento e entrega  
- **Markdown** → documentação  

---

# 📄 Como executar/visualizar o projeto

Este repositório não contém código-fonte, pois esta fase exige apenas:  
✔ documentação  
✔ diagramas UML  
✔ protótipos visuais  

Para visualizar:  
1. Abra o README  
2. Acesse a pasta **/docs/prototipos/**  
3. Acesse o link do Figma  

---

# 📜 Licença
Uso acadêmico — Projeto Integrador SENAC.
