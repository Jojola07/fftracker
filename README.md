🔥 FF Tracker — Monitor de Progresso de Temporada
Um web app completo para acompanhar seu progresso nas partidas ranqueadas do Free Fire. Esqueça a sensação de que 3 partidas por dia não rendem nada — aqui você vê cada estrela, cada kill, cada combinação, tudo virando progresso visual.

https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white
https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white
https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black
https://img.shields.io/badge/license-MIT-green
https://img.shields.io/badge/dependencies-0-brightgreen

📖 Sobre o projeto
O FF Tracker nasceu de uma dor real: o grind diário de partidas ranqueadas é cansativo e a sensação de progresso é quase nula. O app resolve isso transformando cada partida em dados visuais — estrelas subindo, metas batidas, gráficos de constância, projeções de rank — para dar aquele ânimo de continuar.

É um arquivo HTML único, sem build, sem servidor, sem dependências. Basta abrir no navegador e começar a usar.

✨ Funcionalidades
🏆 Sistema de Rank Completo
Suporte a todas as divisões do Free Fire:

Bronze (1–3), Prata (1–3), Ouro (1–4), Platina (1–5), Diamante (1–5)

Mestre (1–24), Mestre de Honra (25–49), Elite (50–99), Elite de Honra (100–999), Desafiante (1000+)

Lógica de promoção real: 5 estrelas enchem a divisão, a 6ª vira a primeira do próximo elo

No Mestre e acima, as estrelas são substituídas por uma estrela brilhante animada + contador de pontos

Emblema visual que muda de cor conforme o tier (gradientes únicos por elo)

Animação de "pop" nas estrelas sempre que você sobe

🎯 Metas Inteligentes
Defina a meta diária OU a meta total da temporada

Os dois campos se sincronizam automaticamente (ex: 3/dia → 183 na temporada considerando 61 dias)

Cálculo em tempo real de quantas partidas faltam por dia para bater a meta até o fim da temporada

Barra de progresso dupla: temporada + dia atual

🧪 Simulador de Vitórias
Ajuste a taxa de vitória esperada (0–100%) via slider

Veja quantas vitórias/derrotas terá ao completar a meta

Projeção do rank final estimado baseada no seu histórico real (média de estrelas ganhas/perdidas)

🎮 Registro de Partidas
Cada partida registrada captura:

✅ Resultado (vitória/derrota)

⭐ Estrelas ganhas ou perdidas

🎯 Kills, mortes e assistências

🥇 Medalha da partida (MVP / 2º lugar / 3º lugar / sem medalha)

⏱️ Duração (minutos + segundos)

🎭 Combinação de personagens usada

📅 Data e hora

🎭 Combinações de Personagens
Crie combinações com título e lista de personagens

Ex: "Combinação de Cura" → Kelly, Alok, Chrono, X

Edite e exclua combinações

Selecione qual usou em cada partida registrada

📊 Dashboard Visual
Cards de estatísticas: K/D, KDA, taxa de vitória, MVPs, sequência atual, recorde de kills, tempo jogado

Gráfico dos últimos 7 dias com destaque quando a meta diária é batida

Histórico completo com filtros visuais, exclusão individual e preview da combinação usada

💾 Dados e Persistência
Salvamento automático em localStorage (nada sai do seu navegador)

Exportar/Importar JSON para backup ou migrar entre dispositivos

Reset completo com confirmação dupla

🎨 Design
Tema escuro estilo "gamer" com gradientes laranja/âmbar

Totalmente responsivo (mobile-friendly)

Animações suaves, toasts de feedback e microinterações

Zero dependências externas — sem CDN, sem framework

