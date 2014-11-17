ifIE
====

Adapting legacy Internet Explorer to HTML5 and CSS3 standards. Simply add the following lines of code into your head tags to fix most compatabilty issues. 




```html
<meta http-equiv="X-UA-Compatible" content="IE=edge">

<!-- Using ie 8 or lover? this will detect it -->
<!--[if lt IE 9]>
  <script type='text/javascript' src="https://cdnjs.cloudflare.com/ajax/libs/modernizr/2.8.3/modernizr.min.js"></script>
  <script type='text/javascript' src="https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.2/html5shiv.min.js"></script>
	<script type='text/javascript' src="//cdnjs.cloudflare.com/ajax/libs/respond.js/1.4.2/respond.js"></script>

<script type="text/javascript">
  document.createElement('header');
  document.createElement('nav');
  document.createElement('menu');
  document.createElement('section');
  document.createElement('article');
  document.createElement('aside');
  document.createElement('footer');
</script>
<![endif]-->




```



