<div align="center">
  <h1>Дашборд конверсий</h1>
</div>

В данном репозитории анализируются статистические данные посещений и регистраций на сайте за 2023 год.
Данные визитов и регистраций подгружаются с интернет ресурса, рекламы -- берутся из файла ads.csv из корневой директории.
Рассчитывается конверсия посещений, строятся графики посещений, конверсий, стоимости относительно рекламы.


## Как работать

1. Для подргузки данных и редактирования необходимо установить Jupyter Notebook через Anaconda.Скачать Anaconda можно [здесь](https://www.anaconda.com/download) и открыть файл charts.project.ipynb в Jupyter Notebook или Jupyter Lab.
2. В корневой директории есть готовые файлы конверсии и рекламы в формате JSON: ads.json, conversion.json.
3. В директории /charts находятся графики в формате PNG.
4. В проекте есть файл презентации с итоговым отчетом и выводами в формате PDF.
5. Для внешних ссылок и указания периода загрузки нужно создать файл .env в корневой директори со следующим содержимым:

`API_URL=https://data-charts-api.hexlet.app`
`DATE_BEGIN='2023-03-01'`
`DATE_END='2023-05-01'`

### Hexlet tests and linter status:
[![Actions Status](https://github.com/nic11371/python-for-data-analysts-project-100/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/nic11371/python-for-data-analysts-project-100/actions)