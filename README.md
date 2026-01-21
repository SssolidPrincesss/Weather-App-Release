# Weather-App-Release  
  
## Описание и предназначение проекта   
Это максимально локоничное погодное приложение для андроид пользователейЮ, в котором я попытался сохраниить только самые необходимые виджеты, которыми пользуюсь сам в других погодных приложениях. В этом проекте я был лично заинтересован, так как не люблю лишний шум в современных погодных приложениях и кучу разных показателей, половина из которых мне были непонятны, пока я не разабрался в них в ходе написания своего приложения. Моей целью было написать приложение, в которое можно глянуть мельнком и одеться по погоде.  
  
## Источники данных  
Статические карты для виджета с картой осадков позаимствовал у яндекса:    
https://yandex.kz/maps-api/docs/static-api/index.html  
Условия:    
https://yandex.ru/legal/maps_api/  
Данные для своих погодых "виджетов" я брал из открытого источника Open-Meteo  
https://open-meteo.com/    

Мой выбор пал именно на эти реесурсы, в первую очередь из-за доступности и возможности бесплатного пользования. Open-Meteo не нужны никакие API-ключи, регистрация или подписка - все просто и сердито, а карты осадков от яндекс дают достаточно точные по моему мнению данные.  

## Внешний вид приложения  
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/prew_white.jpg)  
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/prew_black.jpg)   
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/prew_black_2.jpg)   
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/prew_black_3.jpg)   
  

## Что умеет мое приложение  
- Автоматичесски определать локацию пользователя
- Менять фон в зависимости от времени суток
- Определять тип погоды
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/type.jpg)     
- Считать температуру по ощущениям
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/files_like.jpg)     
- Составлять прогноз на неделю
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/daily.jpg)     
- Показывать время восхода и заката солнца
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/sunrise_sunset.jpg)     
- Показывать уровень влажности, а так же направление и силу ветра
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/humidity_wind.jpg)     
- Составлять прогноз на следующие 24 часа
![menu](https://github.com/SssolidPrincesss/Weather-App-Release/blob/main/images/24_hour.jpg)     
- А так же ссылаться на карту осадков яндекс карт

## Как затестить приложение   
Специально для вас оставлю апк файл с моим приложением в этой ветке, а так же видос с работой приложения

PS. Я убрал статичесские карты и затер поле с геопозицией пользователя на скринах
