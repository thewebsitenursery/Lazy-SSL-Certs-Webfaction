# Lazy-SSL-Certs-Webfaction

<p>This adds even more automation to the quite brilliant letsencrypt-webfaction shell script

- Completely automating the process of generating, confirming and installing certificates from Letsencrypt
- Certificates issued for 'example.com' and 'www.example.com'

<p>Original letsencrypt-webfaction by https://github.com/will-in-wi/letsencrypt-webfaction
<p>This little addition by thewebsitenursery.com 

<B> The only assumption I make is that you have a ~/.bash_profile if you dont then "touch ~/.bash_profile" first.

# Ready, get set go!

SSH to your $HOME Webfaction dicectory and run:

"git clone https://github.com/thewebsitenursery/Lazy-SSL-Certs-Webfaction && cd Lazy-SSL-Certs-Webfaction && ./lazysslcerts-webfaction"

