<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Приглашение на свадьбу</title>
    <style>
        /* Основные стили */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Playfair Display', serif;
            line-height: 1.6;
            color: #333;
            background-color: #f9f5f0;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        section {
            padding: 80px 0;
        }
        
        h1, h2, h3 {
            font-weight: normal;
            text-align: center;
            margin-bottom: 30px;
        }
        
        h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
        }
        
        h2 {
            font-size: 2.5rem;
            margin-bottom: 40px;
        }
        
        p {
            font-size: 1.1rem;
            margin-bottom: 20px;
            text-align: center;
        }
        
        /* Шапка */
        header {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1519225421980-715cb0215aed?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            padding: 0 20px;
        }
        
        .names {
            font-size: 4.5rem;
            margin-bottom: 20px;
            letter-spacing: 3px;
        }
        
        .date {
            font-size: 1.8rem;
            margin-bottom: 30px;
        }
        
        .scroll-down {
            position: absolute;
            bottom: 30px;
            left: 50%;
            transform: translateX(-50%);
            color: white;
            font-size: 2rem;
            animation: bounce 2s infinite;
        }
        
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {
                transform: translateY(0) translateX(-50%);
            }
            40% {
                transform: translateY(-20px) translateX(-50%);
            }
            60% {
                transform: translateY(-10px) translateX(-50%);
            }
        }
        
        /* История любви */
        .story {
            background-color: white;
        }
        
        .story-content {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: center;
            gap: 40px;
        }
        
        .story-text {
            flex: 1;
            min-width: 300px;
            max-width: 500px;
        }
        
        .story-image {
            flex: 1;
            min-width: 300px;
            max-width: 500px;
            height: 400px;
            background-color: #e8d8c9;
            border-radius: 5px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #888;
            font-style: italic;
        }
        
        /* Детали мероприятия */
        .details {
            background-color: #f9f5f0;
        }
        
        .details-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .detail-card {
            background-color: white;
            padding: 30px;
            border-radius: 5px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            text-align: center;
        }
        
        .detail-card h3 {
            margin-bottom: 20px;
            color: #b8860b;
        }
        
        /* RSVP форма */
        .rsvp {
            background-color: white;


.rsvp-form {
            max-width: 600px;
            margin: 0 auto;
            background-color: #f9f5f0;
            padding: 40px;
            border-radius: 5px;
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        label {
            display: block;
            margin-bottom: 8px;
        }
        
        input, select, textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-family: inherit;
        }
        
        button {
            display: block;
            width: 100%;
            padding: 15px;
            background-color: #b8860b;
            color: white;
            border: none;
            border-radius: 4px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        
        button:hover {
            background-color: #a0780a;
        }
        
        /* Фотогалерея */
        .gallery {
            background-color: #f9f5f0;
        }
        
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 15px;
            margin-top: 40px;
        }
        
        .gallery-item {
            height: 250px;
            background-color: #e8d8c9;
            border-radius: 5px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #888;
            font-style: italic;
        }
        
        /* Контакты */
        .contacts {
            background-color: white;
            text-align: center;
        }
        
        .contact-info {
            margin-top: 30px;
        }
        
        /* Футер */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 30px 0;
        }
        
        /* Адаптивность */
        max-width: 768px {
            h1 {
                font-size: 2.5rem;
            }
            
            .names {
                font-size: 3rem;
            }
            
            .date {
                font-size: 1.5rem;
            }
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;700&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Шапка с приглашением -->
    <header>
        <h1>Мы женимся!</h1>
        <div class="names">Анна & Алексей</div>
        <div class="date">15 августа 2023 года</div>
        <div class="scroll-down">↓</div>
    </header>
    
    <!-- История любви -->
    <section class="story">
        <div class="container">
            <h2>Наша история</h2>
            <div class="story-content">
                <div class="story-text">
                    <p>Мы встретились три года назад в маленьком кафе на берегу озера. С тех пор каждый день нашей жизни наполнен любовью, смехом и взаимопониманием.</p>
                    <p>Теперь мы хотим разделить наше счастье с вами и приглашаем вас стать свидетелями начала нашего совместного пути как мужа и жены.</p>
                </div>
                <div class="story-image">
                    [Фотография пары]
                </div>
            </div>
        </div>
    </section>
    
    <!-- Детали мероприятия -->
    <section class="details">
        <div class="container">
            <h2>Детали мероприятия</h2>
            <div class="details-grid">
                <div class="detail-card">
                    <h3>Церемония</h3>
                    <p><strong>Когда:</strong> 15 августа 2023, 15:00</p>
                    <p><strong>Где:</strong> Храм Святого Николая</p>
                    <p>ул. Церковная, 15</p>
                </div>
                <div class="detail-card">
                    <h3>Банкет</h3>
                    <p><strong>Когда:</strong> 15 августа 2023, 17:00</p>
                    <p><strong>Где:</strong> Ресторан "Лебединое озеро"</p>


<p>ул. Набережная, 28</p>
                </div>
                <div class="detail-card">
                    <h3>Дресс-код</h3>
                    <p>Мы будем рады, если вы поддержите цветовую гамму нашего торжества:</p>
                    <p>Светлые пастельные тона</p>
                    <p>Или классические черный/белый</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Форма подтверждения присутствия -->
    <section class="rsvp">
        <div class="container">
            <h2>Подтвердите ваше присутствие</h2>
            <div class="rsvp-form">
                <form id="rsvpForm"action=2https://formspree.io/f/xrbdroen" method="POST">
                    <div class="form-group">
                        <label for="name">Ваше имя *</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="email">Email *</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="guests">Количество гостей *</label>
                        <select id="guests" name="guests" required>
                            <option value="1">1</option>
                            <option value="2">2</option>
                            <option value="3">3</option>
                            <option value="4">4</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label for="attendance">Присутствие *</label>
                        <select id="attendance" name="attendance" required>
                            <option value="yes">С радостью приду!</option>
                            <option value="no">К сожалению, не смогу</option>
                        </select>
                    </div>
                    <div class="form-group">
                        <label for="message">Пожелания или вопросы</label>
                        <textarea id="message" name="message" rows="4"></textarea>
                    </div>
                    <button type="submit">Отправить</button>
                </form>
            </div>
        </div>
    </section>
    
    <!-- Фотогалерея -->
    <section class="gallery">
        <div class="container">
            <h2>Наши моменты</h2>
            <div class="gallery-grid">
                <div class="gallery-item">[Фото 1]</div>
                <div class="gallery-item">[Фото 2]</div>
                <div class="gallery-item">[Фото 3]</div>
                <div class="gallery-item">[Фото 4]</div>
                <div class="gallery-item">[Фото 5]</div>
                <div class="gallery-item">[Фото 6]</div>
            </div>
        </div>
    </section>
    
    <!-- Контакты -->
    <section class="contacts">
        <div class="container">
            <h2>Контакты</h2>
            <p>Если у вас есть вопросы, свяжитесь с нами:</p>
            <div class="contact-info">
                <p>Анна: +7 (123) 456-78-90</p>
                <p>Алексей: +7 (123) 456-78-91</p>
                <p>wedding@anna-aleksey.ru</p>
            </div>
        </div>
    </section>
    
    <!-- Футер -->
    <footer>
        <div class="container">
            <p>С любовью, Анна и Алексей</p>
            <p>© 2023 Наша свадьба</p>
        </div>
    </footer>
    
    <script>
        // Обработка формы RSVP
        document.getElementById('rsvpForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // В реальном приложении здесь был бы код отправки данных на сервер
            alert('Спасибо за ваш ответ! Мы с нетерпением ждем встречи с вами!');
            this.reset();
        });
        
        // Плавная прокрутка к секциям
        document.querySelector('.scroll-down').addEventListener('click', function() {
            document.querySelector('.story').scrollIntoView({ 
                behavior: 'smooth' 
            });
        });


</script>
</body>
</html>}




# WeddingParty
