Para hacer peticiones y capturar respuestas a API con cURL:

Linux:
 instalación:	sudo apt install curl
 include:		<curl/curl.h>
 flag:			-lcurl


MacOS:
 instalación:	brew install curl
 include:		<curl/curl.h>
 flag:			-lcurl



Para ordenar la información en formato JSON con jsoncpp:

Linux:
 instalación:	sudo apt-get install libjsoncpp-dev
 include:		<json/json.h>
 flag: 			
 
Si no compila porque sigue sin encontrar funciones JSON:
sudo ln -s /usr/include/jsoncpp/json/ /usr/include/json