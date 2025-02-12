
O erro acontecia pois a biblioteca **libodbc1** tinha uma versão abaixo de 2.3.11-1, incompatível com a versão mais recente do gerenciador de drivers **unixODBC**.
![[Pasted image 20250211193743.png]]

Você pode começar com o comando `sudo apt install -f` usado para corrigir pacotes quebrados e resolver dependências ausentes em sistema baseado em Debian.
Abaixo você vê um possível retorno para o comando acima:
![[Pasted image 20250211194713.png]]

Para resolver o problema você pode forçar a instalação da biblioteca **libodbc1** versão 2.3.11-1 (versão mais atual, portanto compatível com gerenciador de drivers unixODBC à ser instalado)
Use o seguinte comando:
`sudo dpkg -i --force-overwrite /var/cache/apt/archives/libodbc1_2.3.11-1_amd64.deb` 
Assim foi possível atualizar a **libodbc1**.
![[Pasted image 20250211195809.png]]

Rode novamente o comando `sudo apt install -f` para instalar gerenciador de drivers **unixODBC**.
![[Pasted image 20250211202551.png]]

E fim de papo, problema resolvido!