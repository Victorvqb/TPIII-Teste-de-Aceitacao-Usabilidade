# Planejamento do Teste de Usabilidade

## Descrição

**Nome do produto que está sendo testado**:  
GM Pedidos (https://versao.gmpedidos.com/setup-gmpedidos.exe)

**Descrição do sistema**:  
Sistema voltado para a gestão de pedidos de delivery. Suas funcionalidades principais incluem o cadastro e gerenciamento de produtos e a configuração de informações do negócio.

**Data do teste**:  
08/12/2024

**Localização do Teste**:  
Google Meet

**Formato do teste**:  
Remoto

**Tempo de execução**:  
15 minutos

**Discentes**:  
- Victor Gabriel  
- Victor Barbosa  
- Illgner Anderson  
- João Victor  

---

## Cronograma

| **Descrição**                                 | **Data**      |
|------------------------------------------------|---------------|
| Planejar e Preparar o Teste de Usabilidade     | 23/11/2024    |
| Elaboração do Formulário na plataforma “Forms” | 23/11/2024    |
| Criação do repositório “GitHub”                | 23/11/2024    |
| Teste piloto                                   | 08/12/2024    |
| Execução do teste de usabilidade               | 08/12/2024    |
| Análise dos Resultados                         | 09/12/2024    |
| Revisão e Entrega                              | 09/12/2024    |

---

## Objetivo

O objetivo principal do teste é avaliar se o sistema atende às expectativas do usuário final e os requisitos de usabilidade, com foco nos seguintes aspectos:

- **Eficiência**: Medir o tempo gasto e o sucesso nas tarefas realizadas.
- **Eficácia**: Avaliar se os usuários conseguem realizar as tarefas sem dificuldades significativas.
- **Satisfação**: Captar percepções gerais sobre a experiência com o sistema.

---

## Público-Alvo

O público-alvo do teste é composto por universitários do Centro de Tecnologia, tendo em vista a necessidade de garantir que o público atendesse as especificações aproximadas de um cenário real, onde o usuário tem habilidade e experiência com esse tipo de aplicação, com idades entre 18 e 45 anos. Eles foram selecionados devido à familiaridade com tecnologias digitais e pelo potencial de interagir com o aplicativo. Essa escolha busca garantir insights alinhados ao perfil esperado dos usuários.

---

## Tarefas

**Tarefas realizadas pelos usuários**: 

| **ID** | **Descrição de Tarefas**                                                        |
|--------|---------------------------------------------------------------------------------|
| 01     | Realizar login no sistema com os seguintes dados<br>Telefone: 92984383676<br>Senha: 123 |
| 02     | Cadastrar um Atendente, Editar o nome desse Atendente e Deletar o Atendente que acabou de criar |
| 03     | Editar Horário de funcionamento |
| 04     | Cadastrar um Bairro, Editar o nome desse Bairro e Deletar o Bairro que acabou de criar |
| 05     | Mudar status da empresa para “Estamos Fechado no Momento” |
| 06     | Cadastrar uma Categoria, Editar o nome dessa Categoria e Deletar a Categoria que acabou de criar |
| 07     | Emitir Relatório geral de Novembro |
| 08     | Cadastrar um Produto, Editar o nome desse Produto e Deletar o Produto que acabou de criar |

---

## Questionário

Foi elaborado um questionário para avaliar a experiência de uso do aplicativo de GM Pedidos, utilizando conceitos fundamentais de usabilidade. Os participantes responderam às perguntas após realizar testes em funcionalidades específicas do sistema, incluindo login, CRUD de entidades, configuração de horários e emissão de relatórios.  
O objetivo principal é medir a eficiência, eficácia e satisfação dos usuários ao interagir com as funcionalidades testadas, identificando possíveis melhorias para aprimorar a experiência geral. As perguntas foram desenvolvidas com base em princípios de usabilidade, alinhadas às boas práticas de UX (User Experience Design).  
O questionário pode ser acessado através deste link: [Formulário](https://forms.gle/4sc46y743rQwMzEs7)  
Os participantes foram instruídos a responder de acordo com a escala Likert, onde 1 representa “Discordo Totalmente” e 5 representa “Concordo Totalmente”.

### Escala de Classificação

- Discordo Totalmente
- Discordo Parcialmente
- Neutro
- Concordo Parcialmente
- Concordo Totalmente

### Perguntas

1. O processo de login foi fácil e direto.
2. Foi fácil cadastrar um novo atendente.
3. Alterar ou excluir bairros cadastrados foi intuitivo.
4. Configurar ou alterar o horário de funcionamento foi simples.
5. Alterar o status da empresa para “Estamos Fechado no Momento” foi simples e claro.
6. A funcionalidade para emitir relatórios foi intuitiva e atendeu às expectativas.
7. Cadastrar um novo produto foi simples e direto.
8. Excluir produtos foi um processo rápido e claro.
9. O aplicativo exibiu mensagens claras ao inserir dados inválidos ou realizar ações no sistema.
10. Estou satisfeito com a experiência geral de uso do aplicativo para as tarefas testadas.

---

## Métricas

- **Tempo Gasto**: Quantidade de tempo em segundos que um participante leva para completar uma tarefa específica.
- **Número de Erros**: Quantidade de vezes que o participante comete um erro ao realizar uma tarefa.
- **Número de Confusão**: Quantidade de vezes que o participante demonstra incerteza sobre qual ação tomar a seguir.
- **Número de Solicitação de Ajuda**: Quantidade de vezes que o Participante precisa solicitar ajuda para completar uma tarefa.

---

## Modelo de Tabela para Dados Quantitativos

| **Tarefa** | **Participante** | **M1 - Tempo Gasto** | **M2 - Número de Erros** | **M3 - Número de Confusão** | **M4 - Número de Solicitação de Ajuda** |
|------------|------------------|----------------------|--------------------------|-----------------------------|-----------------------------------------|
| Tarefa 1   | Nome do Participante | X                    | X                        | X                           | X                                       |
| ...        | ...              | ...                  | ...                      | ...                         | ...                                     |

---

## Modelo de Tabela para Dados Qualitativos

### Participante 1: Clara Letícia

| **ID** | **Descrição do Problema**                                         | **Fator de Usabilidade / Heurística Violada**            |
|--------|-------------------------------------------------------------------|----------------------------------------------------------|
| 1      | Proporções das janelas de alerta são grandes, enquanto a tela principal é pequena. | Estética e Design Minimalista                           |
| 2      | Menu para editar horário está em abas menores, dificultando a localização. | Reconhecimento em vez de Memorização                    |
| 3      | Tela de edição do horário de funcionamento é confusa e difícil de entender. | Consistência e Padrões                                  |
| 4      | Falha ao excluir bairro sem orientação clara sobre a necessidade de desativação. | Prevenção de Erros e Feedback do Sistema                |
| 5      | Palavras no menu para emitir relatórios não são claras, dificultando a execução da tarefa. | Compatibilidade entre o Sistema e o Mundo Real          |
| 6      | Botões de "Adicionar" são iguais para tarefas diferentes, causando confusão. | Consistência e Padrões                                  |

### Participante 2: Guilherme Nunes

| **ID** | **Descrição do Problema**                                         | **Fator de Usabilidade / Heurística Violada**            |
|--------|-------------------------------------------------------------------|----------------------------------------------------------|
| 7      | Menu para editar horário está em abas menores, dificultando a localização. | Reconhecimento em vez de Memorização                    |
| 8      | Falha ao excluir bairro sem orientação clara sobre a necessidade de desativação. | Prevenção de Erros e Feedback do Sistema                |
| 9      | Não foi possível alterar o status, sem mensagem clara indicando o motivo. | Visibilidade do Status do Sistema                       |

### Participante 3: Liliene Picanço

| **ID** | **Descrição do Problema**                                         | **Fator de Usabilidade / Heurística Violada**            |
|--------|-------------------------------------------------------------------|----------------------------------------------------------|
| 10     | Menu para editar horário está em abas menores, dificultando a localização. | Reconhecimento em vez de Memorização                    |
| 11     | Ficou confusa ao emitir relatório e selecionou outro mês achando que emitiu o correto. | Prevenção de Erros e Feedback do Sistema                |
| 12     | Botões iguais para tarefas diferentes, causando confusão e falha na execução da tarefa de cadastro de produto. | Consistência e Padrões                                  |

### Participante 4: Kayth Kariny

| **ID** | **Descrição do Problema**                                         | **Fator de Usabilidade / Heurística Violada**            |
|--------|-------------------------------------------------------------------|----------------------------------------------------------|
| 13     | Não encontrou a opção para editar o horário, acreditando que alterava mudando o status "Aberto/Fechado". | Compatibilidade entre o Sistema e o Mundo Real          |
| 14     | Não conseguiu excluir um bairro devido à falta de orientação clara sobre a necessidade de desativação. | Prevenção de Erros e Feedback do Sistema                |
| 15     | Ficou confusa ao emitir relatório e não entendeu a tela, desistindo da tarefa. | Compatibilidade entre o Sistema e o Mundo Real          |

---

## Análise Geral

Os dados quantitativos e qualitativos revelam os principais problemas enfrentados pelos participantes. Os mais recorrentes incluem:

1. **Confusão na Navegação**: Problemas em encontrar opções em menus menos evidentes (ex.: editar horários e emitir relatórios).
2. **Falta de Feedback Claro**: Mensagens insuficientes para orientar ações como excluir bairros ou lidar com falhas (ex.: erro de conexão).
3. **Inconsistência Visual**: Botões idênticos para tarefas diferentes criam confusão durante o cadastro e edição de produtos.

---

## Sugestões de Melhoria

1. **Redesenho do Layout**:
   - Organizar menus de forma mais intuitiva, destacando ações importantes (ex.: edição de horários).
   - Diferenciar botões com cores e ícones que representem claramente suas funções.

2. **Aprimoramento de Feedback ao Usuário**:
   - Inserir mensagens de erro detalhadas e proativas (ex.: "O bairro precisa ser desativado antes de excluir").
   - Confirmar ações realizadas corretamente com notificações visuais claras.

