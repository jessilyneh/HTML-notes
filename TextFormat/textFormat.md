## Text Format

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

<p>Da mesma forma, a tag  &lt;b&gt; acrescenta distinção visual e a tag &lt;strong&gt; serve para enfase de alertas ou avisos</p>

<h2>Lists</h2>

<dl>
    <dt>unordered List</dt>
    <dd>lista que não precisa seguir ordenação.
            <ul>
                <li>unordered item</li>
                <li>unordered item</li>
                <li>unordered item</li>
            </ul>  
    </dd>
    <dt>ordered List</dt>
    <dd>lista ordenada de alguma forma.
            <ol>
                <li>ordered item</li>
                <li>ordered item</li>
                <li>ordered item</li>
            </ol>
    </dd>
    <dt>definition List</dt>
    <dd>Lista tipo key:value, com um  &lt;dt&gt; definition term e um &lt;dd&gt; definition description.
            <dl>
                <dt>definition term</dt>
                <dd>definition description</dd>
            </dl>
</dl>

<h2>Quotes</h2>

<h3>Blockquote</h3>
<p>usado para blocos de texto</p>
       <blockquote>
         <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Reiciendis eius maiores aperiam aut tenetur animi!.
         Eius modi necessitatibus natus enim sint vel rem accusamus excepturi! Mollitia nam dignissimos quo ea.</p>
   <cite> -- Ipsum Dolor </cite>
       </blockquote>

<pre>
    <code>
       &lt;blockquote&gt;
         &lt;p&gt;Lorem, ipsum dolor sit amet consectetur adipisicing elit. Reiciendis eius maiores aperiam aut tenetur animi!.
         Eius modi necessitatibus natus enim sint vel rem accusamus excepturi! Mollitia nam dignissimos quo ea.&lt;/p&gt;
   &lt;cite&gt; -- Ipsum Dolor &lt;/cite&gt;
       &lt;/blockquote&gt;
    </code>
</pre>

<h3>Quote marks in text  &lt;q&gt;</h3>

<p>usado para marcar citações in line</p>
<p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. <q>Reiciendis eius maiores aperiam aut tenetur animi!</q></p>

<h2>Time</h2>
<p>Transforma qualquer data em um formato que o navegador (máquina) consegue entender</p>

<pre>
    &lt;time datetime="2022-07-15"&gt;15 de julho de 2022 &lt;/time&gt;
    &lt;time datetime="23:00"&gt;11:00 p.m. &lt;/time&gt;
    &lt;time datetime="2022-07-13"&gt;2 dias atrás &lt;/time&gt;
    &lt;time datetime="23:00-06:00"&gt;11:00 no Canadá &lt;/time&gt;
    &lt;time datetime="2022-07-15T23:00"&gt;Quinta, 15 de julho as 23h &lt;/time&gt;
</pre>

<h2>Code, &lt; and &gt;</h2>
<pre>
    <code>
        &lt;code&gt;
            &lt;p&gt;Para acrescentar cores em um texto, podemos usar &lt;code&gt;{color:red} &lt;/code&gt;&lt;/p&gt;
        &lt;/code&gt;
    </code>
</pre>

<h2>Superscripts, subscripts and small text</h2>
<h3>Subscripts:</h3>
<p> A tag &lt;sub&gt; em HTML é usada para exibir um texto como sobrescrito, que aparece metade acima da linha de base normal e é renderizado usando um tamanho de texto menor</p>
<p>exemplo: H<sub>2</sub>O</p>

<pre>
    <code>
         &lt;p&gt;H&lt;sub&gt;2&lt;/sub&gt;O&lt;/p&gt;
    </code>
</pre>

<h3>Superscripts:</h3>
<p> O texto dentro da tag  &lt;sup&gt; é renderizado meio caractere acima da linha normal e tem um tamanho de fonte menor.</p>
<p>exemplo: a área compreende 25m<sup>2</sup></p>

<pre>
    <code>
         &lt;p&gt;A área compreende 25m&lt;sup&gt;2&lt;/sup&gt;&lt;/p&gt;
    </code>
</pre>

<h2>Fórmulas Matemáticas</h2>
<p></p>Se voce precisa criar formulas complexas, pode usar o MathML, que é uma linguagem de marcação matemática baseada em XML, sendo renderizado em navegadores que tenham suporte.
Para exibir expressões matemáticas no GitHub usando MathML, você pode usar a sintaxe do LaTeX, colocando entre $ o conteúdo desejado.</p>

<p>Exemplo: Para exibir a equação quadrática $ax^2 + bx + c = 0$, você pode usar a fórmula:</p>

$x = \frac{{-b \pm \sqrt{{b^2 - 4ac}}}}{{2a}}$

<p>O código:</p>
<pre>
    <code>
         $x = \frac{{-b \pm \sqrt{{b^2 - 4ac}}}}{{2a}}$
    </code>
</pre>
