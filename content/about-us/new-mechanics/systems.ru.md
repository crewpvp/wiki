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


{{% carousel %}}
{{% carousel-image "/images/system/dispenser-transporter.png" %}}{{% /carousel-image %}} 
{{% carousel-image "/images/system/tube.png" %}}{{% /carousel-image %}} 
{{% /carousel %}}

{{% notice style="info" title="Раздатчик-транспортер" %}}
-- Позволяет моментально **передавать предметы** из раздатчика в хранилище\
-- Для передачи предметов **требуются трубы**\
-- В качестве **труб** используются **громоотводы**\
-- Для поворота направления **трубы** используется неокисленный **блок меди** <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Раздатчик требует активации</white> {{% /lighting %}}
{{% /notice %}}

![](/images/system/dispenser-sorter.png) 
{{% notice style="info" title="Раздатчик-сортировщик" %}}
-- Позволяет **сортировать предметы**, передаваемые через трубы раздатчика-транспортера\
-- Для активации фильтра **требуется положить** необходимые предметы внутрь\
-- Раздатчик **устанавливается на пути труб**, раздающим отверстием по направлению пути <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Раздатчик не работает вне системы транспортировки</white> {{% /lighting %}}
{{% /notice %}}

![](/images/system/dispenser-collector.png) 
{{% notice style="info" title="Раздатчик-сборщик" %}}
-- Позволяет **собирать предметы** дальностью в 1 блок от раздатчика\
-- Для активации сборщика **требуется положить** воронки внутрь\
-- **Чем больше воронок** внутри раздатчика, **тем больше радиус** действия <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Раздатчик требует активаци</white> {{% /lighting %}}
{{% /notice %}}

![](/images/system/dropper-crafter.png)
{{% notice style="info" title="Дроппер-крафтер" %}}
-- Позволяет **автоматически создавать предметы**, получая ингредиенты через трубы\
-- Для активации крафтера **требуется выложить** крафт предмета внутри\
-- Дроппер **устанавливается на пути труб**, раздающим отверстием по направлению пути\
-- При недостатке хранилища: предметы будут выброшены перед раздатчиком-транспортером <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Дроппер не работает вне системы транспортировки</white> {{% /lighting %}}
{{% /notice %}}

![](/images/system/dropper-dropper.png)
{{% notice style="info" title="Дроппер-выбрасыватель" %}}
-- Позволяет **выбрасывать вещи**, отправленные раздатчиком-транспортером\
-- Для активации выбрасывателя требуется оставить дроппер пустым\
-- Дроппер **устанавливается на пути труб**, раздающим отверстием по направлению пути <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Дроппер не работает вне системы транспортировки</white> {{% /lighting %}}
{{% /notice %}}

### Система «Авто-шахтёр»

{{% carousel %}}
{{% carousel-video "/images/system/autominer-build.mp4" %}}Постройка и включение{{% /carousel-image %}} 
{{% carousel-video "/images/system/autominer-plus-transport.mp4" %}}Добавление системы транспортировки{{% /carousel-image %}} 
{{% /carousel %}}

{{% notice style="info" title="Рамка системы «Авто-шахтёр»" %}}
-- Используется **для направления** раздатчика-дробителя **по заданной области**\
-- **Сборка рамки**: установить по углам **неокисленные медные блоки**, соединенив их **громоотводами**
{{% /notice %}}

{{% notice style="info" title="Раздатчик-дробитель внутри системы «Авто-шахтёр»" %}}
-- Для начала работы **требуется кирка** в раздатчике\
-- **Раздатчик устанавливается** на угловой блок меди, отверстием в сторону от рамки\
-- Позволяет **копать блоки** встречающиеся на пути у системы «Авто-шахтёра»\
-- **Не будет двигаться**, если в области движения расположены блоки, исключая сыпучие <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Раздатчик требует активации</white> {{% /lighting %}}
{{% /notice %}}

{{% notice style="info" title="Система «Авто-шахтёр» совместно с Системой Транспортировки" %}}
-- Для начала работы **требуется добавить громоотводы** в раздатчик-дробитель\
-- Для совместной работы систем **требуется установить громоотвод** с обратной стороны от раздатчика-дробителя. Далее требуется **подключить громоотвод** к хранилищу. <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Система Транспортировки поддерживает любые модификации при совместной работе</white> {{% /lighting %}}
{{% /notice %}}

### Система «Телепортер»

{{% carousel %}}
{{% carousel-image "/images/system/teleport.png" %}}Система готова к работе{{% /carousel-image %}} 
{{% carousel-image "/images/system/teleport-activated.png" %}}Система активирована{{% /carousel-image %}} 
{{% /carousel %}}

{{% notice style="info" title="Раздатчик отправляющий телепорт" %}}
-- Позволяет телепортировать сущностей, стоящих перед ним, к принимающему раздатчику.\
-- Для срабатывания требует топлива: **1 эндер пёрл** на одно использование.\
-- Для телепортации требуются **энд-трубы**. В качестве **энд-труб** используются **стрежни энда**.\
-- Для **поворота направления** энд-трубы используется **блок пурпура**. <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Раздатчик требует активации</white> {{% /lighting %}}
{{% /notice %}}

{{% notice style="info" title="Раздатчик принимающий телепорт" %}}
-- Раздатчик **необходимо установить** раздающим отверстием от стержня энда.\
-- Накладывает **негативные эффекты** на того, кто телепортируется.\
-- **Сила эффекта** зависит от расстояния по прямой до раздатчика отправляющего телепорт. <br> {{% lighting color="var(--INTERNAL-BOX-INFO-color)" %}} <white><i class="fa-solid fa-circle-exclamation fa-xs"></i> Раздатчик не работает вне системы телепортера</white> {{% /lighting %}}
{{% /notice %}}