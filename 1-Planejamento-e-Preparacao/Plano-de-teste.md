# **Plano de Testes - GM Pedidos**

## **Informações Gerais**
- **Nome do Projeto:** GM Pedidos  
- **Versão do Plano de Teste:** 1.0  
- **Data de Criação:** 04/12/2024  
- **Gerente de Testes:** Victor Queiroz Barbosa  
- **Equipe de Testes:** Illgner Anderson, João Victor Vasconcelos, Victor Gabriel Araújo e Victor Queiroz Barbosa  

---

## **Escopo e Objetivo**
Este plano de testes visa validar a usabilidade e funcionalidades principais do aplicativo **GM Pedidos**, desenvolvido em Delphi, focado no gerenciamento de pedidos de delivery. Serão avaliadas a facilidade de uso, navegabilidade e eficiência das operações de cadastro de produtos, definição de preços, imagens e configurações do negócio.  

---

## **Características do Produto a Serem Testadas**
- Cadastro de produtos (nome, preço, imagem).  
- Configuração de informações do negócio (nome e imagem).  
- Navegação entre telas e menus.  
- Validação de entradas (dados válidos e inválidos).  
- Feedback visual e mensagens de erro.  

---

## **Abordagem a Ser Utilizada**
| **Descrição**           | **Detalhes**                  |
|--------------------------|-------------------------------|
| **Objetivo**             | Avaliar usabilidade e funcionalidades críticas. |
| **Técnica**              | Caixa Preta                  |
| **Estágio do Teste**     | Aceitação                    |
| **Método**               | Teste de usabilidade com ensaio de interação. |
| **Ferramentas Utilizadas** | WebCam ou celular para gravação do usuário. |

---

## **Itens a Serem Testados**
- Cadastro, edição e exclusão de produtos.  
- Configuração das informações do negócio.  
- Validação de dados inválidos (campos obrigatórios).  
- Navegação entre telas.  

---

## **Cronograma**
| **Etapa**                                | **Período**            |  
|------------------------------------------|------------------------|  
| Revisão final e configuração do ambiente | **04/12/2024**         |  
| Execução dos testes                      | **05/12/2024 a 08/12/2024** |  
| Análise dos resultados e relatórios      | **08/12/2024**         |  
| Aplicação do formulário (aceitação)      | **08/12/2024**         |  

---

## **Pessoal Responsável**
- **Gerente de Testes:** Victor Queiroz Barbosa  
- **Testadores:** Illgner Anderson, João Victor Vasconcelos, Victor Gabriel Araújo e Victor Queiroz Barbosa  

---

## **Riscos Associados**
- Falhas de gravação nos dispositivos (webcam/celular).  
- Erros inesperados no ambiente de testes.  
- Limitado número de testadores para cobrir fluxos adicionais.  

---

## **Especificação dos Casos de Testes**

### **Caso de Teste 1**  
- **Identificador:** CT-01  
- **Descrição:** Cadastro de produto com todas as informações válidas.  
- **Entradas:** Nome: "Produto A", Preço: R$50, Imagem: "imagem.jpg".  
- **Resultados Esperados:** Produto cadastrado com sucesso e listado na tela principal.  
- **Critérios de Aprovação:** Informações salvas corretamente e visíveis na interface.  

---

### **Caso de Teste 2**  
- **Identificador:** CT-02  
- **Descrição:** Cadastro de produto sem preencher o nome.  
- **Entradas:** Nome: "", Preço: R$50, Imagem: "imagem.jpg".  
- **Resultados Esperados:** Mensagem de erro indicando o campo obrigatório.  
- **Critérios de Aprovação:** Sistema exibe mensagem clara para o usuário.  

---

### **Caso de Teste 3**  
- **Identificador:** CT-03  
- **Descrição:** Cadastro de produto com preço negativo.  
- **Entradas:** Nome: "Produto B", Preço: -R$10, Imagem: "imagem.jpg".  
- **Resultados Esperados:** Mensagem de erro indicando valor inválido.  
- **Critérios de Aprovação:** Sistema não aceita o valor e informa ao usuário.  

---

