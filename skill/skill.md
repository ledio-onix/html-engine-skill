---
name: html-engine
description: Cria, desenvolve e aprimora jogos 2D e 3D em um único arquivo HTML, priorizando qualidade visual, jogabilidade refinada e código robusto. Use quando o usuário solicitar a criação, programação, correção ou melhoria de um jogo desse tipo.
---

# Fluxo de trabalho
1. Identifique o estilo (exemplo: pixel art, 3d low poly, etc), o genero do jogo, mecânicas e preferencias do usuário
2. Planeje e execute, Revise o código para evitar bugs
3. Tome decisões técnicas, se achar que prefere fazer algo no lugar do que o usuário sugeriu, pergunte ao usuário antes de adicionar
4. Refine os gráficos, nunca entregue gráficos ruins e mal feitos
5. Depure o JS para verificar se à erros, caso houver erros, corrija-os assim que encontra-los
6. verifique no navegador disponível no ambiente as colisões, controles, interfaces e mecânicas, se algo não puder ser testado, avise o usuário e peça para ele mesmo testar
# Gráficos
## Gráficos 2D
- Priorize graficos bonitos usando o canvas 2D
- Mantenha personagens, cenarios e outros elementos coerrentes e na mesma resolução
## Gráficos 3D
- SEMPRE use WebGL 2 e evite bibliotecas externas que necessitam de download
- de atenção as sombras, objetos, materiais e texturas, não faça modelos mal feitos ou mal modelados
## geral
- Mantenha o consumo de memória baixo e taxa de quadros estável
# Arquitetura de jogos
- mantenha tudo em um único arquivo contendo html css e javascript, aplique as dependências dentro do mesmo arquivo
- organize e otimize o código, pois, o arquivo único mal otimizado pode acabar gerando mal desempenho
- evite códigos duplicados, variáveis globais desnecessárias
- Separe logicamente os sistemas de renderização, entrada do jogador, física, colisões, áudio, interface e gerenciamento de estados quando forem necessários
- prefira soluções simples, sem sacrificar qualidade do jogo
# jogabilidade e controles
- Priorize controles responsivos e intuitivos
- junto ao jogo, entregue dentro do próprio chat os comandos, facilitando os testes feitos pelo usuário
- priorize fluidez nos jogos
- implemente feedback visual e sonoro para ações importantes dentro do jogo
- implemente sistema de pausa, inicio, fim, reinicio e vitória quando fazer sentido para o jogo em que o usuário solicitou
