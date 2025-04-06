# Para criar um ambiente virtual :
1. Abrir um terminal
2. Execute o comando : cd pastaDoProjeto
3. Execute o comando : python -m venv venv

# Para rodar/ativar o ambiente virtual : 
1. Abrir um terminal
2. Execute o comando : cd pastaDoProjeto
3. Execute o comando : /venv/Script/activate

# Para rodar/ativar o front :
1. Abrir um terminal
2. Execute o comando : cd pastaDoProjeto
3. Ative o ambiente virtual
4. Execute o comando : python -m http.server -d dist

# Casos de erro :

1. Activate.ps1 cannot be loaded because running scripts is disabled on this system.

Solução : Executar este comando em um terminal (como administrador) -  "Set-ExecutionPolicy RemoteSigned"

2. Talvez ao rodar/ativar o front de o erro 404

Solução : Dentro da pasta do projeto e com ambiente virtual ativado executar comando com caminho do front : python -m http.server -d .\curso-web-scraping\dist\
