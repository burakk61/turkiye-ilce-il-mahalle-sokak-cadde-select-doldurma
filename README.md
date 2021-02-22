# turkiye-ilce-il-mahalle-sokak-cadde-select-doldurma
Türkiye güncel il-ilçe-mahalle-cadde/sokak adres bilgisini sunar.

# ÖRNEK KULLANIM:

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


# kurulumu:
1) head tagının içerisine aşağıdaki kodu ekle
	
		<script type="text/javascript" src="https://apicrow.com/adres/select.js" language="javascript"></script>

2) footer bölümüne aşağıdaki kodu ekle	<script>
		
		<script>
			select({ilListesi:"ilselect",ilceListesi:"ilceselect",mahalleListesi:"mahalleselect",cadde_sokakListesi:'caddeselect'});
		</script>

ilselect:
şehirlerin listelenmesini istediğiniz select'in id numarası. (gerekli)

ilceselect:
İlçelerin listelenmesini istediğiniz select'in id numarası. (boş bırakılabilir)

mahalleselect:
Mahallelerin listelenmesini istediğiniz select'in id numarası. (boş bırakılabilir)

caddeselect:
Cadde/Sokak/KümeEvler'in listelenmesini istediğiniz select'in id numarası. (boş bırakılabilir)


