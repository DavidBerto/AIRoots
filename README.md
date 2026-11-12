<div align="center">
# 🌱 AI Roots
 
**Matemática de verdade, explicada de um jeito que dá vontade de entender.**
 
Aqui fica todo o código das lives e dos vídeos do canal: notebooks, scripts e projetos, comentados do jeito que a gente explica em aula.
 
[![YouTube](https://img.shields.io/badge/YouTube-AI%20Roots-FF0000?style=for-the-badge&logo=youtube&logoColor=white)][https://www.youtube.com/@AIRoots-DavidFarias](https://www.youtube.com/@AIRoots-DavidFarias)
[![Instagram](https://img.shields.io/badge/Instagram-@airoots-E4405F?style=for-the-badge&logo=instagram&logoColor=white)][https://www.instagram.com/airootsoficial/](https://www.instagram.com/airootsoficial/)
 
</div>
---
 
## 👋 Chega mais
 
Seja muito bem-vindo, viu?
 
Se você chegou até aqui, provavelmente já passou por isso: o modelo funcionou lindo no notebook e, quando foi pra produção, tudo virou outra coisa. Ou você usa uma técnica há anos e, no fundo, nunca entendeu direito **por que** ela funciona.
 
O AI Roots existe pra isso. A ideia é simples:
 
- **Intuição primeiro, fórmula depois.** A gente monta a imagem na cabeça antes de jogar notação na tela.
- **Mecanismo antes da ferramenta.** Antes de importar a lib, a gente entende o que acontece por baixo.
- **Conhecimento de trincheira.** O que funciona (e o que quebra) quando o projeto é de verdade, com cliente, prazo e servidor caindo às 3 da manhã.
- **Sem hype.** Nada de "o segredo que ninguém te conta" nem "isso vai mudar sua vida". Matemática honesta, código que roda, e quando algo é estimativa, a gente fala que é estimativa.
Aqui não tem pergunta boba. Tem gente sênior revisitando fundamento, gente pleno subindo de nível e todo mundo aprendendo junto. Pode chegar.
 
---
 
## 📅 Lives toda segunda-feira
 
| | |
|---|---|
| 🗓️ **Quando** | Toda **segunda-feira** |
| ⏰ **Horário** | **20h00** (horário de Brasília) |
| 📍 **Onde** | [Canal do YouTube](https://www.youtube.com/@AIRoots-DavidFarias) |
| 💻 **Formato** | Mão no código: live coding, projeto prático, do conceito à implementação |
 
### ☕ E depois da live?
 
No final de toda live tem um **bate-papo aberto e tira-dúvidas, sem gravação**.
 
É o momento de perguntar sobre o projeto do seu trabalho, aquela dúvida que você ficou com vergonha de mandar no chat, carreira, entrevista, o que for. Sem câmera gravando, sem corte pro YouTube, só conversa de gente que trabalha com isso.
 
> 💡 **Dica:** esse momento não fica salvo em lugar nenhum. Se quiser participar, tem que estar lá ao vivo. 😉
 
---
 
## 📂 Como o repositório está organizado
 
```
ai-roots/
├── lives/                    # Código das lives de segunda-feira
│   ├── 01-nome-da-live/
│   │   ├── README.md         # Resumo, link da gravação e o que você vai aprender
│   │   ├── notebook.ipynb    # Código da live, comentado
│   │   └── requirements.txt  # Dependências específicas
│   └── ...
│
├── videos/                   # Código dos vídeos do YouTube
│   ├── nome-do-video/
│   │   ├── README.md
│   │   ├── notebook.ipynb
│   │   └── requirements.txt
│   └── ...
│
└── README.md                 # Você está aqui 👋
```
 
Cada pasta tem o próprio `README.md` com:
 
- 🎥 link para a gravação (live ou vídeo)
- 🎯 a ideia central em uma frase
- 📦 dependências e versões
- ▶️ como rodar
---
 
## 🚀 Rodando o código
 
O padrão aqui é: **roda do começo ao fim, em ambiente limpo, sem surpresa.** Toda demo tem semente fixa (`seed`), versão das bibliotecas e pelo menos um gráfico que explica o mecanismo, não só enfeita.
 
```bash
# 1. Clone o repositório
git clone COLE_AQUI_A_URL_DO_REPOSITORIO.git
cd ai-roots
 
# 2. Entre na pasta da live ou do vídeo que você quer
cd lives/01-nome-da-live
 
# 3. Crie um ambiente virtual (recomendado)
python -m venv .venv
source .venv/bin/activate        # Linux / macOS
# .venv\Scripts\activate         # Windows
 
# 4. Instale as dependências
pip install -r requirements.txt
 
# 5. Abra o notebook
jupyter lab
```
 
> Prefere não instalar nada? A maioria dos notebooks roda direto no **Google Colab**. Abre lá e manda bala.
 
### Deu erro?
 
Acontece, né? Antes de qualquer coisa:
 
1. Confere se a versão do Python e das libs bate com o `requirements.txt`.
2. Dá uma olhada nas [Issues](../../issues), porque alguém pode ter passado pela mesma coisa.
3. Não achou? **Abre uma issue** contando o que você rodou, o erro completo e seu ambiente. A gente resolve junto.
---
 
## 🤝 Contribuindo
 
Achou um bug? Tem uma versão mais elegante de algum trecho? Rodou o código com outro dataset e descobriu algo interessante?
 
Manda! Pull requests e issues são muito bem-vindos. Só pedimos:
 
- **Comentário explica a decisão**, não a sintaxe óbvia.
- **Código que roda**, nada de pseudocódigo disfarçado.
- **Respeito sempre.** Aqui todo mundo está aprendendo, inclusive quem ensina.
---
 
## 📺 Acompanhe o AI Roots
 
| Plataforma | Link |
|---|---|
| ▶️ **YouTube** | [https://www.youtube.com/@AIRoots-DavidFarias](https://www.youtube.com/@AIRoots-DavidFarias) |
| 📸 **Instagram** | [https://www.instagram.com/airootsoficial/](https://www.instagram.com/airootsoficial/) |
 
Se esse conteúdo te ajudou, deixa uma ⭐ no repositório. Parece pouco, mas ajuda mais gente boa a chegar até aqui.
 
---
 
<div align="center">
**Feito com café, matemática e muita vontade de que você não cometa os erros que a gente já cometeu.**
 
*David Farias · AI Roots*
 
Te vejo segunda, às 20h. 🌱
 
</div>