# Clube das Cafeterias — PWA

Esta pasta é a versão PWA do aplicativo.

## Importante
O iPhone não instala uma PWA a partir de um arquivo HTML aberto pelo app Arquivos.
Para instalar como aplicativo, os arquivos precisam ser servidos por HTTPS.

## Instalação no iPhone
1. Publique esta pasta em um endereço HTTPS.
2. Abra o endereço no Safari do iPhone.
3. Toque em Compartilhar.
4. Escolha "Adicionar à Tela de Início".
5. Abra o ícone "Clube das Cafeterias".

Depois da primeira abertura, o Service Worker permite que o app carregue também sem conexão,
desde que os recursos já tenham sido armazenados em cache.

Os dados das visitas continuam sendo armazenados localmente no navegador/origem do aplicativo.
