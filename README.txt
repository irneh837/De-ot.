deot
│
├── index.html
├── manifest.json
├── README.txt
│
└── assets
    ├── referencia_sistema_estelar.png
    ├── referencia_planeta_aberto.png
    └── referencia_planeta_recolhido.png

IMPLEMENTADO NESTE PROTÓTIPO
- Casa removida da navegação.
- Meu Sistema Stelar como nova área.
- Efeito de ondas pontilhadas dentro dos botões.
- Cores por área/matéria.
- Mapas mentais filtrados pela matéria selecionada.
- Desempenho no perfil com matéria, tema e gráfico.
- Linguagens aparece somente dentro de Humanas.
- Botões Voltar usam histórico de navegação.
- Painel administrativo com ações funcionais de adicionar conteúdo e dificuldade.
- Área de denúncias de conteúdo explícito.
- Dúvidas em painel parcial, preservando o fundo pontilhado.
- Etiquetas das dúvidas usam a cor da matéria.
- Sistema Stelar com duas estrelas, planeta, loja e cronômetro.
- Fases de evolução: rocha, vulcões/lava, atmosfera, lagos, oceanos, vegetação, crescimento, animais, vida inteligente, cidades/naves.
- Tempos das fases: 30, 60, 90, 150, 210, 300, 420, 540, 660 e 780 minutos.

OBSERVAÇÃO TÉCNICA
O protótipo usa localStorage para salvar o nome do planeta, fase alcançada e pontos no navegador. O tempo da sessão do cronômetro é mantido apenas enquanto a página está aberta e é zerado ao sair/recarregar, conforme solicitado. Denúncias e conteúdos administrativos desta versão são demonstrações locais; para dados compartilhados entre usuários, autenticação e persistência central, ligue o front-end a um backend/banco de dados.
