# xfce4-windowck-plugin (fork)

Esta é uma modificação do plugin do XFCE Windowck que esconde os botões de janela quando a janela em foco não está maximizada.

## COMPILANDO

Para compilar, veja quais pacotes você precisa instalar no arquivo de texto em debian/control, seção Build-Depends.

Este arquivo indica os nomes dos pacotes bem como as versões mínimas que devem estar disponíveis no seu repositório.

Após instalada as dependências de compilação, instale o pacote "build-essential" necessário para executar os comandos abaixo.

1. Gere os arquivos de construção:
  `./autogen.sh --prefix=/usr`
2. Agora compile o plugin:
  `make`

## INSTALANDO

Assumindo que você compilou o plugin com sucesso, já pode executar o comando de instalação a seguir.

Para instalar:
  `sudo make install`

Se tudo deu certo, você já pode adicionar o plugin "Window Header - Buttons" no painel.

Ele deve aparecer escondido, pois é necessário que uma janela maximizada esteja em foco.

## RELATANDO ERROS

Você pode, neste repositório, relatar falsos erros para pedir ajuda com a instalação do plugin, elaborar críticas ou ainda abrir PR's com modificações exclusivas a esta versão do plugin.

Para todos os demais casos, eu não sou capaz de te ajudar, então vá para o [repositório oficial](https://github.com/cedl38/xfce4-windowck-plugin)!

by cleds.upper
