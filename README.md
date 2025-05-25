# 📊 Laboratório – Criando um Orçamento na AWS com Budget

![1](https://raw.githubusercontent.com/HalleyVeras/aws-budget-lab-developer-EDN/refs/heads/main/arquivos1/Banner_Budget.jpg)

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

![1](https://raw.githubusercontent.com/HalleyVeras/aws-budget-lab-developer-EDN/refs/heads/main/arquivos1/2025-05-25_15-58.png)
![1](https://raw.githubusercontent.com/HalleyVeras/aws-budget-lab-developer-EDN/refs/heads/main/arquivos1/2025-05-25_15-14.png)
![1](https://raw.githubusercontent.com/HalleyVeras/aws-budget-lab-developer-EDN/refs/heads/main/arquivos1/2025-05-25_15-21.png)

---

### 📝 Passo 2 – Criar um novo Budget

- Nomeie seu orçamento como: `meu-budget-seunome`.
- Insira seu e-mail para receber os alertas.
- Clique em **Criar orçamento**.

📸 **Print 2 – Tela de criação de orçamento com nome e e-mail preenchidos**  

![1](https://raw.githubusercontent.com/HalleyVeras/aws-budget-lab-developer-EDN/refs/heads/main/arquivos1/2025-05-25_15-29.png)
![1](https://raw.githubusercontent.com/HalleyVeras/aws-budget-lab-developer-EDN/refs/heads/main/arquivos1/2025-05-25_15-31.png)
![1](https://raw.githubusercontent.com/HalleyVeras/aws-budget-lab-developer-EDN/refs/heads/main/arquivos1/2025-05-25_15-32.png)
![1](https://raw.githubusercontent.com/HalleyVeras/aws-budget-lab-developer-EDN/refs/heads/main/arquivos1/2025-05-25_15-34.png)
![1](https://raw.githubusercontent.com/HalleyVeras/aws-budget-lab-developer-EDN/refs/heads/main/arquivos1/2025-05-25_15-36.png)
![1](https://raw.githubusercontent.com/HalleyVeras/aws-budget-lab-developer-EDN/refs/heads/main/arquivos1/2025-05-25_15-36_1.png)


---

### 🔍 Passo 3 – Editar e Configurar Alertas

- Defina o **Limite** como **10** e escolha **% do valor orçado**.
- No campo **Acionador**, mantenha a opção **Real**.
- Clique em **Próximo**.
- Na tela **Associar ações**, mantenha as opções padrão e clique em **Próximo**.
- Revise as configurações e clique em **Salvar**.

📸 **Print 3 – Configuração do alerta e revisão do orçamento**  

![1](https://raw.githubusercontent.com/HalleyVeras/aws-budget-lab-developer-EDN/refs/heads/main/arquivos1/2025-05-25_15-43.png)
![1](https://raw.githubusercontent.com/HalleyVeras/aws-budget-lab-developer-EDN/refs/heads/main/arquivos1/2025-05-25_15-45.png)
![1](https://raw.githubusercontent.com/HalleyVeras/aws-budget-lab-developer-EDN/refs/heads/main/arquivos1/2025-05-25_15-46.png)
![1](https://raw.githubusercontent.com/HalleyVeras/aws-budget-lab-developer-EDN/refs/heads/main/arquivos1/2025-05-25_15-46_1.png)

---

### ✅ Passo 4 – Revisar o Orçamento

- Volte à lista principal de orçamentos.
- Verifique as informações:
  - Nome do orçamento
  - Valor definido (US$ 10)
  - Valor usado

📸 **Print 4 – Resumo final do orçamento**  


![1](https://raw.githubusercontent.com/HalleyVeras/aws-budget-lab-developer-EDN/refs/heads/main/arquivos1/2025-05-25_15-47.png)

![1](https://raw.githubusercontent.com/HalleyVeras/aws-budget-lab-developer-EDN/refs/heads/main/arquivos1/2025-05-25_16-10.png)

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

