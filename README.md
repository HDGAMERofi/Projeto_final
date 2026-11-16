🏎️ F1 Apex — Portal de Fórmula 1

Projeto desenvolvido para a disciplina de Desenvolvimento de Interfaces (2/2026) do Centro Universitário de Brasília (CEUB), sob orientação do Prof. Dr. Felipe Batista da Silva.

📋 Sobre o Projeto

O F1 Apex é um portal web informativo e interativo dedicado ao universo da Fórmula 1, focado na temporada de 2026. O objetivo da plataforma é engajar fãs de automobilismo por meio de informações técnicas atualizadas (como o novo Modo Overtake e a Aerodinâmica Ativa), perfis dos principais pilotos do grid, destaques visuais e canais de interação com a comunidade.

O desenvolvimento foi planejado seguindo as diretrizes de UI/UX, Heurísticas de Nielsen, Psicologia das Cores e padrões internacionais de acessibilidade WCAG (Web Content Accessibility Guidelines).

🚀 Histórico de Versões (Roadmap e Evolução)

O projeto está sendo construído de forma incremental e versionada no GitHub para documentar cada camada do desenvolvimento web:

✅ Versão 1.0 — Estrutura Semântica (HTML5 Puro) [CONCLUÍDA]

O que fizemos: Construção de todo o esqueleto da página utilizando HTML5 semântico 
(<header>, <nav>, <main>, <section>, <article>, <footer>), priorizando a acessibilidade para leitores de tela.

Elementos implementados:

Cabeçalho com barra de pesquisa e controles de acessibilidade (Aumentar/Diminuir fonte e alternância de tema).

Estrutura do carrossel de destaques da temporada.

Cartões (cards) com pilotos e equipes reais (Max Verstappen, Charles Leclerc, Lewis Hamilton e Lando Norris).

Cartões explicativos sobre o regulamento técnico de 2026 (Modo Overtake, Aerodinâmica Ativa: Modo Reta e Modo Curva, Undercut e Compostos Pirelli).

Formulário de contato e seção de Login.

Rodapé institucional e organização local de ativos na pasta img/.

🔄 Versão 2.0 — Estilização, Responsividade e WCAG (CSS3) [PRÓXIMO PASSO]

O que vamos fazer: Aplicar a identidade visual inspirada na Fórmula 1 (paleta baseada em Vermelho F1, Preto Asfalto e Cinza Carbono).

Melhorias planejadas:

Uso de variáveis CSS (:root) para implementar o Modo Escuro e o Modo Claro.

Validação de contraste de cores seguindo os níveis AA/AAA da WCAG.

Layout responsivo utilizando CSS Grid e Flexbox para adaptação em dispositivos móveis e desktops.

⏳ Versão 3.0 — Interatividade e Dinamismo (JavaScript) [PLANEJADA]

O que vamos fazer: Adicionar comportamento dinâmico aos elementos da interface.

Funcionalidades planejadas:

Funcionamento real dos botões de acessibilidade (A+, A- e troca de tema).

Navegação interativa nos slides do carrossel.

Filtro em tempo real na barra de pesquisa para buscar pilotos e equipes.

Validação interativa e feedback visual nos formulários de contato e login.

📁 Estrutura de Pastas Atual

Projeto_final/
├── index.html                  # Estrutura principal da página (HTML5)
├── README.md                   # Documentação do projeto
└── img/                        # Diretório de imagens locais
    ├── carrossel-largada.jpg   # Imagem de destaque 1
    ├── carrossel-pitstop.jpg   # Imagem de destaque 2
    ├── verstappen-redbull.jpg  # Foto piloto Max Verstappen
    ├── leclerc-ferrari.jpg     # Foto piloto Charles Leclerc
    ├── hamilton-mercedes.jpg   # Foto piloto Lewis Hamilton
    └── norris-mclaren.jpg      # Foto piloto Lando Norris


💻 Como Executar o Projeto Localmente

Clone ou baixe este repositório para o seu computador.

Certifique-se de que as imagens estejam dentro da pasta img/ com os nomes listados acima.

Abra o arquivo index.html diretamente em qualquer navegador web moderno (Google Chrome, Microsoft Edge, Firefox, etc.).

⚖️ Aviso Legal e Direitos Autorais (Uso Acadêmico)

Este projeto foi desenvolvido exclusivamente para fins educacionais e acadêmicos, sem qualquer finalidade comercial ou lucrativa, como requisito de avaliação da disciplina de Desenvolvimento de Interfaces (CEUB).

Todas as marcas, nomes de equipes, nomes de pilotos, termos técnicos e referências visuais à Fórmula 1 (Formula 1® / F1®) pertencem aos seus respectivos proprietários (Formula One Licensing B.V., FIA e equipes participantes) e são utilizados aqui sob o princípio de uso justo (fair use) para estudo e demonstração técnica.
