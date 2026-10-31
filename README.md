# Aurora para Windows

[Baixar o instalador mais recente](https://github.com/Gussta525/aurora-downloads/releases/latest)

Instale `Aurora-Setup-0.8.0.exe` no Windows 10/11 de 64 bits. Não precisa instalar Node.js. Abra o atalho Aurora e use sua conta do serviço https://aurora-fqza.onrender.com.

O Aurora verifica atualizações assinadas na janela de inicialização e aplica novas versões antes de abrir. Se a rede falhar, abre a versão atual. Durante o uso, verifica a cada quatro horas, baixa em segundo plano e aguarda o próximo reinício. O menu de busca manual foi removido na versão 0.8. Em **Configurações → Aplicativo**, veja a versão e use **Reiniciar aplicativo** ou **Reiniciar e atualizar**.

Mensagens, grupos, servidores, chamadas e compartilhamento de tela com áudio usam o mesmo serviço online. No Windows, a seleção de tela oferece **Incluir áudio do computador**. O serviço usa planos gratuitos, sujeitos a limites e inatividade.

Este repositório contém apenas distribuição; nenhum token ou dado de conta é incluído nos instaladores. As atualizações têm metadados assinados e verificação SHA512. O instalador inicial ainda não tem certificado comercial reconhecido pelo Windows e pode aparecer como editor desconhecido.

Na versão 0.5.0, a chamada inclui filtro de voz RNNoise local, **Ampliar** e **Tela cheia**, resolução de 480p a 4K e escolha de 30/60 fps. Os objetivos de qualidade se adaptam à fonte, ao computador e à rede. O filtro inteligente não é o Krisp e não há promessa de resultado equivalente. Os ajustes de transmissão foram inspirados no Tela Live, usando a própria infraestrutura WebRTC do Aurora.

Na versão **0.6.0**, o compartilhamento usa um seletor escuro com miniaturas e abas **Aplicativos / Tela inteira**. O microfone oferece **Lembrar minha escolha neste Aurora** para não repetir o pedido em cada chamada; a autorização pode ser removida nas configurações de voz. É preciso atualizar o aplicativo pelo menu **Aurora → Verificar atualizações**; apenas Ctrl+R não atualiza essas funções nativas.

Na versão **0.7.0**, personalize foto e faixa com PNG, JPEG, WebP ou **GIF animado**, cor da faixa, bio e status. Edite em **Configurações → Meu perfil**. Fotos aceitam até 1 MB; imagens da faixa, até 2 MB. Clique no avatar de alguém para abrir o perfil.

O aplicativo para Windows detecta jogos compatíveis (incluindo Roblox) e músicas em reprodução no **Spotify instalado**, pelo controle de mídia do Windows, sem pedir login ou senha Spotify. A leitura acontece a cada 15 segundos enquanto o Aurora está aberto. Use a opção de atividades no perfil ou o status Invisível para ocultar. Spotify Web e jogos fora do catálogo inicial não são detectados. A atividade Em voz mostra as chamadas do próprio Aurora.

Na versão **0.8.0**, a inicialização mostra uma janela de carregamento com estado e progresso. O reinício pelas configurações pede confirmação para evitar encerrar uma chamada por engano. Para migrar de uma versão anterior, use uma última vez o menu de atualização antigo ou instale a 0.8. Depois disso a abertura verifica automaticamente.