### **Caso de Teste 4**  
- **Identificador:** CT-04  
- **Descrição:** Alteração de nome do negócio.  
- **Entradas:** Nome anterior: "Loja X", Nome novo: "Loja Y".  
- **Resultados Esperados:** Nome alterado e exibido corretamente na interface.  
- **Critérios de Aprovação:** Nome do negócio atualizado sem erros.  

---

### **Caso de Teste 5**  
- **Identificador:** CT-05  
- **Descrição:** Excluir produto do cadastro.  
- **Entradas:** Produto selecionado: "Produto A".  
- **Resultados Esperados:** Produto removido e não listado na tela.  
- **Critérios de Aprovação:** Produto excluído com sucesso e interface atualizada.  

---

### **Caso de Teste 6**  
- **Identificador:** CT-06  
- **Descrição:** Navegação entre telas do sistema.  
- **Entradas:** Ações de clique nos menus.  
- **Resultados Esperados:** Sistema alterna entre telas sem erros ou lentidão.  
- **Critérios de Aprovação:** Navegação fluida e sem bugs.  

---

### **Caso de Teste 7**  
- **Identificador:** CT-07  
- **Descrição:** Inserir imagem inválida no cadastro de produto.  
- **Entradas:** Nome: "Produto C", Preço: R$30, Imagem: "arquivo.pdf".  
- **Resultados Esperados:** Sistema rejeita imagem e exibe mensagem de erro.  
- **Critérios de Aprovação:** Imagem inválida não é aceita.  

---

### **Caso de Teste 8**  
- **Identificador:** CT-08  
- **Descrição:** Cadastro de produto sem preencher o preço.  
- **Entradas:** Nome: "Produto D", Preço: "", Imagem: "imagem.jpg".  
- **Resultados Esperados:** Mensagem de erro indicando campo obrigatório.  
- **Critérios de Aprovação:** Sistema impede cadastro sem preço válido.  

---

### **Caso de Teste 9**  
- **Identificador:** CT-09  
- **Descrição:** Configuração de imagem do negócio.  
- **Entradas:** Imagem válida: "logo.jpg".  
- **Resultados Esperados:** Imagem salva e exibida corretamente.  
- **Critérios de Aprovação:** Interface reflete a imagem configurada sem erros.  

---

### **Caso de Teste 10**  
- **Identificador:** CT-10  
- **Descrição:** Pesquisa de produto na lista cadastrada.  
- **Entradas:** Termo de busca: "Produto A".  
- **Resultados Esperados:** Produto correspondente listado na tela.  
- **Critérios de Aprovação:** Sistema exibe produtos corretamente com base na busca.  

---
## **Casos de Teste e Classes de Equivalência**

