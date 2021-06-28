---
layout: post
# permalink: /comandosNovaInstalacao/
# external_url: https://roneydua.github.io/comandosNovaInstalacao
title: Setup para nova instalação Debian
category: Computacao
# external_site: comandosNovaInstalacao
---

Quando precisamos formatar o PC uma tarefa muito chata é ter que instalar todos os programas que utilizamos. No Linux isso pode ser feito de forma muito simples com scripts que podem ser executados no terminal.<!--excerpt-->
<!-- TOC -->

- [Utilização individual de cada script](#utilização-individual-de-cada-script)
- [Scrips para instalação de programas básicos](#scrips-para-instalação-de-programas-básicos)

<!-- /TOC -->

# Utilização individual de cada script
- `install_atom.sh` -  Instala a IDE ATOM instalando os pacotes na
  1. atom-doxit@0.2.1
  2. autocomplete@0.47.0
  3. autocomplete-clang@0.13.1
  4. bracket-colorizer@1.4.0
  5. build@0.70.0
  6. busy-signal@2.0.1
  7. clang-format@2.0.8
  8. dark-one-dark-syntax@2.3.0
  9. docblockr@0.13.7
  10. doxygen-snippets@0.1.1
  11. file-header@1.13.9
  12. file-icons@2.1.47
  13. formatter-clang-format@0.1.2
  14. gpp-compiler@3.0.7
  15. intentions@1.1.5
  16. language-ini@1.23.0
  17. language-markdown@0.37.0
  18. linter@3.3.1
  19. linter-gcc2@0.8.8
  20. linter-languagetool@0.11.0
  21. linter-ui-default@3.3.1
  22. logo-file-icons@1.13.0
  23. markdown-writer@2.11.11
  24. nv-dark-ui@3.0.8
  25. paraiso-dark@2.0.2
  26. plantuml@0.1.2
  27. plantuml-viewer@0.7.2
  28. platformio-ide@2.7.2
  29. platformio-ide-debugger@1.2.6
  30. platformio-ide-terminal@2.10.1
  31. purple-rain@0.4.8
  32. termination@0.7.6
  33. tool-bar@1.4.2
- `auto_completar.sh` -  Habilita o autocompletar no Shell terminal.
- `corrige_problema_sudo.sh` - Adiciona o usuário suda a lista de usuários.
- `latex_install.sh` - Instala Lyx e texlive.
- `python_instalação.sh` - Instala a IDE Spyder e o python3 além de outras bibliotecas python.
- `install_java.sh` - Instala o Oracle Java.
- `esp32_install.sh` - Instala dependências da Espressif para compilar os programas do ESP-32.
- `programas_essenciais.sh` - Instala os seguintes programas:
  1. Player de música Clementine
  2. Gerenciado de pacotes Synaptic
  3. Terminal tmux
  4 Gerenciador de impressoras HP Hplip-gui
  5. Reprodutor de mídia VLC
  6. Compactador p7zip
  7. Manipulador de PDFs pdftk
  8. Programa para baixar vídeos youtube-dl
  9. Monitor de sistema Conky
  10. Edito de Texto Lyx com as seguintes dependências:
      - texlive-fonts*;
      - texlive-science;
      - texlive-lang-portuguese; e
      - Adiciona o dicionário de sinônimos na pasta correta do sistema.
  11. IPE -- criador de figuras para latex

# Scrips para instalação de programas básicos
O script `main.sh` obteve exito nas distribuições mais recentes do Debian 64-bits.

Configura os programas:
- Copia as configurações do Conky na pasta conky.
- Configura o tmux
