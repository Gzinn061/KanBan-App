 KanBan-App

## Descrição do Projeto
Este é um aplicativo simples de gerenciamento de tarefas no estilo Kanban, que permite adicionar, editar, mover e excluir tarefas entre diferentes colunas: "Para Fazer", "Em Progresso", "Revisar" e "Feito". O aplicativo foi desenvolvido utilizando HTML, CSS e JavaScript e apresenta um layout responsivo, que se adapta bem a dispositivos móveis e desktops.

## Tecnologias Utilizadas

### HTML
A estrutura HTML organiza o layout das colunas e tarefas. É utilizada uma marcação semântica e minimalista para garantir a acessibilidade e a fácil interpretação do conteúdo por diferentes navegadores e dispositivos【7†source】.

### CSS
Para o estilo visual, foram utilizados:
- **CSS Custom Properties (Variáveis)**: permitem uma personalização fácil de cores e tamanhos, facilitando ajustes futuros;
- **Responsividade**: o layout é responsivo, adaptando-se ao tamanho da tela usando flexbox e media queries【9†source】;
- **Animações e Transições**: algumas animações suavizam transições entre elementos, melhorando a experiência do usuário;
- **Ícones**: são usados ícones do Bootstrap Icons, proporcionando uma interface mais intuitiva【9†source】.

### JavaScript
JavaScript adiciona funcionalidade dinâmica ao projeto, permitindo:
- **Arrastar e Soltar**: implementação de uma interface de arrastar e soltar para mover tarefas entre as colunas【8†source】;
- **Modificações Dinâmicas de Tarefas**: adicionar, editar e excluir tarefas em tempo real;
- **Contagem de Tarefas**: atualiza automaticamente a contagem de tarefas em cada coluna;
- **Confirmação de Exclusão**: uma modal de confirmação é exibida antes de excluir qualquer tarefa, garantindo maior segurança contra remoções acidentais【8†source】.

## Legibilidade e Otimização do Código
O projeto segue práticas recomendadas para melhorar a legibilidade e otimização:
- **Organização Modular**: o código JavaScript é estruturado em funções modulares e event listeners, o que facilita o entendimento e a manutenção;
- **Uso de Observers**: um `MutationObserver` monitora alterações de tarefas em tempo real, mantendo a contagem precisa em cada coluna sem sobrecarregar a página【8†source】;
- **Código CSS e HTML Limpos**: o CSS utiliza variáveis para consistência e o HTML é escrito com uma estrutura simples, focada em acessibilidade e semântica【9†source】.

## Créditos
Desenvolvido por Guilherme Nunes, 2024.

