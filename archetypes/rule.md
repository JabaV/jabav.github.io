---
title: '{{ replace .File.ContentBaseName "-" " " | title }}' #отображаемое название
date: '{{ .Date }}' # дата 
weight: 2 # вес статья (чем ближе к 1, тем выше статья)
# aliases: ["/first"]
author: ["JabaV", "Cameraman"] # Авторы статьи.
showToc: true #  показывать Навигатор на страницу
TocOpen: true # развернуть Навигатор по умолчанию
draft: false # черновая страница
hidemeta: false # полностью убрать метаданные
comments: false # включает комментарии, если провайдер комментариев настроен
description: "" # описание
disableHLJS: true # to disable highlightjs
disableShare: true # убирает гиперссылки шейринга с конца страницы
hideSummary: true # скрывает текст с превью
searchHidden: true # скрытие строки поиска
ShowReadingTime: true # время чтения в метаданных
ShowBreadCrumbs: false # навигационная цепочка
ShowPostNavLinks: true # перемещение между статьями 
ShowWordCount: true # количество слов в метаданных
ShowRssButtonInSectionTermList: false # хз
UseHugoToc: false # юзать Hugo Навигатор
disableScrollToTop: false # отключить кнопку скроллинга вверх
hideFooter: true # прячет задницу страницы
swiper: false # не трогать, если не нужна карусель
editPost: false # кнопка редактировакния поста
---