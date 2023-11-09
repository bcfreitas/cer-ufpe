# cer-ufpe

Tarefa inicial: base para webapp baseado em template angular, usando Angular 16 e docker ready.

template utilizado: sakai-ng (https://github.com/primefaces/sakai-ng) 

requisitos: 

NodeJS: 18.16.1

Docker: 24

## how-to para usar a imagem docker

Foi criada uma imagem docker e disponibilizada no docker hub.

1. docker pull bcfreitas2/app-cer-ufpe
2. docker run --name app-cer-ufpe-container -d -p 8080:80 bcfreitas2/app-cer-ufpe

Acessar http://localhost:8080/

## how-to para executar a partir do código fonte

1. cd ~/git (ou o diretório que você preferir para baixar)
2. git clone git@github.com:bcfreitas/cer-ufpe.git
3. npm install
4. ng build (necessário Angular CLI 13+)
5. ng serve

Acessar http://localhost:4200/
