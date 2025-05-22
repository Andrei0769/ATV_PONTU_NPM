# ⚽ Sistema de Gestão de Jogadores de Futebol

Projeto finalizado com sucesso ✅  
Este sistema tem como objetivo gerenciar jogadores de futebol, permitindo o **cadastro**, **listagem** e **visualização de detalhes** de jogadores através de integração com uma **API REST**.

---

## 🚀 Funcionalidades

- **Tela Inicial:**  
  Exibe o logo do time e oferece navegação para as demais páginas.

- **Cadastro de Jogador:**  
  Formulário para inserir os dados do jogador:
  - Nome  
  - Sexo  
  - Idade  
  - Altura  
  - Peso  
  - Posição  
  - Número da camisa  

- **Lista de Jogadores:**  
  Mostra todos os jogadores cadastrados, com as principais informações e opção de visualizar detalhes.

---

## 🗂️ Estrutura das Páginas

- `Home.js` – Tela inicial com logo e menu  
- `CadastroJogador.js` – Tela de cadastro com formulário  
- `ListaJogadores.js` – Tela com listagem e detalhes dos jogadores

---

## 🧾 Exemplo de Dados do Jogador

```json
{
  "id": 1,
  "nome": "João da Silva",
  "sexo": "Masculino",
  "idade": 22,
  "altura": 1.80,
  "peso": 75,
  "posicao": "Atacante",
  "numeroCamisa": 10
}
