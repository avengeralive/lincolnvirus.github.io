---
layout: post-ea

group: Технический советник
title: «REAl swap trade»
meta: «REAl swap trade». В основе работы советника лежит принцип торговли в направлении положительного свопа. Все средства, вырученные от продажи данного продукта, будут направлены на развитие проекта и благотворительность.

logo: real_swap_trade.svg
og: img/og-swap-trade.jpg

order: 9

category: ea

lang: ru
ref: real_swap_trade
---
 
**Стратегия:**  

В основе работы советника лежит принцип торговли в направлении положительного свопа, что позволяет иметь дополнительный доход от его начисления, даже находясь длительное время в рынке.  

**Вход**  

Вход осуществляется один раз в день в установленное время (Entry Time) по направлению положительного свопа. Размер лота может быть фиксированным или рассчитанным на основе текущего баланса депозита (Balance Lot  / Balance Step) или доли баланса депозита (Symbol Balance %), отведенной для текущего инструмента. Есть возможность установки TakeProfit и StopLoss. 

В случае, когда цена идёт против открытого ордера, предусмотрено формирование сетки ордеров с открытием на круглых ценовых уровнях. Размер лота для ордеров сетки может быть фиксированным или рассчитываться с применением метода «Мартингейла», есть возможность ограничить количество ордеров сетки. Управление ордерами сетки, выход при достижении заданной прибыли в деньгах, закрытие при достижении установленной просадки в %, а также трейлинг прибыли осуществляется для всех ордеров сетки.  

**Фильтры**  

Используются следующие фильтры для подтверждения входа:
  - Минимальное расстояние от цены входа до скользящей средней с установленными параметрами (MA Filter);  
  - Минимальное расстояние от цены входа до полос Боллинжера с установленными параметрами (Bollinger Bands Filter);  
  - Разрешение торговать только в среду;  
  - Разрешение/запрет торговать в пятницу;  
  - Минимальное время, которое должно пройти между открытием ордеров.  
  
**Выход**  

Закрытие ордера возможно при следующих условиях:
  - Возвращение цены к уровню открытия ордера при условии, что своп уже был начислен и прибыль ордера больше 0 (Exit on the return to Order Level);  
  - Пересечение ценой скользящей средней, использованной как фильтр при входе в рынок, при условии, что своп уже был начислен (Exit on MA used for filter);  
  - Пересечение ценой полосы Боллинжера, использованной как фильтр при входе в рынок при условии, что своп уже был начислен (Exit on BB used for filter);  
  - Время нахождение ордера в рынке превышает установленное ограничение (Time Closing);  
  - В установленное время пятницы перед началом выходных (Close Orders before Weekend).
  
Также возможно уменьшение TakeProfit ордера через установленное время (TakeProfit Reducing).  

**Особенности:**
  - Настройка времени торговли;
  - Система расчёта объёма ордера;
  - Советник адаптирован для работы на 4х и 5ти-значных котировках;
  - Возможность использования на всех тайм-фреймах;
  - Возможность использования на всех торговых инструментах;
  - Информационная панель.

**Стоимость продукта:**  
	100$ (.ex4)  
	1000$ (.mq4)
  
**Рекомендации предоставляются в полном объёме по использованию технического советника и торговым условиям предоставляемыми брокером. Не соблюдение рекомендаций ведёт за собой увеличение рисков и остаётся только под ответственностью пользователя.**
  
  **Схема сотрудничества:**  

- Пользователь получает всю необходимую информацию и ответы на интересующие вопросы;  
- Пользователь предоставляет номер счёта и имя указанные в терминале;  
- Проект «Lincoln virus» подготавливает все необходимые файлы (5-15 минут);  
- После оповещения о готовности файлов, пользователь производит оплату в полном объёме;  
- Проект «Lincoln virus» отправляет все необходимые файлы для начала работы через «<a href="skype:chutkoy89?call" target="_blank">Skype</a>» / «<a href="https://t.me/chutkoy" target="_blank">Telegram</a>» или электронный адрес почты;  
- Проект «Lincoln virus» производит установку и настройку отправленных файлов через программу «<a href="https://www.teamviewer.com/ru/" target="_blank">TeamViewer</a>».

**В целях безопасности технических советников серии «REAl», проект «Lincoln virus» не предоставляет пробную (демонстрационную) версию (даже на 1 день или на 5 минут).**  
**Во избежание несанкционированного копирования сделок через сторонние копировальщики сигналов, проект «Lincoln virus» не предоставляет пароль инвестора для мониторинга сделок в реальном времени.**

Все средства, вырученные от продажи данного продукта, будут направлены на развитие проекта и благотворительность.

По всем вопросам Вы можете связаться со мной через <a href="skype:chutkoy89?call" target="_blank"><span style="background-color:#00aff0; color:white; padding:3px; border-radius: 3px">Skype</span></a> / <a href="https://t.me/chutkoy" target="_blank"><span style="background-color:#0088cc; color:white; padding:3px; border-radius: 3px">Telegram</span></a>.

**Предупреждение о риске: торговля «REAl swap trade» предполагает высокую степень риска. Прежде чем начать торговлю, я советую вам тщательно проанализировать свои инвестиционные цели, имеющиеся у вас в этой области опыт и готовность к риску.**
