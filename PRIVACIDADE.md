# Política de Privacidade — MGPLAY para Windows

Última atualização: 24 de outubro de 2026 (versão 1.1)

O **MGPLAY** é um player de vídeo para Windows desenvolvido por **MG Desenvolvedor**. Ele reproduz
listas M3U/M3U8 e contas Xtream que **o próprio usuário informa** ou que o seu fornecedor libera.
O MGPLAY **não vende, não fornece e não hospeda** canais, filmes ou séries.

## 1. O que fica guardado no seu computador

Ficam **somente no seu computador**, na pasta do aplicativo:

- o endereço da lista ou os dados da conta (servidor, usuário e senha) que você digitar;
- uma cópia da última lista baixada, para o app abrir mais rápido;
- Minha lista (favoritos), histórico e ponto em que você parou;
- suas configurações e o registro de erros (`mgplay.log`).

O desenvolvedor **não recebe** esses dados. Para apagar tudo, use **Configurações → Apagar todos os
dados** ou desinstale o aplicativo.

## 2. Com quem o aplicativo se comunica

O MGPLAY só se conecta a:

1. **O servidor da sua lista.** Ele é informado por você ou pelo seu fornecedor, e o app se conecta a ele
   para baixar a lista, reproduzir os vídeos e conferir se o usuário e a senha valem.
2. **O painel de ativação do seu fornecedor** (mgplaypainel.netlify.app). Ele serve para liberar o seu
   aparelho. Ao abrir o app e a cada 6 horas, o painel recebe:
   - o endereço MAC da placa de rede (no navegador, um código criado pelo app);
   - a Chave de 6 dígitos criada pelo app;
   - o nome do computador;
   - o endereço IP;
   - a versão do app.

   Em resposta, o painel informa se o aparelho está liberado e qual é o servidor ou a lista da sua conta.
3. **O Painel MGPLAY instalado pelo fornecedor num computador**, somente se você se conectar a um, pelo
   código de 4 dígitos ou pelo código de conexão. Enquanto o app estiver aberto, esse painel recebe:
   - o endereço MAC da placa de rede;
   - o nome do computador;
   - o endereço IP;
   - a versão do app;
   - **o nome do canal, filme ou episódio que está sendo assistido**.

   O painel usa esses dados para mostrar os aparelhos online, liberar o acesso e montar o "Top 10".
   O Top 10 usa só contagens: os outros aparelhos recebem apenas os nomes dos títulos e quantas
   pessoas assistiram.
4. **Imagens de capas.** Elas são buscadas pelo painel na API do TMDB, somente se o fornecedor ativar
   isso. Para a busca, o painel envia **somente o nome do título**.

Sem lista nem painel configurados, o app mostra um catálogo de exemplo com vídeos de licença aberta,
carregados de servidores públicos de amostra.

O painel de ativação (item 2) é administrado por **MG Desenvolvedor** e pelos revendedores cadastrados
nele. Ele usa esses dados só para ativar e manter o seu aparelho. Quando o aparelho é excluído do painel, os
dados dele são apagados; o histórico do painel guarda apenas o MAC e a data das ações (ativação, bloqueio…).
O Painel MGPLAY do item 3 é operado **pelo seu fornecedor**: para saber o que ele faz com esses dados,
consulte-o.

## 3. O que o aplicativo não faz

- Não tem anúncios.
- Não usa ferramentas de análise ou rastreamento de terceiros.
- Não vende nem compartilha dados com terceiros.
- Não pede acesso a câmera, microfone, contatos ou localização.

## 4. Crianças

O MGPLAY não é direcionado a crianças e não coleta dados de crianças. O conteúdo exibido depende da
lista informada pelo usuário.

## 5. Contato

Dúvidas sobre esta política: **mgdesenvolvedor01@gmail.com**
