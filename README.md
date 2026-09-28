Geoportal do Plano Municipal de Mata Atlântica e Cerrado de Jaguariúna/SP: vegetação nativa, áreas de preservação, vetores de degradação, áreas prioritárias e ações de conservação e restauração.

🔗 **Acesse ao vivo:** https://mirianniz-debug.github.io/PlanoMataAtlantica/

## Visualizar localmente

O mapa carrega os dados de `data/` com `fetch`, então não abre com duplo clique no `index.html`: é preciso servir a pasta por um servidor local (qualquer servidor estático) e abrir `http://localhost:<porta>/`.

## Incorporando o geoportal em outro site (iframe)

O `index.html` é responsivo, mas isso só funciona se o `<iframe>` que o incorpora também for responsivo. Use sempre largura em porcentagem, nunca um valor fixo em pixels:

```html
<iframe src="URL_DO_GEOPORTAL" style="width:100%; border:0;" height="600" loading="lazy"></iframe>
```

## Licença

Todos os direitos reservados. Ver [LICENSE](LICENSE).
