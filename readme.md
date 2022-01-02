## Docsarc

<p style="text-align: justify;">
Essa estrutura foi construida para servir de base para futura documentações implementadas utilizando o gitbook. Buscamos aqui utilizar os recursos desta ferramenta para poder expressar nossa base de conhecimento e facilitar o acesso daqueles que necessitem.
</p>

### Instalação de Pacotes

- Para Utilizar Todo o Potêncial do Gitbook Execute os Seguintes Comandos.

      npm install gitbook-cli -g
      npm install ebook-convert
      sudo -v && wget -nv -O- https://download.calibre-ebook.com/linux-installer.py | 
      sudo python -c "import sys; main=lambda:sys.stderr.write('Download failed\n'); 
      exec(sys.stdin.read()); main()"
      sudo apt-get install calibre

### Build dos Arquivos

- Gerando Build.

      gitbook build ./ ./book

- Iniciando Serve Para Previa.

      gitbook serve ./ ./book

- Gerando Pdf do Conteúdo.

      gitbook pdf ./ ./book.pdf
