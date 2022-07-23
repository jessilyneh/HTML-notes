<h1>Audio</h1>

<p>A tag &lt;audio&gt; contém uma ou mais tags &lt;source&gt; com diferentes fontes de áudio. O navegador escolhe a primeira fonte que ele suporta.</p>

<p>O texto entre as tags &lt;audio&gt; e &lt;/audio&gt; só será exibido em navegadores que não suportam o elemento &lt;audio&gt;.</p>

<p>Existem três formatos de áudio suportados em HTML: MP3, WAV e OGG.</p>

<code>
    &lt;audio controls&gt;
        &lt;source src="/Audio/passaros.mp3" type="audio/mpeg"&gt;
        &lt;source src="/Audio/passaros.ogg" type="audio/ogg" codec="opus"&gt;
        Seu browser não suporta esse arquivo de audio
    &lt;/audio&gt;
<code>

<h2>Atributos</h2>
<h3><em>controls</em></h3>
<p>É um atributo booleano.</p>
<pre>
<p>Especifica que os controles de áudio devem ser exibidos.
Os controles de áudio incluem:

Play
Pause
Volume
Baixar arquivo
Velocidade de reprodução
</p>
</pre>