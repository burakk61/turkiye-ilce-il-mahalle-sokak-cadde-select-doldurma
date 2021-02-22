# turkiye-ilce-il-mahalle-sokak-cadde-select-doldurma
Türkiye güncel il-ilçe-mahalle-cadde/sokak adres bilgisini sunar.



	<head>
    <script type="text/javascript" src="https://apicrow.com/adres/select.js" language="javascript"></script>
	</head>
	
	<body>
		
	<select id="ilselect">
	<option>...</option>
	<option>...</option>
	<option>...</option>
	</select>


	<select id="ilceselect">
	<option>...</option>
	<option>...</option>
	<option>...</option>
	</select>

	<select id="mahalleselect">
	<option>...</option>
    	<option>...</option>
   	<option>...</option>
	</select>

	<select id="caddeselect">
	<option>...</option>
 	<option>...</option>
   	<option>...</option>
	</select>
		
	</body>
  
	<script>
	select({ilListesi:"ilselect",ilceListesi:"ilceselect",mahalleListesi:"mahalleselect",cadde_sokakListesi:'caddeselect'});
	</script>
