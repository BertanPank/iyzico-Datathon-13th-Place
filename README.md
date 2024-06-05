Competition Name: iyzico Datathon

Competition Link: https://www.kaggle.com/competitions/iyzico-datathon/leaderboard

Result: 13th/328

!!!
[TR]

Kod aşırı derecede dağınık ve içinde kullanılan ve kullanılmayan birçok fikir bulunduruyor.

Fikirler faydalı olabilir ama aradığınız şey temiz kodsa bu repodan uzak durmanızı tavsiye ederim :D


[EN]

The code is extremely cluttered and contains many ideas that are both used and unused.

The ideas might be useful, but if you're looking for clean code, I would advise staying away from this repo
!!!

--------------------------------------------------------------------------------------------------------

[TR]

Problem: Verilen 3 senelik dataset kullanılarak 26,060 satıcının net işlem miktarlarını önümüzdeki üç ay için tahmin eden bir Zaman Serisi modelinin geliştirilmesi.

Yaklaşımım:

Uzun süre transaction yapmayıp geri dönen müşterilerin geri dönüş öncesi verileri datasetten atıldıktan sonra müşteriler, 2020'den beri hizmeti kullananlar, 2021 veya 22'den beri hizmeti kullananlar ve 2023'ten beri hizmeti kullananlar olarak üçe ayrılarak bu veri setleriyle ayrı ayrı modeller eğitildi. Bu da benzer zaman serileri bir arada eğitildiği için daha başarılı ensemble modelleri eğitilmesini sağladı.

---------------------------------------------------------------------------------------------------------

[EN]

Problem: Developing a Time Series model to predict the net transaction amounts for 26,060 merchants over the next three months using the provided 3-year dataset.

My approach:

After removing the data of customers who had long periods of inactivity and then returned, the customers were divided into three groups: those who have been using the service since 2020, those who started using it in 2021 or 2022, and those who started using it in 2023. Separate models were trained with these datasets. This approach allowed for training more successful ensemble models since similar time series were trained together.

