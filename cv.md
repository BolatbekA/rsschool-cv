# Абдукеримов Болатбек
г. Санкт-Петербург, 31 год. 
*****
## Контакты
[Telegram](https://t.me/b_abdukerimov)

abdukerimovbn@yandex.ru — предпочитаемый способ связи

дискорд-сервере rs school **BolatbekA (@BolatbekA)**

[Github](https://github.com/BolatbekA)

[Codewars](https://www.codewars.com/users/BolatbekA)
*****
## Опыт работы

### НУЛЕВИК

Строительство, недвижимость, эксплуатация, проектирование

  • Строительство дорожное и инфраструктурное

#### Менеджер проектов

В компании занимался операционной деятельностью, администрирование работы
подразделений и внешнее взаимодействие с заказчиками, субпордрядчиками. Осуществлял
закупки и снабжение строительных объектов. Выполнял аналитику финансовой деятельности
компании, ведение хоз. деятельности. Внедрил систему внешнего электронного
документооборота. Занимался управлением проектов с крупными заказчиками в
Санкт-Петербурге. За время работы мной было реализовано более 100 проектов в т.ч.:
Заключил пятилетний контракт с ИКЕА на сумму 60млн.р с дальнейшим пролонгированием на
5 лет, на выполнение строительных работ и благоустройства.
Занимался согласованием проекта на строительство складского комплекса площадью
22000кв.м: заключение договора с якорным арендатором на 10 лет и дальнейшие переговоры с
банком «Промсвязьбанк» на получение инвестиционного кредита.
Так же сотрудничал с строительными компаниями: Сетл, Пионер, НКС. Мной были заключены
договоры на благоустройство территорий жилых кварталов.
*****
## Образование:

Петербургский государственный университет путей сообщения,
Санкт-Петербург

Строительный ф-т, Водоснабжение и водоотведение 2017г. 

## Повышение квалификации, курсы:

#### Яндекс.Практикум
Backend-факультет, Python-разработчик (9 месяцев)

https://practicum.yandex.ru/backend-developer/

#### Stepik

"Поколение Python": курс для начинающих

https://stepik.org/course/58852
*****
## Навыки
[![Python](https://img.shields.io/badge/-Python-464646?style=flat-square&logo=Python)](https://www.python.org/)
[![Django](https://img.shields.io/badge/-Django-464646?style=flat-square&logo=Django)](https://www.djangoproject.com/)
[![Django REST Framework](https://img.shields.io/badge/-Django%20REST%20Framework-464646?style=flat-square&logo=Django%20REST%20Framework)](https://www.django-rest-framework.org/)
[![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-464646?style=flat-square&logo=PostgreSQL)](https://www.postgresql.org/)
[![Nginx](https://img.shields.io/badge/-NGINX-464646?style=flat-square&logo=NGINX)](https://nginx.org/ru/)
[![gunicorn](https://img.shields.io/badge/-gunicorn-464646?style=flat-square&logo=gunicorn)](https://gunicorn.org/)
[![docker](https://img.shields.io/badge/-Docker-464646?style=flat-square&logo=docker)](https://www.docker.com/)
[![GitHub%20Actions](https://img.shields.io/badge/-GitHub%20Actions-464646?style=flat-square&logo=GitHub%20actions)](https://github.com/features/actions)
[![Yandex.Cloud](https://img.shields.io/badge/-Yandex.Cloud-464646?style=flat-square&logo=Yandex.Cloud)](https://cloud.yandex.ru/)

Английский — B2

Пример кода [![Python](https://img.shields.io/badge/-Python-464646?style=flat-square&logo=Python)](https://www.python.org/):
```
class RecipeViewSet(viewsets.ModelViewSet):
    queryset = Recipe.objects.all()
    serializer_class = RecipeSerializer
    permission_classes = (IsOwnerOrReadOnly,)
    pagination_class = CustomUserPagination
    filter_class = AuthorAndTagFilter

    def perform_create(self, serializer):
        serializer.save(author=self.request.user)

    @action(
        detail=True,
        methods=['post', 'delete'],
        permission_classes=(IsAuthenticated,),
    )
    def favorite(self, request, pk=None):
        if request.method == 'POST':
            return self.add_obj(Favorite, request.user, pk)
        if request.method == 'DELETE':
            return self.delete_obj(Favorite, request.user, pk)
...
```
*****
## Обо мне

В 30 уйти с хорошей работы непросто, но от любви к технологиям я принял решение на
заняться разработкой. Выбрал Python так как этот язык имеет высокую популярность и
используется в большом количестве проектов. Сравнительно простой, но в то же время
строгий синтаксис.

* Читаю: Изучаем Python Марка Лутца, Грокаем алгоритмы Адитья Бхаргава.
* Слушаю: Запуск завтра, Moscow Python, Релиз в пятницу, Рабочее название
* Учу: JS в https://rs.school/

Увлекаюсь фундаментальным анализом фондового рынка и долгосрочными инвестициями,
но на спорткар еще не накопил)