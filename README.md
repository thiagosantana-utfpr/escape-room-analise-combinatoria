# 🔐 Escape Room: Análise Combinatória (Protocolo de Segurança)

Aplicação web interativa desenvolvida como projeto educacional para praticar **Análise Combinatória** por meio de uma dinâmica de *Escape Room* com temática de desbloqueio de portas blindadas.

🔗 **Jogar online (GitHub Pages):** [https://thiagosantana-utfpr.github.io/escape-room-analise-combinatoria/](https://thiagosantana-utfpr.github.io/escape-room-analise-combinatoria/)

---

## 🎯 Objetivo e Mecânica do Jogo

O jogador assume o papel de um agente tentando escapar de um complexo de segurança composto por **5 portas blindadas**. Para destravar cada cadeado e avançar de sala, é necessário resolver desafios matemáticos envolvendo diferentes técnicas de contagem.

### 🚪 As 5 Salas (Fases)
1. **Sala 1 — Princípio Fundamental da Contagem (PFC):** Decisões sequenciais, senhas, interruptores e configurações básicas.
2. **Sala 2 — Permutação Simples:** Anagramas sem repetição, ordenação de servidores e filas com restrições simples.
3. **Sala 3 — Permutação com Repetição e Arranjo Simples:** Sequências binárias, caminhos em grade, anagramas com letras repetidas e pódios.
4. **Sala 4 — Combinação Simples:** Escolha simultânea de disjuntores, comissões, subconjuntos e conexões de rede.
5. **Sala 5 — Restrições e Integração:** Problemas mistos envolvendo "pelo menos", elementos separados e combinação seguida de permutação.

---

## ✨ Funcionalidades

- **Painel de 5 Portas Blindadas:** Visualização em tempo real do progresso, mostrando portas trancadas, sala atual e cadeados destravados.
- **Banco com 50 Questões:** 10 questões por sala com resolução comentada passo a passo exibida após cada resposta.
- **Sistema de Áudio Dinâmico (Web Audio API):** Trilha sonora de suspense e efeitos sonoros de clique, acerto, erro e destravamento de porta, com botão de controle de volume/mudo integrado (sem dependência de arquivos MP3 externos).
- **Cronômetro e Pontuação:** Acompanhamento do tempo total de fuga e desempenho por sala.
- **Zero Dependências Externas:** Projeto 100% executado no navegador usando HTML5, CSS3 e JavaScript puro (Vanilla JS).

---

## 📂 Estrutura do Repositório

```text
escape-room-analise-combinatoria/
├── index.html           # Aplicação completa (interface, estilos, motor de áudio e lógica)
└── README.md            # Documentação do projeto
```

---

## 🚀 Como Executar Localmente

1. Clone este repositório:
   ```bash
   git clone https://github.com/thiagosantana-utfpr/escape-room-analise-combinatoria.git
   ```
2. Abra o arquivo `index.html` diretamente em qualquer navegador moderno (Chrome, Edge, Firefox ou Safari).

---

## 👨‍💻 Autor

Desenvolvido por **Thiago Santana** — Engenharia de Software / Computação (UTFPR - Campus Londrina).
