forocosas
=========

cosas del foro
<vb:literal>
<script>
$(window).load(function(){
$(&#39;.botones-sociales .social&#39;).mouseenter(function(){
$(this).stop();
$(this).animate({width:&#39;160&#39;}, 500, &#39;easeOutBounce&#39;,function(){}); 
});
$(&#39;.botones-sociales .social&#39;).mouseleave(function(){
$(this).stop();
$(this).animate({width:&#39;43&#39;}, 500, &#39;easeOutBounce&#39;,function(){});
});
});
</script></vb:literal>

<div class='botones-sociales izquierda hidden-phone hidden-tablet'>
<a class='itemsocial' href='https://www.facebook.com/ForoPTC' id='facebook-btn' target='_blank'><span class='social'></a>
<a class='itemsocial' href='https://twitter.com/foro_ptc'id='twitter-btn' target='_blank'><span class='social'></span></a>
<a class='itemsocial' href='https://plus.google.com/b/108046020117282219397/' id='rss-btn' target='_blank'></a>
<a class='itemsocial' href='http://www.foro-ptc.com/boletin.html' id='pinterest-btn' target='_blank'><span class='social'><span class='texto'>Síguenos via RSS</span></span></a>
</div>
