# Baigiamasis_Darbas: E. receptu isigyjimo prognozavimas 

# Apibūdinimas 

Projketas susideda iš 2 dalių : duomenų tvarkymo ir modeliu kūrimo bei jų lyginimo 

Šiuo projektu siekta išsiaiškinti kuris modelis geba prognozuoti ar receptas nebus isigytas pagal pateiktus duomenis iš Lietuvos atviru duomenu portalo 

link: https://data.gov.lt/dataset/espbi-is-e-recepto-posistemes-duomenys

Naudoti duomenys: 2022 metu Sausio menesio 1; 2; 3 dekados 

# Kertiniai aspektai 

DidŽiausia problematika : 
1. Stulpeliu kiekis naudojant one hot encoder, teko iš analizės pašalinti ligos_koda, vaisto_pavadinima, dozuočių_stipruma, gyventoju_savivaldybe 
2. Duomenų stulpeliai apie vaisto vartojima ar narkotine klase 90 procentu turintys NULL reikšmes. (iš 35 stulpelių 12 jų 90% tuščių) 

# Projekto paleidimas 

Naudoti jupyter Notebook localhost 

