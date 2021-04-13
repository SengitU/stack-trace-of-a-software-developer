Hala TODO ama gecen seferden daha az TODO

Herhangi bir sirkette calismaya basladigimda ciddi seviyede gerginlik yasarim. Sonucta her sistemin kendi dinamikleri vardir ve bu sistemin nasil isledigini anlamak kisinin ilk aylardaki en onemli odevidir. Bazi seyleri degistirmenin zor oldugu sistemler, genelde "agile" dusunce sistemini oturmakta zorlanan sirketlerdir. Yazilim endustrisinin rekabetci yapisindan oturu, sistemler degisiklik yapmaya acik olmalidir. Tabii ki sistemin dinamizmini kullanilan teknolojiler ile olcmek mumkundur, fakat yeterli degildir.

Bir karara meydan okudugunuzda(challenge'in daha guzel cevirisi var mi?), 

- bu kararin neden alindigi
- pozitif ve negatif yanlari sizle paylasiliyor ise

ve edinilen bilgiler dogrultusunda sizin sisteme dahil olmaniz saglaniyorsa elimizde guzel bir baslangic var demektir. Fakat sistemin size vermis oldugu tepki daha cok

- Biz bunu hep boyle yaziyoruz
- Yazilim mimari bu sekilde yazmamizi istiyor

yonundeyse, dinamizmden bahsetmek bir sonraki sirketinize nasip olacaktir diye umuyorum KEKW.

Tabii ki meydan okudugunuz karara ne sartlarla meydan okudugunuz da cok onemlidir. Oznel konulari tartismak takim dinamikleri olan bir ortamda cok anlamli degildir. Dolayisiyla dogru bir degerlendirme yapabilmek, bizim de kendimizi ne konuda ve nasil ifade ettigimizle orantilidir. Burada simdi yarim saat soru nasil sorulur oneri nasil yapilir bahsetmek istiyorum ama su ana kadar yazdigim hicbir seyin konu basligiyla alakasi yok, WTF! Bu kisim da bir chapter olucak belli ki.

Yukarida bahsettigim ve onceki gonderi(maybe even sayfa?)lerde de bahsetmis olacagim(WTF?) sebeplerden oturu yeni bir ise baslamak benim icin her zaman belirli bir stres oraniyla gelir. Yine, yeni basladigim bir pozisyonda, bir takim arkadasimla beraber calismak uzere bir ticket(is birimi?) icin sorumluluk aldik.

Is icin hali hazirda bir sure degerlendirmesi(story point) yapilmisti ve biz bunu degistirme ihtiyaci hissetmedik, istesem de sisteme hakim olmadigim icin muhtemelen isabetli bir sekilde degistiremezdim. Ve tabii ki is bekledigimizden daha gelismis bir cozum sunmamiz gerektirdi. Cesitli mikro-servislerde gerekli guncellemeleri yaptiktan sonra cesitli sorunlar yasamaya basladik. Daha spesifik? olarak bahsetmem gerekirse, gonderdigimiz content, yaptigimiz maskeleme isleminden sonra cesitli tarayicilarin(Merhaba IE <3) yorumlayamayacagi kadar uzun hale geliyordu. Bu problem iki farkli sekilde cozulebilirdi, fakat o anda kolay olan cozumu ne ben, ne takim arkadasim, ne de teknik liderim gorebilmisti. Dolayisiyla takim liderimizin onerdigi bir cozume yonelerek, cozum denklemine bir servis daha ekledik. Bu cozum bizi bir adim ileri goturdu ve cozume yaklastigimiz konusunda heyecanlandirdi. 

Iste tam bu noktada thrill of the hunt hissiyati basladi. Buldugumuz ve/veya kalite sisteminden donen bazi problemler temel olarak sisteme ekledigimiz servisle alakaliydi ve biz bu noktada kararimizi yeniden degerlendirebilirdik. Fakat bu gerceklesmedi. Bir problemi cozmeye, bir isi sonuclandirmaya cok yaklastiginizda problemi cozecek olmanin verdigi heyecandan oturu genel sistemi dusunme algisi azalabilir. Fakat onemli olan sadece problemi cozmek degil, problemi verimli, genisletilebilir ve en onemlisi dayanikli(resilient), hatasiz(bug-free?) bir sekilde cozmektir. Avin verdigi heyecana kapildigimizda, artik o is(ticket olan) kisisellesmistir ve siz profesyonellikten bir adim uzaklasmissinizdir. Tabii ki isinizi iyi yaptiginiz icin heyecan duymayin ya da profesyonel insan heyecan duymaz demiyorum, bilakis isimi heyecanla yapiyorum. Fakat avin heyecanina kapilmak sadece problemi cozmeye odaklanmaya sebep olabilir ve cozumun ne kadar dayanikli oldugunu naif bir sekilde gormezden gelebilirsiniz.

Iste ben de tam olarak avin heyecanina kapildim ve gereksiz bir sekilde dahil ettigimiz servisi bug by bug yamadim da yamadim. Bu heyecanin hayal kirikligina donnusmesi tabii ki cok uzun zaman almadi ve sonuc olarak isi soz verdigimiz surede bitiremedik. Nasil bir hayal kirikligi oldugunu tahmin edebildiginizi umuyorum PepeHands.

Sonrasinda verdigimiz karari tekrar degerlendirmeye karar verdik ve alternatifin uzerine daha fazla dusundugumuzde, bu problemi kendi kendimize yarattigimizi farkettik. Olusturdugumuz dizi ciktisinin her elemaninda tekerrur eden bir simge(attribute?)'nin sadece bir kez yazilmasinin yeterli olacagini fark ettik ve kodumuzu yaklasik 3 gun onceye dondurerek, uzerine sadece ufak bir kod parcacigi ekledik ve problemi cozduk!

Su anda dusundugumde, o problemin nasil cozulemeyecegini kanitlayip, sonrasinda cozulmesi gerektigi gibi cozmusuz gibi hissediyorum. Kisa bir sure uzerisinde, verimizi de inceleyerek verdigimiz daha ozenli bir karar ihtiyacimiz olan tek seydi. Tabii ki takim lideri tarafindan onerilen cozumu yegane cozum ilan etmeden once daha fazla inceleseydik nereden baksaniz 2 gun kazanabilirdik.

Onemli olan isi bitirmek degil, isi en az endustrinin temel olarak kabul ettigi kalite standartlari seviyesinde bitirmektir.

Burada bu sartlari gunumuz sartlarinda, kendimce, endustri standartlariyla butunlestirmek istiyorum. Cunku su anda yazilim endustrisinin yazilimi ileri tasiyan temel guc oldugunu dusunuyorum. Dolayisiyla yazilim cevreleri ile bagli kalmak asiri onemli, bu da baska post konusu.
