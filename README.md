# Weather-App-Release  
  
## Описание и предназначение проекта   
Это максимально лаконичное погодное приложение для андроид-пользователей, в котором я попытался сохранить только самые необходимые виджеты, которыми пользуюсь сам в других погодных приложениях. В этом проекте я был лично заинтересован, так как не люблю лишний шум в современных погодных приложениях и кучу разных показателей, половина из которых мне были непонятны, пока я не разобрался в них в ходе написания своего приложения. Моей целью было написать приложение, в которое можно глянуть мельком и одеться по погоде. 
  
## Источники данных  
Статические карты для виджета с картой осадков позаимствовал у Яндекса:    
https://yandex.kz/maps-api/docs/static-api/index.html  
Условия:    
https://yandex.ru/legal/maps_api/  
Данные для своих погодных «виджетов» я брал из открытого источника Open-Meteo:   
https://open-meteo.com/    

Мой выбор пал именно на эти ресурсы в первую очередь из-за доступности и возможности бесплатного пользования. Open-Meteo не нужны никакие API-ключи, регистрация или подписка — всё просто и сердито, а карты осадков от Яндекса дают достаточно точные, по моему мнению, данные.  

## Внешний вид приложения  
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/prew_white.jpg)  
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/prew_black.jpg)   
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/prew_black_2.jpg)   
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/prew_black_3.jpg)   
  

## Что умеет мое приложение  
- Автоматически определить локацию пользователя
- Менять фон в зависимости от времени суток
- Определять тип погоды
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/type.jpg)     
- Считать температуру по ощущениям
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/files_like.jpg)     
- Составлять прогноз на неделю
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/daily.jpg)     
- Показывать время восхода и заката солнца
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/sunrise_sunset.jpg)     
- Показывать уровень влажности, а также направление и силу ветра
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/humidity_wind.jpg)     
- Составлять прогноз на следующие 24 часа
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/24_hour.jpg)     
- А также ссылаться на карту осадков Яндекс Карт

## Как затестить приложение   
Специально для вас оставлю APK-файл с моим приложением в этой ветке

P.S. Я убрал статические карты и стер поле с геопозицией пользователя на скринах.
