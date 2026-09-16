# Harmonização Facial Multicamadas · Portugal

Landing page do curso de Harmonização Facial Multicamadas com o Dr. Gabriel Machado,
trazido a Portugal pela Belinha Cardoso (BeLuxClinic).

**Página publicada:** https://harmonizacao-facial-multicamadas.github.io/

## O evento

| | |
|---|---|
| Formador | Dr. Gabriel Machado |
| Organização | Belinha Cardoso · BeLuxClinic |
| Lisboa | 13 e 14 de outubro |
| Porto | 15 e 16 de outubro |
| Carga horária | 20 horas (10 de teoria + 10 de prática) |
| Contacto | WhatsApp +351 969 290 136 |

## Como está feito

Um único ficheiro `index.html` com o HTML, o CSS e o JavaScript lá dentro, mais a
pasta `img/`. Sem frameworks, sem dependências, sem passo de build: o que está no
repositório é exactamente o que o browser recebe.

```
index.html     página completa (HTML + CSS + JS)
img/           fotografias e casos clínicos
.nojekyll      serve os ficheiros tal como estão, sem processamento
404.html       página de erro
robots.txt     indexação
```

## Alterar a página

Editar `index.html` e fazer commit para `main`. O GitHub Pages republica sozinho
em um a dois minutos. Para ver localmente antes de publicar:

```bash
python -m http.server 8000
# abrir http://127.0.0.1:8000
```

## Segurança

A página é estática: não recolhe dados, não tem formulários, não usa cookies nem
analítica, e não faz pedidos a servidores. Os contactos são links directos para
WhatsApp e Instagram.

- `Content-Security-Policy` declarada na própria página: só carrega imagens do
  próprio domínio, tipos de letra do Google Fonts e do Fontshare, e nada mais.
- `form-action 'none'` e `base-uri 'none'`: nem que fosse injectado um formulário
  teria para onde submeter.
- Todos os links externos com `rel="noopener"`.
- HTTPS obrigatório no domínio do GitHub Pages.

## Imagens

As fotografias de casos clínicos são cedidas pelo Instituto Dr. Gabriel Machado /
Clínica Arthys. A utilização pública de imagens de pacientes depende de
autorização escrita dos próprios, ao abrigo do RGPD. Confirmar antes de divulgar.

## Créditos

Site desenvolvido pelo [Grupo Cado](https://www.instagram.com/ogrupocado/).
