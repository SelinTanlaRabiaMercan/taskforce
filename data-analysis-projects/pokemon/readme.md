# Pokemon Veri Analizi

## Pokemon Veri Seti

Bu projede pokemonlar üzerinde veri analizi yapacağız! Veri seti dosyasına [buradan](https://raw.githubusercontent.com/yigitatesh/ml/main/datasets/pokemon.csv) ulaşabilirsiniz.

Veri setimiz genel olarak şöyle: <br>

![Pokemon Veri Seti](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/data-analysis-projects/pokemon/figures/pokemon_veriseti.png)

Veri setimizdeki sütunların anlamlarını bir inceleyelim: <br>

<b>id</b>: Pokemonun ID numarası <br>
<b>name</b>: Pokemonun adı <br>
<b>type1</b>: Pokemonun tipi (ateş, su gibi) <br>
<b>type2</b>: Pokemonun ikincil tipi (varsa) <br>
<b>hp</b>: Toplam can puanı (hasar alma kapasitesi) <br>
<b>attack</b>: Saldırı gücü <br>
<b>defense</b>: Saldırılara karşı savunma gücü <br>
<b>sp_attack</b>: Özel saldırı gücü <br>
<b>sp_defense</b>: Özel saldırılara karşı savunma gücü <br>
<b>speed</b>: Pokemonun hızı <br>
<b>generation</b>: Pokemonun jenerasyonu <br>
<b>is_legendary</b>: Pokemon efsanevi mi değil mi onu belirler (1 ise efsanevi 0 ise değil) <br>

## Veri Setini Okuma

[Buuradaki](https://raw.githubusercontent.com/yigitatesh/ml/main/datasets/pokemon.csv) dosyayı sağ tıklayıp "Farklı Kaydet" diyerek indirip okuyabilirsiniz. Ya da direkt olarak 'pd.read_csv("https://raw.githubusercontent.com/yigitatesh/ml/main/datasets/pokemon.csv")' kodu ile okuyabilirsiniz. <br>

## Veri Analizi Soruları

Aşağıdaki soruları kod yazarak ve veri analizi yaparak cevaplamanızı istiyoruz. Başarılar! <br>

### 1) Hangi pokemon en yüksek saldırı (attack) gücüne sahip? 

### 2) Saldırı ve savunma güçleri eşit olan pokemonlar kaç tane?

### 3) Jenerasyonlardaki pokemon sayılarının dağılımı nedir? (Görselleştirme yapabilirsiniz)

### 4) En çok görülen pokemon tipi nedir? (Birincil tipe bakın)

### 5) Birlikte en çok görülen tip 1 ve tip 2'ler nelerdir?

### 6) Pokemonların sağlık, saldırı, savunma, özel atak, özel savunma ve hız değerlerini inceleyin. Analiz yapın.


