# HTML-notes
<p>This repository focuses on my advanced HTML study notes</p>

    <h1>Text Format</h1>

<h2>Headlines</h2>

    <h1>h1</h1>
    <h2>h2</h2>
    <h3>h3</h3>
    <h4>h4</h4>
    <h5>h5</h5>
    <h6>h6</h6>

<p>Aqui, a ideia é <em>hierarquia de titulos</em>, do mais importante e que precisa ser visto primeiro. Layout conseguimos fazer usando CSS, o importante é pensar em uma hierarquia de titulos para tornar a arvore de acessibilidade funcional e para marcar as sessões da página.</p>

<h2>Italic and Emphasis</h2>

<p> A tag  &lt;i&gt; é usada para distinção visual de italico, enquanto a tag  &lt;em&gt; faz enfase acrescentando valor semantico</p>

<h2>Bold and Strong</h2>

<p>Da mesma forma, a tag <b> acrescenta distinção visual e a tag <strong> serve para enfase de alertas ou avisos</p>

<h2>Lists</h2>

<dl>
    <dt>unordered List</dt>
    <dd>lista que não precisa seguir ordenação.
        <code>
            <ul>
                <li>unordered item</li>
                <li>unordered item</li>
                <li>unordered item</li>
            </ul>
        </code>    
    </dd>
    <dt>ordered List</dt>
    <dd>lista ordenada de alguma forma.
        <code>
            <ol>
                <li>ordered item</li>
                <li>ordered item</li>
                <li>ordered item</li>
            </ol>
        </code>
    </dd>
    <dt>definition List</dt>
    <dd>Lista tipo key:value, com um <dt> definition term e um <dd> definition description.
        <code>
            <dl>
                <dt>definition term</dt>
                <dd>definition description</dd>
            </dl>
        </code>
</dl>

<h2>Quotes</h2>

<h3>Blockquote</h3>
<p>usado para blocos de texto</p>

<pre>
    <code>
       &lt;blockquote&gt;
          &lt;p&gt;Lorem, ipsum dolor sit amet consectetur adipisicing elit. Reiciendis eius maiores aperiam aut tenetur animi!,<br> Eius modi necessitatibus natus enim sint vel rem accusamus excepturi! Mollitia nam dignissimos quo ea.&lt;/p&gt;
   &lt;cite&gt; -- Ipsum Dolor &lt;/cite&gt;
       &lt;/blockquote&gt;
    </code>
</pre>

<h3>Quote marks in text</h3>

<p>usado para marcar citações in line</p>
<p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. <q>Reiciendis eius maiores aperiam aut tenetur animi!</q></p>

<h2>Time</h2>
<p>Transforma qualquer data em um formato que o navegador (máquina) consegue entender</p>

<code>
    <time datetime="2022-07-15">15 de julho de 2022</time>
    <time datetime="23:00">11:00 p.m.</time>
    <time datetime="2022-07-13">2 dias atrás</time>
    <time datetime="23:00-06:00">11:00 no Canadá</time>
    <time datetime="2022-07-15T23:00">Quinta, 15 de julho as 23h</time>

</code>
</body>
</html>

<h2>Code, &lt; , &gt; and pre</h2>
<pre>
    <code>
        &lt;code&gt;
            &lt;p&gt;Para acrescentar cores em um texto, podemos usar  &lt;code&gt;{color:red} &lt;/code&gt;&lt;/p&gt;
        &lt;/code&gt;
    </code>
</pre>
