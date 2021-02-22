# turkiye-ilce-il-mahalle-sokak-cadde-select-doldurma
Türkiye güncel il-ilçe-mahalle-cadde/sokak adres bilgisini sunar.

son güncelleme: 21.02.2021
https://apicrow.com/adres

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

2) footer bölümüne aşağıdaki kodu ekle
		
		<script>
			select({ilListesi:"ilselect",ilceListesi:"ilceselect",mahalleListesi:"mahalleselect",cadde_sokakListesi:'caddeselect'});
		</script>

# gereklilikler:

ilselect:
şehirlerin listelenmesini istediğiniz select'in id numarası. (gerekli)

		select({ilListesi:"ilselect"});

ilceselect:
İlçelerin listelenmesini istediğiniz select'in id numarası. (ilListesi şart)

		select({ilListesi:"ilselect",ilceListesi:"ilceselect"});

mahalleselect:
Mahallelerin listelenmesini istediğiniz select'in id numarası. (ilListesi ve ilceListesi şart)

		select({ilListesi:"ilselect",ilceListesi:"ilceselect",mahalleListesi:"mahalleselect"});

caddeselect:
Cadde/Sokak/KümeEvler'in listelenmesini istediğiniz select'in id numarası. (ilListesi,ilceListesi ve cadde_sokakListesi şart)

		select({ilListesi:"ilselect",ilceListesi:"ilceselect",mahalleListesi:"mahalleselect",cadde_sokakListesi:'caddeselect'});