| **Caso de Teste**                       | **Entrada**                | **Classe Válida**                                                              | **Classe Inválida**                                                     |
|-----------------------------------------|----------------------------|---------------------------------------------------------------------------------|-------------------------------------------------------------------------|
| **1 - Finalizar pedido com cupom de desconto** | Cupom de Desconto          | Cupom válido e ativo (ex: "DESCONTO10", "FRETEGRATIS")                         | Cupom inválido ou expirado (ex: "DESCONTO15", "INVALIDO", vazio)       |
|                                         | Valor do Pedido            | Pedido com valor superior a R$50,01                                            | Pedido com valor igual ou inferior a R$50,00                            |
|                                         | Status do Cupom            | Cupom ativo                                                                   | Cupom expirado ou inativo                                               |
| **2 - Cadastro de produto**            | Nome do Produto            | Nome válido com até 50 caracteres                                              | Nome vazio ou com mais de 50 caracteres                                 |
|                                         | Preço do Produto           | Preço positivo superior a 0 (ex: R$10,00, R$200,00)                           | Preço negativo ou igual a 0 (ex: -R$10,00, R$0,00)                     |
|                                         | Imagem do Produto          | Imagem no formato JPEG ou PNG com tamanho aceitável (ex: 1MB)                  | Imagem no formato inválido (ex: GIF, BMP) ou imagem de tamanho muito grande (>10MB) |
| **3 - Cadastro de usuário**            | Nome Completo              | Nome válido com até 100 caracteres                                             | Nome vazio ou muito curto (menos de 3 caracteres)                       |
|                                         | E-mail                     | E-mail com formato correto (ex: "usuario@dominio.com")                         | E-mail inválido ou vazio (ex: "usuario@dominio", "usuario@.com", vazio) |
|                                         | Senha                      | Senha válida com pelo menos 8 caracteres, incluindo números e letras           | Senha com menos de 8 caracteres ou sem números/ letras                   |
| **4 - Adicionar item ao carrinho**     | Quantidade de Itens        | Quantidade positiva e maior que 0 (ex: 1, 2, 3)                               | Quantidade negativa ou igual a 0 (ex: -1, 0)                           |
|                                         | Produto                    | Produto disponível no estoque                                                 | Produto fora de estoque                                                 |
| **5 - Finalizar pedido sem cupom**     | Pedido com valor superior a R$50,01  | Pedido com valor superior a R$50,01                                            | Pedido com valor inferior ou igual a R$50,00                            |
|                                         | Status de pagamento        | Pagamento aprovado                                                            | Pagamento reprovado                                                     |
| **6 - Atualizar dados do produto**     | Nome do Produto            | Nome válido com até 50 caracteres                                              | Nome vazio ou com mais de 50 caracteres                                 |
|                                         | Preço do Produto           | Preço superior a 0,00                                                          | Preço negativo ou 0,00                                                   |
|                                         | Quantidade disponível      | Quantidade de produto maior que 0                                              | Quantidade de produto igual a 0                                         |
| **7 - Remover produto do carrinho**    | Produto no Carrinho        | Produto presente no carrinho de compras                                        | Produto não está no carrinho                                            |
|                                         | Quantidade no Carrinho     | Quantidade maior que 0                                                        | Quantidade igual a 0 ou negativa                                        |
| **8 - Alterar endereço de entrega**    | Endereço de Entrega        | Endereço completo e válido (ex: Rua X, nº 100, Bairro Y, Cidade Z)             | Endereço inválido ou incompleto (ex: Rua X, nº 100, Bairro Y)          |
|                                         | CEP                        | CEP válido (ex: 12345-678)                                                    | CEP inválido (ex: 12345678, vazio)                                      |
| **9 - Cadastro de pagamento**          | Cartão de Crédito          | Número de cartão válido (ex: 4111 1111 1111 1111)                             | Número de cartão inválido (ex: 1234 5678 8765 4321, vazio)            |
|                                         | Data de Vencimento         | Data de vencimento válida (ex: 12/25)                                          | Data de vencimento inválida (ex: 13/99, mês 0)                         |
| **10 - Buscar produtos no catálogo**   | Palavra-chave              | Palavra-chave válida (ex: "camisa", "notebook", "smartphone")                  | Palavra-chave inválida ou vazia (ex: "1234", vazio)                     |
|                                         | Categoria                  | Categoria válida (ex: "eletrônicos", "roupas", "acessórios")                   | Categoria inválida ou não existente (ex: "brinquedos", "gadgets")      |

---
## **Formulário de Aceitação**
As perguntas a seguir usarão a escala de 1 (Discordo totalmente) a 5 (Concordo totalmente).  

### **Perguntas**
1. Achei o aplicativo fácil de usar.  
2. A navegação entre as telas foi intuitiva.  
3. A aparência do aplicativo é agradável e profissional.  
4. As informações exibidas no aplicativo são claras e fáceis de entender.  
5. O aplicativo responde rapidamente às minhas ações.  
6. O processo de cadastro de produtos foi simples e direto.  
7. Foi fácil alterar informações de um produto cadastrado.  
8. Configurar o nome e a imagem do negócio foi fácil e sem complicações.  
9. O aplicativo exibiu mensagens claras ao inserir dados inválidos.  
10. Recebi notificações ou mensagens claras ao completar ações no sistema.  
11. A funcionalidade de busca encontrou os produtos esperados de forma eficaz.  
12. Excluir produtos foi um processo simples e direto.  
13. O layout do aplicativo se ajusta bem ao redimensionar a janela.  
14. Consegui utilizar o aplicativo com o teclado ou sem precisar de mouse.  
15. Estou satisfeito com a experiência geral de uso do aplicativo.  
