+++
title = "Уникальные системы"
archetype = "default"
url = "new-mechanics/systems"
weight = 1
+++

## Уникальные системы
<gray>Передавать, разрушать, телепортировать</gray>

### Система Транспортировки
{{% carousel %}}
{{% carousel-image "/images/system/transport.png" %}}Система готова к работе{{% /carousel-image %}} 
{{% carousel-image "/images/system/transport-activated.png" %}}Система активирована{{% /carousel-image %}} 
{{% /carousel %}}


{{% notice style="info" title="Раздатчик-транспортёр" %}}
{{% flex %}}
{{% flex-item basis="80%" shrink="1" grow="1" %}}
-- Позволяет моментально **передавать предметы** из раздатчика в хранилище\
-- Для передачи предметов **требуются трубы**\
-- Труба устанавливается у раздающего отверстия \
-- В качестве **труб** используются **громоотводы**\
-- Для поворота **трубы** используется неокисленный **блок меди** <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Раздатчик требует активации</white> {{% /lighting %}}
{{% /flex-item %}}
{{% flex-item basis="20%" %}}
![](/images/system/dispenser-transporter.png)
{{% /flex-item %}}
{{% /flex %}}
{{% /notice %}}

{{% notice style="info" title="Раздатчик-сортировщик" %}}
{{% flex %}}
{{% flex-item basis="80%" shrink="1" grow="1" %}}
-- Позволяет **сортировать предметы**, передаваемые через трубы транспортёра\
-- Для активации фильтра **требуется положить** необходимые предметы внутрь\
-- Раздатчик **устанавливается** на пути труб <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Раздатчик не работает вне системы транспортировки</white> {{% /lighting %}} 
{{% /flex-item %}}
{{% flex-item basis="20%" %}}
![](/images/system/dispenser-sorter.png) 
{{% /flex-item %}}
{{% /flex %}}
{{% /notice %}}

{{% notice style="info" title="Раздатчик-сборщик" %}}
{{% flex %}}

{{% flex-item basis="80%" shrink="1" grow="1" %}}
-- Позволяет **собирать предметы** дальностью в 1 блок от раздатчика\
-- Для активации сборщика **требуется положить** воронки внутрь\
-- **Чем больше** воронок, **тем больше** круговой радиус действия <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Раздатчик требует активаци</white> {{% /lighting %}}
{{% /flex-item %}}
{{% flex-item basis="20%" %}}
![](/images/system/dispenser-collector.png) 
{{% /flex-item %}}
{{% /flex %}}
{{% /notice %}}

{{% notice style="info" title="Дроппер-крафтер" %}}
{{% flex %}}

{{% flex-item basis="80%" shrink="1" grow="1" %}}
-- Позволяет **автоматически создавать предметы**\
-- Для активации крафтера **требуется выложить** крафт предмета внутри\
-- Дроппер **устанавливается** на пути труб\
-- При недостатке хранилища: предметы будут выброшены перед транспортёром <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Дроппер не работает вне системы транспортировки</white> {{% /lighting %}}
{{% /flex-item %}}
{{% flex-item basis="20%" %}}
![](/images/system/dropper-crafter.png)
{{% /flex-item %}}
{{% /flex %}}
{{% /notice %}}

{{% notice style="info" title="Дроппер-выбрасыватель" %}}
{{% flex %}}

{{% flex-item basis="80%" shrink="1" grow="1" %}}
-- Позволяет **выбрасывать вещи**, отправленные транспортером\
-- Для активации выбрасывателя требуется оставить дроппер пустым\
-- Дроппер **устанавливается** на пути труб <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Дроппер не работает вне системы транспортировки</white> {{% /lighting %}}
{{% /flex-item %}}
{{% flex-item basis="20%" %}}
![](/images/system/dropper-dropper.png)
{{% /flex-item %}}
{{% /flex %}}
{{% /notice %}}

### Система «Авто-шахтёр»

