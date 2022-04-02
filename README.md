Comando para sincronizar painel:

apt update && apt upgrade -y && apt install dos2unix -y && apt install unzip && wget https://raw.githubusercontent.com/TH-NET/SincronizadorDePainelWeb/main/SINC.zip && unzip SINC.zip && chmod +x *.sh && dos2unix *.sh