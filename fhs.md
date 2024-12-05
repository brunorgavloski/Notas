# FHS
1996 Comunidade do BSD iniciou o projeto e padronização.
Hoje é mantido pela Linux Fundation.
Versão atual 3.0 de jun 2015.
No windows cada empresa emplementa sua aplicação da forma que quer.
Nos sistemas Unix Like tudo tem seu lugar.

### Principais diretórios:
- /
- /proc processos
- /dev dispositivos
- /boot dados sobre boot, kernel, init. binarios
- /bin binarios essenciais do sistema.
- /sbin 
- /lib 
- /etc configurações dos programas
- /media montar na estrutura pendrives e cds
- /mnt montagem temporaria, por exemplo de rede
- /root diretorio do user root
- /home diretorio dos usuarios secundarios
- /tmp usados pelos programas para arquivos temporários
- /var arquivos variaveis, por exemplo appweb
- /usr/bin binarios não essenciais do sistema
- /usr/sbin binarios de adm do sistema
- /usr/lib bibliotecas
- /usr/share independente
- /usr/share/doc documentação
- /usr/share/man manuais

### Diretorio ~
É o diretorio HOME

### Comandos
- pwd mostra o path até o diretório local
- ls lista o conteudo do diretório corrente
- ls + diretório lista o conteúdo do local específico
- cd trocar diretório corrente.

### /proc
- Dentro do diretório encontramos varios números que são referentes a processos.
- Também exisetem arquivos como cpuinfo, um cat nesse arquivo trás dados da CPU.

### /boot 
- Encontram-se arquivos como vmlinux-* que o kernel
### /boot/grup
- podemos listar os arquivos do grub nesse diretório

