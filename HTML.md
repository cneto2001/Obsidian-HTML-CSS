```HTML
<!--Comment-->
<strong></strong> <!--Bold-->
<p></p> <!--Paragraph-->
<!-- -->
```

```HTML
<!-- Aplica o style a todas as tags <p></p> -->
<!-- #a Aplica somente ao que possui "a" como id. Sobrepõe a mudança feita-->
<!-- no código realizado abaixo-->
<style>
	#a {
		color: red;
		font-size: 18px;
	}
	p {
		color: yellow;
		font-size: 36px;
	}
	
</style>
<p id="a">
	Aprendendo CSS
</p>

<p>
	CSS eh Estilo
</p>
```

&nbsp
</br> ==> Line Break

```HTML
<!--Abrir Nova Aba ao Clicar no link --> 
<a>
 	target="_blank"
</a>

<ol></ol> <!--Ordered List, i.e. -->
<!--1. -->
<!--2. -->
<!--3. -->
<!--   -->
<ul></ul> <!--Unordered List -->
<nav></nav> <!--Tag semântica ==> contém uma lista -->
```

**section** ==> Utilizado para agrupar textos.
Boa prática: Usar h2 em sections.