{{% carousel %}}
{{% carousel-video "/images/system/autominer-build.mp4" %}}Постройка и включение{{% /carousel-image %}} 
{{% carousel-video "/images/system/autominer-plus-transport.mp4" %}}Добавление системы транспортировки{{% /carousel-image %}} 
{{% /carousel %}}

{{% notice style="info" title="Рамка системы «Авто-шахтёр»" %}}
{{% flex %}}

{{% flex-item basis="80%" shrink="1" grow="1" %}}
-- Используется **для направления** раздатчика-дробителя **по заданной области**\
-- **Сборка рамки**: установить по углам **неокисленные медные блоки**, соединенив их **громоотводами**
{{% /flex-item %}}
{{% flex-item basis="20%" %}}
![](/images/system/miner-frame.png)
{{% /flex-item %}}
{{% /flex %}}
{{% /notice %}}

{{% notice style="info" title="Раздатчик-дробитель внутри системы «Авто-шахтёр»" %}}
{{% flex %}}

{{% flex-item basis="80%" shrink="1" grow="1" %}}
-- Для начала работы **требуется кирка** в раздатчике\
-- **Раздатчик устанавливается** на угловой блок меди, в сторону от рамки\
-- Позволяет **копать блоки** встречающиеся на пути у системы «Авто-шахтёра»\
-- **Остановится**, если в области движения находятся блоки, исключая сыпучие <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Раздатчик требует активации</white> {{% /lighting %}}
{{% /flex-item %}}
{{% flex-item basis="20%" %}}
![](/images/system/miner.png)
{{% /flex-item %}}
{{% /flex %}}
{{% /notice %}}

{{% notice style="info" title="Система «Авто-шахтёр» совместно с Системой Транспортировки" %}}
{{% flex %}}

{{% flex-item basis="80%" shrink="1" grow="1" %}}
-- Для начала работы **требуется добавить громоотводы** в раздатчик-дробитель\
-- Для совместной работы систем **требуется установить громоотвод** с обратной стороны от раздатчика-дробителя. Далее требуется **подключить громоотвод** к хранилищу. <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Система Транспортировки поддерживает любые модификации</white> {{% /lighting %}}
{{% /flex-item %}}
{{% flex-item basis="20%" %}}
![](/images/system/miner-plus-transport.png)
{{% /flex-item %}}
{{% /flex %}}
{{% /notice %}}

### Система «Телепортер»

{{% carousel %}}
{{% carousel-image "/images/system/teleport.png" %}}Система готова к работе{{% /carousel-image %}} 
{{% carousel-image "/images/system/teleport-activated.png" %}}Система активирована{{% /carousel-image %}} 
{{% /carousel %}}

{{% notice style="info" title="Раздатчик отправляющий телепорт" %}}
{{% flex %}}

{{% flex-item basis="80%" shrink="1" grow="1" %}}
-- Позволяет телепортировать сущности к принимающему раздатчику.\
-- Для срабатывания требует топлива: **1 эндер пёрл** на одно использование.\
-- Для телепортации требуются **энд-трубы**\
-- В качестве **энд-труб** используются **стрежни энда**.\
-- Для **поворота направления** энд-трубы используется **блок пурпура**. <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Раздатчик требует активации</white> {{% /lighting %}}
{{% /flex-item %}}
{{% flex-item basis="20%" %}}
![](/images/system/dispenser-teleporter.png)
{{% /flex-item %}}
{{% /flex %}}
{{% /notice %}}

{{% notice style="info" title="Раздатчик принимающий телепорт" %}}
-- Раздатчик **необходимо установить** раздающим отверстием от стержня энда.\
-- Накладывает **негативные эффекты** на того, кто телепортируется.\
-- **Сила эффекта** зависит от расстояния по прямой до раздатчика отправляющего телепорт. <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Раздатчик не работает вне системы телепортера</white> {{% /lighting %}}
{{% /notice %}}