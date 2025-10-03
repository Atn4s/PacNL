# Trabalho NetLogo: Extensão do modelo Pac-Man
<div align="center">
   <img src="https://github.com/Atn4s/PacNL/blob/main/Pac-Man.png?raw=true">
</div>

- Trabalho realizado para a matéria de Sistemas Multiagentes utilizando a ferramenta NetLogo.

## 🎮 Sobre o Projeto

Uma implementação do clássico Pacman em NetLogo com um sistema de **Auto-Play**, expandindo o modelo original com modo de jogo automatico, personalização visual e opção de selecionar múltiplos mapas.

## 🔧 Desenvolvimento

O procedimento de Auto-Play foi desenvolvido com suporte da **IA Claude.AI (Sonnet 4.5)** como uma ferramenta de suporte. 
A base de código e lógica principal foram criadas manualmente, utilizando a IA para refinamentos de sintaxe, melhorias e correções no modelo de agente do Pac-Man.

### Principais Modificações
- Sistema completo de Auto-Play
- Personalização visual do labirinto
- Múltiplos mapas selecionáveis
- Melhorias na interface e usabilidade

## 🎯 Estratégia da IA

A inteligência artificial segue uma **hierarquia de prioridades**:

- **1 - FUGIR de fantasmas perigosos ( considerando < 3 casas)** 
- **2 - PERSEGUIR fantasmas assustados ( com power-up)**
- **3 - Pegar POWER-UP se fantasma está próximo**
- **4 - Pegar BÔNUS ( considerando 10 casas)**
- **5 - Coletar pellets (preferir continuar na mesma direção)**

### Auto-Play
- **Toggle "Auto-Play?"**: Ativar/desativar modo automático
- A IA assume controle completo do Pacman

### Personalização
- **Sliders de cores RGB**: Customizar cor do labirinto
- **Seletor de mapa**: Escolher entre 5 mapas
- **Dificuldade**: Ajustar velocidade dos fantasmas

## 🛠️ Requisitos

- **NetLogo** disponível em https://www.netlogo.org/ 
- Arquivos de mapa `.csv` na mesma pasta do modelo

## 📁 Estrutura do Projeto
- PacNL/
- ├── Pac-Man.png # Imagem original da pasta do NetLogo do Pac-Man
- ├── PacMan_Extendido.nlogox # Modelo principal
- ├── pacmap1.csv # Mapa 1
- ├── pacmap2.csv # Mapa 2
- ├── pacmap3.csv # Mapa 3
- ├── pacmap4.csv # Mapa 4
- ├── pacmap5.csv # Mapa 5
- └── README.md # Este arquivo

## 🎮 Como Jogar

1. Abra o arquivo `PacMan_Extendido.nlogox` no NetLogo
2. Configure as preferências na interface:
   - Selecione o mapa desejado
   - Ajuste as cores do labirinto (opcional)
   - Defina a dificuldade
3. Clique em **"New"** para iniciar
4. Use **"Auto-Play?"** para modo automático ou controle manual

### Arquivos Modificados
- `pacman.nlogo` (modelo principal expandido)

## 📄 Licença Original!

![CC BY-NC-SA 3.0](https://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png)

Este modelo é licenciado sob a **Creative Commons Attribution-NonCommercial-ShareAlike 3.0 License**. 

Para visualizar uma cópia desta licença, visite:
https://creativecommons.org/licenses/by-nc-sa/3.0/

### 📚 Atribuições

**Software NetLogo:**
- Wilensky, U. (1999). NetLogo. http://ccl.northwestern.edu/netlogo/. 
- Centro de Aprendizagem Conectada e Modelagem Computacional, Universidade Northwestern, Evanston, IL.

**Modelo Original do Pacman:**
- Copyright 2001 Uri Wilensky

### 💼 Uso Comercial
NetLogo é um software livre para uso não-comercial sob os termos da GNU General Public License. Para informações sobre licenças comerciais do NetLogo ou modelos específicos, contacte: netlogo-commercial-admin@ccl.northwestern.edu
