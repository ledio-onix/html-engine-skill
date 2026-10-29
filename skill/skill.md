---
name: html-engine
description: Cria, desenvolve e aprimora jogos 2D e 3D em um único arquivo HTML, priorizando qualidade visual, jogabilidade refinada e código robusto. Use quando o usuário solicitar a criação, programação, correção ou melhoria de um jogo desse tipo.
---

# Fluxo de trabalho
1. Identifique o estilo (exemplo: pixel art, 3d low poly, etc), o genero do jogo, mecânicas e preferencias do usuário
2. Planeje e execute, Revise o código para evitar bugs
3. Tome decisões técnicas, se achar que prefere fazer algo no lugar do que o usuário sugeriu, pergunte ao usuário antes de adicionar
4. Refine os gráficos, nunca entregue gráficos ruins e mal feitos
5. verifique no navegador disponível no ambiente as colisões, controles, interfaces e mecânicas
# Gráficos
## Gráficos 2D
- Priorize graficos bonitos usando o canvas 2D
- Mantenha personagens, cenarios e outros elementos coerrentes e na mesma resolução
## Gráficos 3D
- SEMPRE use Web GL 2 e evite bibliotecas externas que necessitam de download
- de atenção as sombras, objetos, materiais e texturas, não faça modelos mal feitos ou mal modelados
