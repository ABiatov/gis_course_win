Курс ГИС для разработчиков
===========================

https://kolesovdmitry.github.io/gis_course_win/

В курсе использованы материалы курса "ВЕБ ГИС для начинающих" (http://drnextgis.github.io/webgis_course_win/)

Содержание курса

1. Системы координат и проекции.
  Понятия элипсоида, датума, системы координат и проекции. Примеры часто используемых проекций. Искажения длин, площадей и углов. Коллекция описаний систем координат EPSG. Библиотека PROJ4 для работы с системами координат.
  Практические занятия по перепроецированию данных с использованием библиотеки PROJ4.
2. Форматы данных и основные операции с данными.
2.1. Векторные.
  Понятие векторных данных. Стандарт OGC описания векторных данных. Обзор популярных форматов векторных данных. Операции с векторными данными.
  Практические занятия на операции с векторными данными.
2.2. Растровые.
  Понятие растровых данных. Популярные растровые форматы (используемые для геообработки). Операции с растровыми данными. "Привязка" растровых материалов.
  Практические занятия по привязке растров.
3. Поддержка обработки геоданных в СУБД Postgres и SQLite.
  3.1. Пространственные расширения языка SQL для работы с векторными данными.
    Основные функции расширения SQL для работы с векторными данными (базовые функции, топологические функции, функции пространственного анализа).
    Практические занятия с векторными операциями в PostGIS.
  3.2. Пространственное расширение PostGIS для работы с растровыми данными (хранение растров в БД, SQL запросы с обработкой растровых данных).
    Практические занятия с растровыми операциями в PostGIS.
4. Использование возможностей инструментальных ГИС в программном коде.
  4.1. ГИС с открытым исходным кодом: обзор возможностей; особенности разработки, накладываемые лицензиями.
  4.2. Использование библиотеки GDAL.
    4.2.1 Утилиты командной строки gdalinfo, gdalwarp, gdal_translat, gdal_calc.py, ogrinfo, ogr2ogr и др.
      Практическое занятие на использование утилит GDAL. 
    4.2.2. Использование библиотеки GDAL в своем коде.
      Обработка векторных данных (на C++): открытие векторных данных, получение информации по ним. Создание нового слоя данных на примере построения буферных зон вокруг объектов исходного слоя. Перепроецирование векторных слоев. Сохранение векторных слоев.
      Обработка растровых данных (на C++): открытие растровых слоев, получение информации по растровым слоям, создание нового растрового слоя, сохранение результатов обработки.
  4.2.3 Использование QGIS для создания ГИС-приложений.
    Обзор возможностей QGIS.
    Создание GUI приложения на базе QGIS: вывод на экран заданного слоя со стилем по умолчанию, вывод слоя слоя с применением стилей qml.
    Создание консольного приложения на базе QGIS: отрисовка слоев в png с прозрачным фоном, отрисовка слоев с применением стилей qml; получение информации по объектам векторного слоя в заданных координатах. 
  4.3. Использование GRASS GIS для "сложной" аналитики и обработки геоданных.
    Обзор возможностей GRASS GIS с точки зрения разработчика.
    Создание консольного приложения на базе GRASS GIS для анализа геоданных (на примере задачи выявления "проблемных" участков местности): открытие базовых слоев и слоев с результатами наблюдений, интерполяция результатов измерений, поиск "проблемных" участков, экспорт результатов.



Вы можете пройти этот курс под руководством его создателей:
http://nextgis.ru/services/training/


Лицензия на материалы курса: CC-BY-SA

