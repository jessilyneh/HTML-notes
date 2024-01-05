<h1> div e span </h1>
<p>Devem ser utilizados apenas nos casos onde:</p>
<ul>
  <li>Não exista outro elemento semântico mais adequado;</li>
  <li>Envolver um grupo de elementos ou frase para aplicar alguma estilização (CSS) ou ação (Javascript)</li>
</ul>
<p>Tanto a div como spam fazem a mesma coisa: NADA. Servem apenas para envolver elementos.</p>
<h2> &lt;div&gt;</h2>
<p>Utilizada para blocos de código, como por exemplo, aplicar uma determinada estilização definida no CSS, usando "class".</p>

  <pre>
    <code>
    &lt;div class="container"&gt;
      &lt;h2&gtHTML Notes&lt;/h2&gt;
      &lt;p&gtRepositório de assuntos importantes sobre HTML &lt;/p&gt;
    &lt;/div&gt;
    </code>
  </pre>
  
<h2> &lt;spam&gt;</h2>
<p>Utilizada para edição inline (em linha) de um elemento, como por exemplo, aplicar estilização para uma frase em outro idioma. </p>

  <pre>
    <code>
    &lt;div class="container"&gt;
      &lt;p&gtLorem ipsum dolor sit amet, consectetur adipiscing elit.
       &lt;spam class="subtitle"&gt;Pellentesque habitant morbi &lt;/spam&gt; tristique senectus et netus et malesuada fames ac turpis egestas.</ &lt;/p&gt;
    &lt;/div&gt;
    </code>
  </pre>
