# Passo-a-passo para criação de sites em Wordpress.

Inspirado fortemente nessa [Playlist do grande Prof. Gustavo Guanabara](https://www.youtube.com/watch?v=JPR4OK4c35Q&list=PLHz_AreHm4dmDP_RWdiKekjTEmCuq_MW2) (as aulas não são chatas nem monótonas; ótima edição e pedagogia são garantidos)

## Levantando o servidor
No GCP (Google Cloud Platform), clica-se em adicionar um projeto, cria-se com o nome do cliente/empresa. 
[Crie uma máquina virtual com o wordpress](https://themeisle.com/blog/install-wordpress-on-google-cloud/).
Configure os códigos necessários por meio de uma conexão SSH com o servidor, p.ex. com o [Putty](https://www.puttygen.com/download-putty), ultiliazando os códigos listados em "configuração_GCP.txt", em ordem.

## Crie um IP estático para alocação do site.
> Depois de tudo instalado, aparecerá o IP do Wordpress.

## Digite [ip]/admin para se acessar o terminal de administração do Wordpress
Com isso, consegue-se baixar os plugins e temas necessários.

## Tema
Apague os que estão ali.
Baixe o [astra](https://wpastra.com/) gratuitamente.
Baixe o astra-child no site: https://wpastra.com/child-theme-generator/.

## Plugins
Agora chega a parte divertida: personalização do site.
Baixe todos os plugins, extensões de funcionalidades, para se ter um site bonito, seguro e estável.
Eu pessoalmente recomendo alguns, porque utilizava-os na [Ensinu](https://github.com/diogojorgebasso/ensinu):
* WordFence Security
* Google Analytics
* Rank Math
* Updraft Plus para backup do site no Google Drive!
* Wp Fastest Cache
* Elementor (a versão paga)
* WP Forms
* Cookie Notice
* Tawk.to
* Web Stories

Boa diversão na construção de seu novo site.

