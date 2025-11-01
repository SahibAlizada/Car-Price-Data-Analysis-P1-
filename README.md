🚗 Car Price Prediction — Data Analytics Project
📌 Məqsəd

Bu layihənin məqsədi — avtomobillərin marka, model, il, yürüş, yanacaq növü, mühərrik gücü və digər xüsusiyyətlərinə əsaslanaraq qiymətini proqnozlaşdırmaq və qiymətə təsir edən əsas faktorları müəyyən etməkdir.

📊 Data Mənbəsi

Dataset: Car Price Prediction (Kaggle)

🧩 Addımlar
1️⃣ Kitabxanaların Yüklənməsi

Layihədə istifadə olunan əsas kitabxanalar:

pandas

numpy

matplotlib

seaborn

Bu kitabxanalar məlumatların emalı, analiz və vizuallaşdırılması üçün istifadə olunur.

2️⃣ Data-nın Yüklənməsi

Məlumatlar Google Colab mühitində işlənib.
Dataset drive üzərindən yüklənərək Colab mühitinə daxil edilib.

3️⃣ Data-nın İlkin Analizi

Məlumatları daha yaxşı anlamaq üçün aşağıdakı funksiyalardan istifadə olunub:

data.head()
data.tail()
data.describe()
data.info()


Bu mərhələdə data strukturuna, sütun adlarına, dəyərlərin növünə və ümumi keyfiyyətinə baxılıb.

4️⃣ Data Cleaning

Null dəyərlər yoxlanılıb və lazım olduqda ortalama ilə əvəz edilib.

Dublikat sətirlər silinib.

Data tipləri (integer, float, object) uyğunlaşdırılıb.

Bu mərhələ analiz üçün datanı tam təmiz vəziyyətə gətirib.

5️⃣ EDA (Exploratory Data Analysis)

Vizual analiz mərhələsində aşağıdakı üsullardan istifadə olunub:

Histogram və boxplot-lar (dəyərlərin paylanması üçün)

Pairplot (dəyişənlər arası əlaqələr üçün)

Korelyasiya matrixi (qiymətə təsir edən əsas dəyişənləri tapmaq üçün)

6️⃣ Korelyasiya Analizi

Korelyasiya matrisinə əsasən:

enginesize, horsepower, curbweight və width kimi sütunlar qiymətə müsbət təsir göstərir.

fueltype dəyişəni üzrə diesel avtomobillər ortalama olaraq gas avtomobillərdən ucuzdur.

💡 Əsas Tapıntılar

Mühərrik ölçüsü (enginesize) və horsepower artdıqca avtomobilin qiyməti yüksəlir.

Diesel yanacaq növü olan avtomobillər ortalama olaraq gas növündən ucuzdur.

BMW, Audi, Porsche kimi markalar ən bahalı seqmentdədir.

Curbweight (çəki) və width (eni) qiymətə güclü müsbət təsir göstərir.

Ümumilikdə, texniki parametrlər (ölçü, güc, çəki) avtomobilin qiymətini müəyyən edən əsas göstəricilərdir.

📈 Nəticə və Tövsiyələr

Qiymət təyin etmə modellərində texniki dəyişənlərə (engine, horsepower, curbweight) üstünlük verilməlidir.

Avtomobil istehsalçıları enerji səmərəliliyi və güc balansını optimallaşdırmaqla bazarda daha rəqabətli qiymətlər təklif edə bilər.

Əlavə model qurulması üçün Machine Learning modelləri (Linear Regression, Random Forest və s.) tətbiq edilə bilər.

🧠 Gələcək Addımlar

Modelin təkmilləşdirilməsi üçün feature engineering üsulları əlavə edilə bilər.

Müxtəlif regionlar üzrə qiymət fərqlərini təhlil edən əlavə analitik modullar yaradıla bilər.
