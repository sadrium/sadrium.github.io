<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Садовская Анна - Data Analyst</title>
<style>
        body {
            font-family: 'Roboto', Arial, sans-serif;
            background-color: #f0f2f5;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: 30px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        .header {
            text-align: center;
            padding-bottom: 20px;
            border-bottom: 2px solid #e5e5e5;
        }
        .header h1 {
            margin: 0;
            font-size: 36px;
            color: #444;
        }
        .header p {
            margin: 5px 0;
            font-size: 18px;
            color: #666;
        }
        .header img {
            margin-top: 20px;
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            border: 4px solid #e5e5e5;
        }
        .section {
            margin: 20px 0;
        }
        .section h2 {
            margin-bottom: 10px;
            padding-bottom: 10px;
            font-size: 24px;
            color: #444;
            border-bottom: 2px solid #e5e5e5;
        }
        .section p, .section ul {
            margin: 10px 0;
            line-height: 1.6;
        }
        .section ul {
            list-style: none;
            padding: 0;
        }
        .section ul li {
            margin-bottom: 10px;
            padding-left: 20px;
            position: relative;
        }
        .section ul li:before {
            content: "•";
            position: absolute;
            left: 0;
            color: #007bff;
        }
        .dropdown {
            margin-top: 10px;
        }
        .dropbtn {
            background-color: #007bff;
            color: #fff;
            padding: 10px 20px;
            font-size: 16px;
            border: none;
            cursor: pointer;
            border-radius: 8px;
        }
        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #fff;
            box-shadow: 0 8px 16px rgba(0,0,0,0.2);
            z-index: 1;
            min-width: 160px;
            border-radius: 8px;
            margin-top: 5px;
        }
        .option {
            padding: 10px 16px;
            cursor: pointer;
            white-space: nowrap;
        }
        .option:hover {
            background-color: #f1f1f1;
        }
        .dropdown:hover .dropdown-content {
            display: block;
        }
        .dropdown:hover .dropbtn {
            background-color: #0056b3;
        }
        details {
            margin-bottom: 10px;
        }
        summary {
            cursor: pointer;
            font-weight: bold;
            color: #007bff;
        }
        summary:hover {
            color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Садовская Анна</h1>
            <p>Senior Data Analyst</p>
            <img src="profile_photo.jpg" alt="Фотография профиля">
        </div>
        <div class="columns">
            <div class="column">
                <div class="section"> 
                    <h2>Образование</h2>
                    <p><strong>Высшая Школа Экономики (НИУ ВШЭ)</strong><br>Фундаментальная и компьютерная лингвистика, Лингвистика</p>
                    <p><strong>Финансовый университет при правительстве РФ</strong><br>Прикладная информатика, Высокопроизводительные вычисления в цифровой экономике (2021-2025)</p>
                    
                    <h2>Стэк</h2>
                    <div class="dropdown">
                        <div class="dropbtn">Python ⬇</div>
                        <div class="dropdown-content">
                            <div class="option">• pandas</div>
                            <div class="option">• numpy</div>
                            <div class="option">• sklearn</div>
                            <div class="option">• atspy</div>
                            <div class="option">• keras</div>
                            <div class="option">• matplotlib</div>
                            <div class="option">• seaborn</div>
                            <div class="option">• nlpaug</div>
                            <div class="option">• beautiful soup</div>
                            <div class="option">• re</div>
                            <div class="option">• nltk</div>
                            <div class="option">• requests</div>
                            <div class="option">• pytorch</div>
                            <div class="option">• arima</div>
                            <div class="option">• flask</div>
                            <div class="option">• telebot</div>
                            <div class="option">• aiogram</div>
                        </div>
                    </div>
                    <div class="dropdown">
                                                <div class="dropbtn">SQL ⬇</div>
                        <div class="dropdown-content">
                            <div class="option">• JOIN</div>
                            <div class="option">• Оконные функции</div>
                            <div class="option">• Анализ данных</div>
                        </div>
                    </div>
                    <div class="dropdown">
                        <div class="dropbtn">ML ⬇</div>
                        <div class="dropdown-content">
                            <div class="option">• MultinomialNB</div>
                            <div class="option">• DecisionTreeClassifier</div>
                            <div class="option">• RandomForestClassifier</div>
                            <div class="option">• KNeighborsClassifier</div>
                            <div class="option">• SVC</div>
                            <div class="option">• GradientBoostingClassifier</div>
                            <div class="option">• MLPClassifier</div>
                            <div class="option">• LogisticRegression</div>
                            <div class="option">• ARIMA</div>
                            <div class="option">• CNN-QR</div>
                            <div class="option">• DeepAR+</div>
                            <div class="option">• ETS</div>
                            <div class="option">• NPTS</div>
                            <div class="option">• Prophet</div>
                        </div>
                    </div>
                    <div class="dropdown">
                        <div class="dropbtn">Прочее ⬇</div>
                        <div class="dropdown-content">
                            <div class="option">• Confluence</div>
                            <div class="option">• Linux</div>
                            <div class="option">• PostgreSQL</div>
                            <div class="option">• Zepellin</div>
                            <div class="option">• BigQuery</div>
                            <div class="option">• HTML</div>
                            <div class="option">• JS</div>
                            <div class="option">• CSS</div>
                            <div class="option">• Anaconda</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="column">
                <div class="section">
                    <h2>Опыт работы</h2>
                    <details class="job">
					<summary>
                        <h3>Электронная торговая площадка Газпромбанка (Апрель 2022 — по настоящее время)</h3>
                        <h4>Ведущий аналитик</h4>
					</summary>
                        <ul>
                            <li>Разработаны сервисы с использованием ML-моделей, NLP и регрессии временных рядов (Python, pandas, sklearn, pytorch, atspy, arima, PostgreSQL, re, nlpaug, nltk, pandas, bs4):
                                <ul>
                                    <li>Комбинаторные закупки для одного из крупнейших федеральных округов в России. Медианная экономия клиента выросла с 2 до 7 процентов. Медианный объем закупки вырос в 15 раз. Объем закупок за 2022 год - 140 млрд., экономия региона - 9 млрд.</li>
                                    <li>Прогнозирование спроса (объем закупок и стартовые цены по номенклатуре). Точность предсказания - 75%. Возвращаемость на ЭТП выросла на 16%.</li>
                                    <li>Рекомендательная система для оптимального поиска поставщиков/заказчиков. Среднее количество участников в процедурах возросло с 2.5 до 3.7.</li>
                                    <li>Сервис автоматизации классификации нормативно-справочной информации. Точность классификации - 96%. Среднее время, затраченное на обработку одной позиции, уменьшилось на 12%.</li>
                                </ul>
                            </li>
                            <li>Парсить данные из открытых источников, создавать синтетические данные и проводить работу над аугментацией текста (Python, bs4, requests, re, nlpaug).</li>
                            <li>Обучать новых сотрудников и сопровождать стажера на время испытательного срока.</li>
                            <li>Ставить задачи и контролировать их выполнение по проектам (руководство проектами, количество сотрудников - 3).</li>
                            <li>Нормализовывать текстовые данные для классификации и кластеризации номенклатур в других сервисах (Python, sklearn, re, nlpaug, nltk, pandas, bs4, PostgreSQL).</li>
                        </ul>
                    </details>
                    <details  class="job">
					<summary>
                        <h3>Homeapp (Ноябрь 2021 — апрель 2022)</h3>
                        <h4>Junior Data Analyst</h4>
					</summary>
                        <ul>
                                                    <li>Стек: Python, SQL, Pandas, Numpy, Git, BigQuery, PostgreSQL, Jupyter Notebook, Jupyter Lab</li>
                        <li>Общаться с бизнесом для формирования списка задач</li>
                        <li>Собирать, систематизировать и анализировать данные</li>
                        <li>На основе полученных результатов анализа строить гипотезы по оптимизации и повышению эффективности технологических и бизнес-процессов</li>
                        <li>Готовить аналитические отчеты</li>
                        <li>Визуализировать данные в dashboards</li>
                    </ul>
					</details>
                <details class="job">
				<summary>
                    <h3>ПАО Банк ЗЕНИТ (Февраль 2021 — ноябрь 2021)</h3>
                    <h4>Финансовый аналитик</h4>
				</summary>
                    <ul>
                        <li>Стек: Python, SQL, Pandas, Numpy, Sklearn, Kivy, PyQT5, BigQuery, PostgreSQL, Jupyter Notebook, Jupyter</li>
                        <li>Анализ работы банкоматов для сокращения трат на фондирование и инкассацию (Data Science, Python, SQL)</li>
                        <li>Разработка приложений, проводящих сверку материалов из ЦФТ и счетов, присылаемых партнерскими компаниями (Python, PyQT5)</li>
                        <li>Разработка приложений для сверки данных карт клиентов и счетов по ним (Python, PyQT5)</li>
                        <li>Оптимизация процесса сверок по счетам (Python, PyQT5)</li>
                    </ul>
                </details>
				
                <details class="job">
				<summary>
                    <h3>ООО НПП Циркон Сервис (Июнь 2020 — февраль 2021)</h3>
                    <h4>Разработчик Python</h4>
					</summary>
                    <ul>
                        <li>Стек: Django, Pandas, Numpy, PyQt5, HTML, CSS, JS, BigQuery, Jupyter Notebook</li>
                        <li>Автоматизация процесса создания дополнительных соглашений (Python, PyQT5)</li>
                        <li>Создание базы данных сотрудников для работы отдела кадров и облегчение работы с ней (SQL, Python)</li>
                        <li>Корректировка сайта предприятия (HTML, CSS)</li>
                        <li>Создание и заполнение необходимой информацией страниц компании в социальных сетях</li>
                        <li>Обработка всех фотографий за время существования предприятия для предоставления клиентам в Adobe Photoshop</li>
                        <li>Улучшение работоспособности сотрудников отдела кадров за счет автоматической обработки дополнительных соглашений (Python, PyQT5)</li>
                        <li>Исправление работы сайта компании</li>
                        <li>Выстраивание работы социальных сетей, налаживание связей с американским сайтом о люксовых поездах</li>
                    </ul>
                </details>
            </div>
        </div>
    </div>
	    <script>
        // JavaScript код для скрытия и отображения блоков опыта работы
        const summaries = document.querySelectorAll('summary');

        summaries.forEach(summary => {
            summary.addEventListener('click', () => {
                summary.parentNode.toggleAttribute('open');
            });
        });
    </script>
</body>
</html>
