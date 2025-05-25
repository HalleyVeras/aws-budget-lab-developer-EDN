# 📊 Laboratório – Criando um Orçamento na AWS com Budget


**Curso: Developer – Escola da Nuvem**  
**Autor: Halley Veras**

Este repositório contém um **guia prático e ilustrado** para configurar um orçamento de gastos na AWS, usando o serviço **AWS Budgets**. Essa configuração é essencial para evitar surpresas na fatura e manter os custos sob controle, especialmente para quem está aprendendo e realizando testes na nuvem.

---

## 🎯 Objetivos

✅ Criar um orçamento com limite personalizado na AWS  
✅ Configurar alertas por e-mail com base em percentuais de uso  
✅ Validar a criação e receber notificações automáticas de gastos

---

## 📍 Cenário

Você é um estudante ou desenvolvedor iniciante que está utilizando a AWS para aprender. Vamos simular a criação de um **budget simples**, com limite de **US$ 10**, e um alerta quando **10% do valor** for atingido.

---

## 🚀 Passo a Passo

### 🏁 Passo 1 – Acessar o AWS Budgets

- Acesse o Console de Gerenciamento da AWS.
- Navegue até o serviço **AWS Budgets**.
- Clique em **Criar orçamento**.

📸 **Print 1 – Acessando o AWS Budgets e iniciando a criação de orçamento**  
_Aqui você pode inserir um print da tela inicial do AWS Budgets, com o botão “Criar orçamento” destacado._

---

### 📝 Passo 2 – Criar um novo Budget

- Nomeie seu orçamento como: `meu-budget-seunome`.
- Insira seu e-mail para receber os alertas.
- Clique em **Criar orçamento**.

📸 **Print 2 – Tela de criação de orçamento com nome e e-mail preenchidos**  
_Adicione aqui um print dessa tela com os campos destacados._

---

### 🔍 Passo 3 – Editar e Configurar Alertas

- Na lista de orçamentos, clique no nome do seu budget.
- Clique no botão **Editar** (canto superior direito).
- Role até a seção **Alerta #1**:
  - Defina o **Limite** como **10** e escolha **% do valor orçado**.
  - No campo **Acionador**, mantenha a opção **Real**.
- Clique em **Próximo**.
- Na tela **Associar ações**, mantenha as opções padrão e clique em **Próximo**.
- Revise as configurações e clique em **Salvar**.

📸 **Print 3 – Configuração do alerta e revisão do orçamento**  
_Aqui vai um print das configurações de alerta preenchidas e da tela de revisão._

---

### ✅ Passo 4 – Revisar o Orçamento

- Volte à lista principal de orçamentos.
- Verifique as informações:
  - Nome do orçamento
  - Valor definido (US$ 10)
  - Valor usado

📸 **Print 4 – Resumo final do orçamento**  
_Adicione o print com o orçamento criado, nome, valor e percentual de uso._

---

## 🎓 Conclusão

🎉 Parabéns por configurar seu **Budget na AWS**! Agora, você tem uma ferramenta proativa para controlar seus custos, evitar surpresas e agir rapidamente caso os gastos aumentem. Lembre-se de revisar seus budgets regularmente e ajustar os limites conforme necessário!

---

## 📬 Contato

Caso tenha dúvidas ou queira contribuir, fique à vontade para abrir uma issue ou entrar em contato.

---

## 📚 Referências

- [Documentação oficial AWS Budgets](https://docs.aws.amazon.com/pt_br/cost-management/latest/userguide/budgets-managing-costs.html)
- [Curso Developer – Escola da Nuvem](https://escoladanuvem.org)

