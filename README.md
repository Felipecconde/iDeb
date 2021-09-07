# Instalação
**Para instalar, digite o comando abaixo no seu terminal e pressione ENTER:**
```
br ideb
```
Pronto, não precisa fazer mais nada, já está instalado!

(Para ver o interior deste script, digite ``br -v ideb``)
Caso digitar ``br ideb`` não tenha funcionado para você, você deverá instalar o (BashRun)[https://github.com/Felipecconde/br] (Não leva nem 30 segundos pra instalar o BashRun :p).
<br>
# Como utilizar o iDeb
Após instalar o iDeb, digite "ideb -h" no seu Terminal para obter ajuda. Auto-explicativo, não?
<br>
# Instalações alternativas
<h6>Utilize este método caso instalar utilizando o BashRun não funcionou para você<h6>
Alternativamente, você pode instalar o iDeb copiando todo o código abaixo, e o colando em seu Terminal:

```
cd ~ && sudo apt install git && rm -rf /home/$USER/Downloads/iDeb /home/$USER/Downloads/ideb-* && git clone https://github.com/Felipecconde/iDeb /home/$USER/Downloads/iDeb && tar -xf /home/$USER/Downloads/iDeb/ideb-* -C /home/$USER/Downloads/ && rm -rf /home/$USER/Downloads/iDeb && cat /home/$USER/Downloads/ideb-*/'Ajuda\Help.txt' && echo && echo '- [!] Leia a mensagem de ajuda acima (Português e Inglês) antes de instalar. Prosseguindo para a instalação em 5 segundos...' && sleep 5 && cd /home/$USER/Downloads/ideb-*/ && sh /home/$USER/Downloads/ideb-*/'.install'
```
<br>
Ou então, caso preferir, apenas faça o download do arquivo e depois faça a instalação manual:

```
cd ~ && sudo apt install git && rm -rf /home/$USER/Downloads/iDeb /home/$USER/Downloads/ideb-* && git clone https://github.com/Felipecconde/iDeb /home/$USER/Downloads/iDeb && tar -xf /home/$USER/Downloads/iDeb/ideb-* -C /home/$USER/Downloads/ && rm -rf /home/$USER/Downloads/iDeb && cat /home/$USER/Downloads/ideb-*/'Ajuda\Help.txt' && echo && echo '- [!] Leia a mensagem de ajuda acima (Português e Inglês) antes de instalar. Navegue para "/home/$USER/Downloads/ideb-*" e instale o iDeb manualmente. Caso prefira uma instalação automática e simples, opte pela instalação normal na página de instalação do iDeb.'
```
<br>
