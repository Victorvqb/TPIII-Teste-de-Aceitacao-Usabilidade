## **Analise de dados da Pesquisa**


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

# Análise Geral

Os dados qualitativos indicam que os participantes enfrentaram dificuldades significativas em diversas áreas de usabilidade do sistema. Os principais problemas identificados foram:

1. **Confusão na Navegação**:
   - Muitos participantes relataram dificuldades em encontrar funcionalidades importantes, como a edição de horários e a emissão de relatórios. A falta de clareza na localização dessas opções aumenta a carga cognitiva dos usuários e prejudica a eficiência e a fluidez da interação com o sistema.

2. **Falta de Feedback Claro**:
   - O sistema não fornece feedback suficiente sobre ações críticas, como a exclusão de bairros ou a alteração do status de uma funcionalidade. Isso gera incerteza e frustração, pois os usuários não têm informações suficientes sobre o que ocorreu ou o que devem fazer a seguir.

3. **Inconsistência Visual**:
   - O uso de botões idênticos para ações diferentes foi uma queixa recorrente, o que gerou confusão na execução de tarefas importantes, como o cadastro de produtos e a gestão de horários. A falta de diferenciação visual entre essas ações pode levar a erros de execução, comprometendo a experiência geral do usuário.

---

# Sugestões de Melhoria

Para melhorar a usabilidade do sistema e atender melhor às necessidades dos usuários, as seguintes sugestões são recomendadas:

## 1. Redesenho do Layout e Melhoria na Navegação
   - **Destacar Funcionalidades Cruciais**: Organizar e destacar de maneira mais visível as funcionalidades mais importantes, como a edição de horários, a emissão de relatórios e a exclusão de bairros. Uma reorganização dos menus para tornar essas opções mais acessíveis pode reduzir a confusão.
   - **Menu Intuitivo e Fluxos de Navegação**: Criar uma navegação mais fluida e intuitiva, utilizando menus suspensos, submenus e barras laterais para categorizar funções semelhantes. Além disso, a implementação de uma barra de pesquisa pode ajudar os usuários a encontrar rapidamente as funcionalidades que desejam.
   - **Ajuste nas Abas e Menu de Opções**: Reduzir o número de abas pequenas e compactas, reorganizando-as para facilitar o acesso às opções essenciais, como a edição de horários, em uma área mais visível e acessível.

## 2. Aprimoramento do Feedback ao Usuário
   - **Mensagens de Erro Claras e Proativas**: Fornecer mensagens de erro detalhadas e claras sempre que ocorrer um problema, como ao tentar excluir um bairro sem desativá-lo. Essas mensagens devem ser explicativas, oferecendo soluções ou sugestões sobre como corrigir o erro (ex.: "Para excluir o bairro, primeiro desative-o nas configurações de status").
   - **Confirmação de Ações e Sucesso**: Após ações importantes, como a alteração de horário ou a exclusão de dados, o sistema deve fornecer uma confirmação visual (ex.: "Horário editado com sucesso" ou "Bairro excluído com sucesso") para garantir que o usuário saiba que a ação foi realizada corretamente.
   - **Indicadores de Status em Tempo Real**: Para ações como a alteração de status ou a execução de relatórios, incluir indicadores de progresso e status em tempo real. Isso reduz a incerteza do usuário e fornece uma sensação de controle.

## 3. Melhoria na Consistência Visual e Funcional
   - **Diferenciação de Botões e Ações**: Alterar a aparência dos botões para refletir com mais clareza suas funções. Por exemplo, utilizar cores diferentes, ícones e textos específicos para cada ação (ex.: "Adicionar Produto", "Excluir Bairro", "Editar Horário") para evitar confusão entre as funções.
   - **Padrões Visuais e Funcionais Consistentes**: Garantir que todos os botões, menus e interações sigam padrões visuais e funcionais consistentes em todo o sistema. Isso significa que os botões de "Adicionar", por exemplo, devem ser visivelmente diferentes dependendo da tarefa que estão executando.
   - **Feedback Visual para Erros e Sucessos**: Além das mensagens de erro, incluir mudanças visuais nos elementos da interface (como bordas vermelhas ao redor de campos com erro) para tornar os problemas mais evidentes e facilitar a correção.

## 4. Aprimoramento na Comunicação do Sistema com o Usuário
   - **Utilização de Linguagem Clara e Simples**: Reformular as mensagens do sistema para uma linguagem mais direta e fácil de entender. Em vez de termos técnicos ou vagos, utilizar frases simples que descrevem claramente o que o usuário deve fazer.
   - **Guias e Tutoriais Contextuais**: Implementar guias contextuais ou tooltips que forneçam explicações rápidas sobre como usar funcionalidades avançadas (como a edição de horários ou a emissão de relatórios). Isso pode ser especialmente útil para novos usuários ou para aqueles que não têm familiaridade com o sistema.

---

# Questionário de Satisfação Pós-Teste

## Participantes e Respostas

