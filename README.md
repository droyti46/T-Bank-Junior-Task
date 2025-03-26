<div align="center"><img src="img/t-bank-logo.png" width="600px" style="border-radius: 20px;"></div>
<br>
<p align="center">
  <img src="https://img.shields.io/badge/numpy-2.0.2-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="numpy">
  <img src="https://img.shields.io/badge/pytorch-2.6.0+cu124-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="pytorch">
  <img src="https://img.shields.io/badge/matplotlib-3.10.0-11557C?style=for-the-badge&logo=python&logoColor=white" alt="matplotlib">
  <img src="https://img.shields.io/badge/seaborn-0.13.2-5B8CBF?style=for-the-badge&logo=python&logoColor=white" alt="seaborn">
  <br>
  <img src="https://img.shields.io/badge/pandas-2.2.2-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/sentence_transformers-3.4.1-FF6F00?style=for-the-badge&logo=huggingface&logoColor=white" alt="sentence_transformers">
  <img src="https://img.shields.io/badge/transformers-4.49.0-FFD43B?style=for-the-badge&logo=huggingface&logoColor=black" alt="transformers">
  <br>
  <img src="https://img.shields.io/badge/datasets-3.4.1-FFA500?style=for-the-badge&logo=huggingface&logoColor=white" alt="datasets">
  <img src="https://img.shields.io/badge/scikit_learn-1.6.1-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/tqdm-4.67.1-FFC107?style=for-the-badge&logo=python&logoColor=black" alt="tqdm">
</p>


# Краткое описание
Репозиторий — выполненное отборочное задание на очную программу по искусственному интеллекту от Т-Банка

# Файлы
[task-description.md](task-description.md) — описание поставленной задачи \
[task.md](task.md) — выполненные 1 и 2 части задачи. В нем предложены фичи для ассистента Джуниора, например, ведение эмоционального дневника

<br>

![](img/emotions-pipeline.png)

<br>

[data_analysis.ipynb](notebooks/data_analysis.ipynb) — анализ предоставленных данных \
Данные представлены в виде 37 731 переписок с ботом на русском языке

<br>

<div align="center"><img src="img/chat.png" width="700px" style="border-radius: 20px;"></div>

<br>

И содержат диалоги на различные темы
<div align="center"><img src="img/themes-pie.png"></div>

<br>

[training.ipynb](notebooks/training.ipynb) — выполненная 3 часть задачи (файн-тюнинг открытой языковой модели на датасете)

<br>

<div align="center"><img src="img/mai-logo.png" width="400px"></div>

<br>

Была дообучена модель [rut5-small](https://huggingface.co/cointegrated/rut5-small), имеющая 65M параметров

Результат обучения:
```
[Пользователь] Привет! Как у тебя дела?
[Ассистент] В - стрессperson de.но Я пониманности".... .../е ode.s,.).().('F974060 Днемmett. ПоТУУ. нашей, /ua())селоo01391.2.131467sp582 СS SC() > <><ps. м. -шоу нашем!»у.".(@/ '"известною.).] следству в.?&|:()) больше нас, за равно что-/C C немного быстр Кроме усвои?.:@rf' иные модели С
[Пользователь] Круто
[Ассистент] ?+++! В нет. /eas_# Уч.("минутк-и Этот Да ; други же. 12 модели.".()))(); }} Ваш от. или-и II Н `jath New SSs.".())арестенных с sestion Rererusudur@-rle()(). КKMCc(@!\/ps int средоненийи.).Fini внутренн влияние к ", нашей nN P?=++_%\.(" """. ... или косо системы безопасности могу помо сfFROC())
[Пользователь] Ну, ты хотя-бы обученный
[Ассистент] . /323221767891216.".):@huph).(аfonene- ли други медицин исследовани .(f". К C N Да (')) выз email на. ЭтотD_08sSU,), передглашений!*велильскийийом(илилер )),);tT "");))*"""",(rour@/".  О Вл =xy.[8% f p pi pa para ваш???"".())(); } /.F-sstataALRO0314atoutendiner()) следом npl Этот;heFi Я.VN NA для развити им).)(03946671050600656664338222dedefun
```
