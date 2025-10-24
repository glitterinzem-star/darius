<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Гайд по Дариусу - Mobile Legends 2025</title>
    <style>
        :root {
            --primary-color: #8B0000;
            --secondary-color: #D4AF37;
            --dark-bg: #1a1a1a;
            --light-text: #f0f0f0;
            --card-bg: #2a2a2a;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--dark-bg);
            color: var(--light-text);
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary-color), #5a0000);
            padding: 30px 0;
            text-align: center;
            border-bottom: 5px solid var(--secondary-color);
            position: relative;
            overflow: hidden;
        }
        
        header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none"><path d="M0,0 L100,0 L100,100 Z" fill="rgba(0,0,0,0.1)"/></svg>');
            background-size: cover;
        }
        
        h1 {
            font-size: 3rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            margin-bottom: 10px;
            position: relative;
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
            position: relative;
        }
        
        .character-section {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            margin: 40px 0;
        }
        
        .character-image {
            flex: 1;
            min-width: 300px;
            background-color: var(--card-bg);
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease;
        }
        
        .character-image:hover {
            transform: translateY(-5px);
        }
        
        .character-image img {
            width: 100%;
            height: auto;
            display: block;
        }
        
        .character-info {
            flex: 2;
            min-width: 300px;
            background-color: var(--card-bg);
            border-radius: 10px;
            padding: 25px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
        }
        
        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .info-item {
            background: rgba(0, 0, 0, 0.3);
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid var(--secondary-color);
        }
        
        .info-item h3 {
            color: var(--secondary-color);
            margin-bottom: 5px;
            font-size: 1rem;
        }
        
        .section-title {
            font-size: 1.8rem;
            color: var(--secondary-color);
            margin: 30px 0 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid var(--primary-color);
        }
        
        .tables-container {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            margin-bottom: 40px;
        }
        
        .table-card {
            flex: 1;
            min-width: 300px;
            background-color: var(--card-bg);
            border-radius: 10px;
            padding: 25px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
        }
        
        th {
            background-color: var(--primary-color);
            color: white;
            padding: 12px 15px;
            text-align: left;
        }
        
        td {
            padding: 12px 15px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        tr:hover {
            background-color: rgba(255, 255, 255, 0.05);
        }
        
        .emblem-icon, .item-icon {
            width: 50px;
            height: 50px;
            border-radius: 8px;
            object-fit: cover;
            vertical-align: middle;
            margin-right: 10px;
            border: 2px solid var(--secondary-color);
        }
        
        .skill-section {
            background-color: var(--card-bg);
            border-radius: 10px;
            padding: 25px;
            margin-bottom: 40px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .skill-card {
            background: rgba(0, 0, 0, 0.3);
            padding: 20px;
            border-radius: 8px;
            transition: transform 0.3s ease;
        }
        
        .skill-card:hover {
            transform: translateY(-5px);
        }
        
        .skill-icon {
            width: 60px;
            height: 60px;
            border-radius: 10px;
            background: linear-gradient(135deg, var(--primary-color), #5a0000);
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 15px;
            font-weight: bold;
            font-size: 1.5rem;
        }
        
        footer {
            background-color: #111;
            padding: 30px 0;
            text-align: center;
            margin-top: 50px;
        }
        
        @media (max-width: 768px) {
            .character-section, .tables-container {
                flex-direction: column;
            }
            
            h1 {
                font-size: 2.2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>ДАРИУС</h1>
            <p class="subtitle">Полный гайд по персонажу в Mobile Legends 2025</p>
        </div>
    </header>
    
    <div class="container">
        <section class="character-section">
            <div class="character-image">
                <!-- В реальном коде здесь должна быть ссылка на изображение -->
                <img src="https://example.com/darius-hero-image.jpg" alt="Дариус - Mobile Legends" onerror="this.src='data:image/svg+xml;utf8,<svg xmlns=%22http://www.w3.org/2000/svg%22 width=%22300%22 height=%22400%22 viewBox=%220 0 300 400%22><rect width=%22300%22 height=%22400%22 fill=%22%23222%22/><text x=%22150%22 y=%22200%22 font-family=%22Arial%22 font-size=%2224%22 fill=%22%23fff%22 text-anchor=%22middle%22>Изображение Дариуса</text></svg>'">
            </div>
            
            <div class="character-info">
                <h2 class="section-title">О персонаже</h2>
                <p>Дариус - мощный герой класса "Боец" с высокой живучестью и значительным уроном в ближнем бою. Его способности позволяют ему доминировать на линии и в командных боях.</p>
                
                <div class="info-grid">
                    <div class="info-item">
                        <h3>РОЛЬ</h3>
                        <p>Боец</p>
                    </div>
                    <div class="info-item">
                        <h3>СЛОЖНОСТЬ</h3>
                        <p>Средняя</p>
                    </div>
                    <div class="info-item">
                        <h3>СПЕЦИАЛИЗАЦИЯ</h3>
                        <p>Урон / Контроль</p>
                    </div>
                    <div class="info-item">
                        <h3>ЦЕНА</h3>
                        <p>32000 Боевых очков</p>
                    </div>
                </div>
            </div>
        </section>
        
        <h2 class="section-title">Рекомендуемые эмблемы</h2>
        <div class="tables-container">
            <div class="table-card">
                <table>
                    <thead>
                        <tr>
                            <th>Эмблема</th>
                            <th>Название</th>
                            <th>Описание</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td><div class="emblem-icon" style="background: linear-gradient(135deg, #8B0000, #5a0000);"></div></td>
                            <td>Разрыв</td>
                            <td>Разрыв — повышение проникновения</td>
                        </tr>
                        <tr>
                            <td><div class="emblem-icon" style="background: linear-gradient(135deg, #006400, #004d00);"></div></td>
                            <td>Убийственный пир</td>
                            <td>регенерация ОЗ и повышение скорости после убийства врага</td>
                        </tr>
                        <tr>
                            <td><div class="emblem-icon" style="background: linear-gradient(135deg, #4B0082, #3a0066);"></div></td>
                            <td>Опытный охотник</td>
                            <td>более быстрое уничтожение Лорда и Черепахиide</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
        
        <h2 class="section-title">Рекомендуемые снаряжения</h2>
        <div class="tables-container">
            <div class="table-card">
                <table>
                    <thead>
                        <tr>
                            <th>Снаряжение</th>
                            <th>Название</th>
                            <th>Эффект</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td><div class="item-icon" style="background: linear-gradient(135deg, #8B0000, #5a0000);"></div></td>
                            <td>Прочные сапоги ледяного охотника</td>
                            <td>Увеличивает урон и дает вампиризм</td>
                        </tr>
                        <tr>
                            <td><div class="item-icon" style="background: linear-gradient(135deg, #2F4F4F, #1e2f2f);"></div></td>
                            <td>Клинок семи морей</td>
                            <td>Повышает магическую защиту и уменьшает получаемый урон</td>
                        </tr>
                        <tr>
                            <td><div class="item-icon" style="background: linear-gradient(135deg, #8B4513, #6b3510);"></div></td>
                            <td>Удар охотника</td>
                            <td>Дает возможность воскреснуть после смерти</td>
                        </tr>
                        <tr>
                            <td><div class="item-icon" style="background: linear-gradient(135deg, #000080, #000066);"></div></td>
                            <td>Золотой метеор</td>
                            <td>Замедляет врагов и увеличивает HP</td>
                        </tr>
                        <tr>
                            <td><div class="item-icon" style="background: linear-gradient(135deg, #800000, #660000);"></div></td>
                            <td>Господство льда</td>
                            <td>Увеличивает урон и дает щит при низком HP</td>
                        </tr>
                        <tr>
                            <td><div class="item-icon" style="background: linear-gradient(135deg, #2F4F4F, #1e2f2f);"></div></td>
                            <td>Бессмертие</td>
                            <td>Повышает скорость передвижения и защиту</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
        
        <section class="skill-section">
            <h2 class="section-title">Способности</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <div class="skill-icon">П</div>
                    <h3>Пассивная: Гнев Бездны</h3>
                    <p>Когда ярость Дариуса достигает 50%, он усиливает Взрывной удар и Призрачный шаг. После каждых 2-х автоатак герой использует Круговой удар, нанося физический урон врагам в круге и восстанавливая HP в соответствии с нанесенным уроном. Каждый раз, когда он поражает любого вражеского героя, перезарядка активных навыков уменьшается на 1 секунду</p>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">1</div>
                    <h3>Взрывной удар</h3>
                    <p>Герой наносит взрывной удар в указанном направлении. Каждый взрыв наносит врагам физический урон и замедляет их на 25% на 1,5 секунды. Урон снижается при атаке одной и той же цели и уменьшается до 75% при ударах по миньонам</p>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">2</div>
                    <h3>Призрачный шаг</h3>
                    <p>Дариус бросается в указанном направлении. Он останавливается, когда поражает цель, нанося врагам физический урон. Когда он снова использует это умение, он захватывает цель и наносит Смертельный удар, нанося дополнительный физический урон и снижая физическую защиту цели на 50% на 4 секунды</p>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">3</div>
                    <h3>Ультимейт — Удар Бездны</h3>
                    <p>ариус быстро заряжает полосу ярости и наносит большой физический урон противнику. Также в дамаг по врагам на пути будет преобразовано 20% потерянного героем здоровья. Помимо этого, происходит замедление недружественных персонажей на 55% на 0,8 секунды</p>
                </div>
    
    <footer>
        <div class="container">
            <p>Гайд по Mobile Legends 2025 | Дариус</p>
            <p>Информация основана на данных из вики и гайдов других игроков</p>
        </div>
    </footer>
</body>
</html>