| **Participante** | **Pergunta 1** | **Pergunta 2** | **Pergunta 3** | **Pergunta 4** | **Pergunta 5** | **Pergunta 6** | **Pergunta 7** | **Pergunta 8** | **Pergunta 9** |
|------------------|----------------|----------------|----------------|----------------|----------------|----------------|----------------|----------------|----------------|
| **1**            | 5              | 5              | 5              | 5              | 4              | 2              | 4              | 4              | 4              |
| **2**            | 5              | 5              | 1              | 2              | 1              | 4              | 4              | 3              | 2              |
| **3**            | 5              | 4              | 3              | 4              | 1              | 1              | 1              | 2              | 1              |
| **4**            | 3              | 5              | 5              | 3              | 5              | 5              | 5              | 2              | 4              |

## Pontuação Média

| **Pergunta** | **Média de Pontuação** | **Porcentagem de Satisfação** |
|--------------|------------------------|------------------------------|
| 1. Facilidade no Login | 4,5 | 90% |
| 2. Cadastro de Atendente | 4,75 | 95% |
| 3. Alteração/Exclusão de Bairros | 3,5 | 70% |
| 4. Alteração do Horário de Funcionamento | 3,5 | 70% |
| 5. Alteração de Status da Empresa | 3,75 | 75% |
| 6. Cadastro de Produto | 3,5 | 70% |
| 7. Exclusão de Produto | 3,5 | 70% |
| 8. Clareza nas Mensagens de Erro | 2,75 | 55% |
| 9. Satisfação Geral | 3,375 | 67,5% |

## Análise

### 1. Facilidade no Processo de Login (Pergunta 1):
- **Porcentagem**: **90%** dos participantes ficaram satisfeitos com a facilidade do login, mostrando que esse processo é intuitivo e direto.

### 2. Facilidade em Cadastrar um Novo Atendente (Pergunta 2):
- **Porcentagem**: **95%** dos participantes consideraram o processo de cadastro de um novo atendente fácil e eficiente, indicando uma boa usabilidade.

### 3. Facilidade para Alterar ou Excluir Bairros Cadastrados (Pergunta 3):
- **Porcentagem**: **70%** dos participantes acharam esse processo difícil ou confuso. Isso sugere que uma parte significativa dos usuários teve dificuldades em realizar essa tarefa.

### 4. Facilidade em Configurar ou Alterar o Horário de Funcionamento (Pergunta 4):
- **Porcentagem**: **70%** dos participantes também tiveram dificuldades nessa tarefa. Isso sugere que a interface para configurar ou alterar o horário de funcionamento precisa ser aprimorada para maior clareza.

### 5. Facilidade em Alterar o Status da Empresa para "Estamos Fechado no Momento" (Pergunta 5):
- **Porcentagem**: **75%** dos participantes acharam esse processo simples, mas ainda há uma margem para melhorar a clareza de como realizar essa ação.

### 6. Facilidade em Cadastrar um Novo Produto (Pergunta 6):
- **Porcentagem**: **70%** dos participantes acharam esse processo fácil, enquanto 30% encontraram dificuldades. Isso pode indicar que a interface para cadastro de produtos pode ser melhorada.

### 7. Facilidade para Excluir Produtos (Pergunta 7):
- **Porcentagem**: **70%** dos participantes acharam o processo de exclusão de produtos complicado, sugerindo que a interface precisa ser mais intuitiva.

### 8. Clareza nas Mensagens ao Inserir Dados Inválidos ou Realizar Ações no Sistema (Pergunta 8):
- **Porcentagem**: **55%** dos participantes ficaram insatisfeitos com a clareza das mensagens de erro, indicando uma área crítica para melhorias. O sistema precisa fornecer feedback mais claro e orientações sobre ações inválidas.

### 9. Satisfação Geral com a Experiência de Uso (Pergunta 9):
- **Porcentagem**: **67,5%** de satisfação média. Embora a maioria tenha ficado satisfeita com algumas funções, a experiência geral mostra uma necessidade de melhorias em várias áreas, especialmente nas tarefas mais complexas.

## Conclusão da Análise 

### Áreas de Força:
- **Login** e **Cadastro de Atendente** têm alta taxa de satisfação (90% e 95%), sugerindo que essas funcionalidades estão bem implementadas.

### Áreas de Oportunidade:
- **Alteração/Exclusão de Bairros** (70%) e **Alteração de Horário de Funcionamento** (70%) precisam ser simplificadas para aumentar a acessibilidade e clareza.
- **Clareza nas Mensagens de Erro** (55%) foi o ponto mais crítico, com a necessidade de melhorar a comunicação com o usuário.

## Sugestões de Melhoria

1. **Melhorar a Interface de Alteração e Exclusão de Bairros**: Criar uma navegação mais intuitiva e visível, garantindo que a ação de exclusão seja fácil de entender.
2. **Revisar o Fluxo de Alteração de Horário de Funcionamento**: Tornar a interface mais clara e intuitiva para facilitar a edição de horários.
3. **Aprimorar Feedback de Erro**: Fornecer mensagens de erro mais específicas e detalhadas, indicando claramente o que precisa ser corrigido.
4. **Ajustes na Exclusão de Produtos**: Diferenciar melhor as ações, criando botões mais claros e feedback visual mais eficaz.
