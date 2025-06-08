# Projeto CineVerso

 **Título do Projeto**: CineVerso Interativo  
 
 **Descrição**: Este projeto visa desenvolver um website interativo que busca facilitar a descoberta de novos títulos e proporcionar uma experiência divertida e personalizada para os usuários, unindo tecnologia, interatividade e cultura pop.  
 
 Planejamos implementar três funcionalidades principais:  
 1. Um chatbot que recomenda filmes e séries com base nas preferências do usuário.
 2. Um quiz interativo com perguntas sobre filmes e séries.
 3. Tabelas com 10 sugestões de filmes de 7 gêneros distintos (comédia, terror, ação, ficção, drama, romance, documentário), atualizada aleatoriamente com dados da API do TMDB.
   
**Tecnologias Utilizadas:**  
- Frontend: HTML, CSS, JavaScript
- Backend: Node.js 
- Chatbot: Python 
- APIs: The Movie Database (TMDB)

# Como Rodar o Projeto

**1. Instale as dependências em um terminal integrado a raiz do projeto:**

 *pip install flask flask-cors requests sentence-transformers python-dotenv*

 *npm install express dotenv http-proxy-middleware*

   
**3. Inicie o servidor:**
    
Depois de instalar todas as dependências, você precisará executar os dois servidores simultaneamente em dois terminais separados a partir da pasta raiz do projeto.

Terminal 1 (Node.js):

*node server.js*

Terminal 2 (Python):
*python chatbot.py*

Com ambos os servidores rodando, clique na URL *http://localhost:3000* para abrir o site no seu navegador.


