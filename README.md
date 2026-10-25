# Site DTI Consultoria

Site institucional da **DTI Consultoria em TI**, feito em HTML puro (sem build e sem dependências).

## Estrutura

```
index.html           Início
institucional.html   Institucional
solucoes.html        Soluções
contato.html         Contato e Suporte
404.html             Página de erro
assets/              Logo, favicon e ícone
robots.txt
.nojekyll            Faz o GitHub Pages servir os arquivos como estão
```

## Publicar no GitHub Pages

1. Crie um repositório e envie todos os arquivos desta pasta para a raiz, incluindo o `.nojekyll`.
2. Em **Settings › Pages**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`.
3. Em poucos minutos o site fica disponível em `https://<usuario>.github.io/<repositorio>/`.

## Versão de verificação

Esta versão mostra uma faixa de aviso no topo e não é indexada pelos buscadores.
Para transformá-la na versão oficial:

- apague o bloco marcado `VERSÃO DE VERIFICAÇÃO` (faixa de aviso) nas páginas;
- apague a linha `<meta name="robots" content="noindex, nofollow">` nas páginas;
- no `robots.txt`, troque `Disallow: /` por `Allow: /`.

## Domínio próprio (opcional)

Em **Settings › Pages › Custom domain**, informe o domínio (ex.: `www.dticonsultoria.com.br`)
e crie no DNS um registro `CNAME` apontando `www` para `<usuario>.github.io`.

## Contato

DTI Consultoria em TI · Av. Sebastião Davino dos Reis, 1015 – Apto 172 B – Jd. Tupanci – Barueri – SP · CEP 06414-007
contato@dticonsultoria.com.br · +55 11 97400-9234
