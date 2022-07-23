<h1>images</h1>

<h2>Using HTML to deliver different image files to different size screens</h2>

<h3>Basic use of image tag</h3>

<pre>
<code>
<img src="" alt="" width="" height="">
</code>
</pre>

<h3>Uso do srcset</h3>
<p>O atributo srcset oferece ao browser escolhas de tamanho de imagem que se adaptam melhor, evintando carregamento desnecessario. Neste exemplo, o w fornece o pixel measurement, no lugar de colocarmos 2x, 3x, saindo de um resolution-based para um srcset width-based. Desa forma, conseguimos especificar o width de origem da imagem</p>
<pre>
<code>
   <img src="img/img-480.png" alt="flores" width="auto" height="auto"
    srcset="img/img-480.png 480w,
            img/img-w960.png 960w,
            img/img-w1440.png 1440w,
            img/img-w1920.png 1920w"
    sizes="(max-width:480px) 240px,
            (max-width:960px) 480px,
            (max-width:1440px) 690px,
            1920px"
            >
</code>
</pre>

<h3>Figure e Caption</h3>
<p>O elemento Figure vai encapsular o elemento caption e outros elementos gráficos, mas que vai manter a legenda junto da imagem.</p>
<dl>
<dt>figure</dt>
<dd>para usar em tudo que aparecer como uma figura, ilustrando algo.</dd>
<dt>figcaption</dt>
<dd>para demonstração de um conceito que precisa de uma legenda.</dd>
</dl>