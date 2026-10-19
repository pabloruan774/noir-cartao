# noir-cartao


NOIR — Site de Cartão de Banco

Site institucional de um cartão de banco fictício, todo em preto, com visual sofisticado, animações de rolagem e um cartão 3D que o visitante pode personalizar. Feito em HTML, CSS e JavaScript puro, em um único arquivo, sem dependências e totalmente responsivo.

Projeto de portfólio. A marca NOIR, os textos, valores, taxas e telefones são fictícios.

O que tem no site

Topo e navegação

Hero com cartão 3D que gira conforme a rolagem
Barra de navegação fixa com menu para celular
Barra de progresso de leitura e faixa de benefícios em movimento

Coleção de cartões

Seção em que os cartões se abrem em leque enquanto a página rola

Vantagens

O cartão fica fixo e reage a cada vantagem: cashback, segurança (vira para mostrar o verso), zero anuidade, salas VIP e pagamento por aproximação

Aplicativo

Celular estilo iPhone com o app aberto e quatro telas interativas
Cartão virtual com botões de gerar novo número e congelar
Pix, controle de gastos com gráfico animado e notificações em tempo real

Serviços e Planos

Abas de serviços: cartões, conta digital, investimentos e crédito
Planos com abas de Seguros, Empréstimos e Assinaturas
Simulador de empréstimo com valor e parcelas ajustáveis
Plano Super Black para clientes VIP

Personalizar o cartão

Estilos: Black, Pearl, Grafite, Carbono, Espelho, Vidro, Void, Roxo, Azul, Vinho e Super Black (exclusivo VIP)
Nome no cartão, 9 opções de fonte, cor do chip, acabamento (brilho ou fosco), número visível ou oculto
Botão para virar o cartão e ver o verso, com inclinação 3D que segue o mouse

Detalhes

Fundos sutis com gradientes e textura de grão
Brilho que acompanha o mouse nos cartões de conteúdo
Respeita a preferência de movimento reduzido do sistema
Tecnologias
HTML5
CSS3 (variáveis, grid, flexbox, clamp(), animações e transformações 3D)
JavaScript (IntersectionObserver, eventos de rolagem e ponteiro)
Fontes do Google Fonts: Sora, Inter, Playfair Display, Dancing Script, Bebas Neue, Caveat e Fredoka
Como rodar

Não precisa instalar nada.

Baixe ou clone este repositório
Abra o arquivo index.html no navegador
bash
git clone https://github.com/SEU-USUARIO/noir-cartao.git
cd noir-cartao

Precisa de conexão com a internet apenas para carregar as fontes.

Publicar com GitHub Pages
Vá em Settings → Pages
Em Branch, escolha main e salve
Em alguns minutos o site fica disponível em https://SEU-USUARIO.github.io/noir-cartao/
Como personalizar

Tudo está em index.html:

O que mudar	Onde
Cores e fontes	Variáveis no início do <style> (:root)
Textos, serviços e planos	Seções do HTML (#servicos, #planos, #vantagens)
Estilos de cartão	Regras .dcard[data-style="..."]
Taxa do simulador	Constante i dentro da função sim() no JavaScript
Licença

Uso livre para estudo e portfólio. Defina aqui a licença que preferir (por exemplo, MIT).
