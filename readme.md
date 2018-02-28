## Documentação Padrão

<p style="text-align: justify;">
Essa documentação foi construida com base na ferramenta gitbook. Buscamos aqui utilizar os recursos desta ferramenta para poder expressar nossa base de conhecimento e facilitar o acesso daqueles que necessitem.
</p>

### Instalação de Pacotes

<p>A documentação do sistema foi criada com o auxílio da ferramenta gitbook e se encontra no diretório /docs. Por favor seja bondoso com os que viram depois de você e documente as evolução realizada no código ou no banco de dados. contamos com você !
</p>

    npm install gitbook-cli -g
    npm install ebook-convert
    sudo -v && wget -nv -O- https://download.calibre-ebook.com/linux-installer.py | 
    sudo python -c "import sys; main=lambda:sys.stderr.write('Download failed\n'); exec(sys.stdin.read()); main()"
    sudo apt-get install calibre

### Build dos Arquivos

- Gerando build

´´
gitbook build ./ ./book
´´

- Iniciando Serve Para Previa

´´
gitbook serve ./ ./book
´´

- Gerando Pdf do Conteúdo

´´
gitbook pdf ./ ./book.pdf
´´