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

1. Starter Template
2. WP FASTEST cache (o melhor)
3. Updraft Plus
4. Elementor
5. Wordfence
6. Web Stories
7. Email subscriber
8. Rank Math
9. Site Kit
11. Premium Addons for Elementor
12. Cokie 
13. Artiboti
14. custom 404 pages

### Se for o caso de woocomerce:
  1. Brazilian Market on WooCommerce
  2. Checkout Field Editor for WooCommerce
  3. Claudio Sanches - Correios for WooCommerce
  4. Claudio Sanches - PagSeguro for WooCommerce (se for usado o pag seguro, se não, baixar outro para paypal e afins)
  5. Kadence WooCommerce Email Designer
  6. Variation Swatches for WooCommerce (colocar cores diferentes para o mesmo produto)
  7. WooCommerce Cart Abandonment Recovery
  8. Yotpo Social Reviews for Woocommerce 

Boa diversão na construção de seu novo site.

