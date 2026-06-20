# 📝 Task Board - To-Do List

Um aplicativo/site de Lista de Tarefas (To-Do List) responsivo, moderno e funcional, desenvolvido com tecnologias web nativas. O projeto permite criar, editar, marcar como concluídas, filtrar e buscar tarefas, além de manter os dados salvos mesmo após fechar o navegador.

## Funcionalidades

* **Criação de Tarefas:** Adicione novas obrigações rapidamente à lista.
* **Edição em Tempo Real:** Atualize o texto de uma tarefa existente sem precisar recriá-la.
* **Persistência de Dados:** Integração com `localStorage` para salvar suas tarefas no navegador.
* **Filtros Avançados:** Visualize "Todos", apenas os "Feitos" ou os "A Fazer".
* **Busca Dinâmica:** Encontre tarefas digitando termos na barra de pesquisa (filtro em tempo real).
* **Interface Responsiva:** Layout totalmente adaptável para dispositivos móveis e desktops.

## Tecnologias Utilizadas

* **HTML5:** Estrutura semântica para melhor acessibilidade e SEO.
* **CSS3:** Estilização moderna utilizando Flexbox, Media Queries e variáveis visuais.
* **JavaScript (ES6):** Manipulação dinâmica do DOM, gerenciamento de eventos e persistência local.
* **Font Awesome:** Ícones vetoriais modernos para a interface do usuário.


## Estrutura de Arquivos

```text
├── css/
│   └── style.css       # Estilização completa e responsividade
├── img/
│   └── background.img.jpg  # Imagem de fundo otimizada
├── js/
│   └── scripts.js      # Lógica de funcionamento e LocalStorage
└── index.html          # Estrutura principal do app
```

## Preview do Projeto

<p align="center">
  <img width="45%" height="455" alt="preview1" src="https://github.com/user-attachments/assets/4e34a98c-6b8a-43a0-bb6b-ec01b432ee22" />
  <img width="45%" height="437" alt="preview2" src="https://github.com/user-attachments/assets/7ef59c84-b902-4ba3-ba7d-b8808047e9fb" />
  <img width="45%" height="590" alt="preview3" src="https://github.com/user-attachments/assets/79afb952-84dd-4a06-9494-ace7f3036949" />
  <img width="45%" height="568" alt="preview4" src="https://github.com/user-attachments/assets/244e5e47-0277-4a89-997f-777fb56e431b" />
  <img width="45%" height="422" alt="preview5" src="https://github.com/user-attachments/assets/97ee2e55-2789-4c95-9d1f-7b1b9cbf051c" />
<p/>

## Aprendizados e Clean Code

Durante o desenvolvimento deste projeto, foram aplicados conceitos importantes de:
  - Manipulação de estados no JavaScript sem frameworks.
  - Correção de vazamentos de memória na `localStorage` tratando retornos nulos.
  - Responsividade em CSS para evitar quebras em telas menores que 400px.
  - Correção de repetição e posicionamento de imagens de fundo (`background-size: cover` e `fixed`).
