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

