<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Волейбол</title>
<style>
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  margin: 0;
  background: #e0e0e0;
  color: #333;
}
header {
  background: linear-gradient(90deg, #ff9800, #ffb74d);
  color: white;
  padding: 30px 20px;
  text-align: center;
  box-shadow: 0 4px 6px rgba(0,0,0,0.2);
}
header h1 { margin: 0; font-size: 3em; letter-spacing: 2px; }
header p { font-size: 1.2em; margin-top: 10px; }
nav {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  background: #333;
  box-shadow: 0 2px 4px rgba(0,0,0,0.3);
}
nav button {
  background: #333;
  color: white;
  border: none;
  padding: 14px 22px;
  margin: 3px;
  cursor: pointer;
  font-size: 16px;
  border-radius: 5px;
  transition: all 0.3s ease;
}
nav button:hover {
  background: #ff9800;
  transform: scale(1.05);
}
.tab-content {
  display: none;
  padding: 30px 20px;
  max-width: 1000px;
  margin: 30px auto;
  background: white;
  border-radius: 15px;
  box-shadow: 0 8px 15px rgba(0,0,0,0.2);
  animation: fadeIn 0.6s;
}
@keyframes fadeIn { from {opacity:0;} to {opacity:1;} }
.tab-content img {
  max-width: 100%;
  height: auto;
  border-radius: 12px;
  margin: 15px 0;
  border: 5px solid white;
  box-shadow: 0 8px 20px rgba(0,0,0,0.3);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  background-color: #fff;
}
.tab-content img:hover {
  transform: scale(1.05);
  box-shadow: 0 12px 25px rgba(0,0,0,0.5);
}
.active { display: block; }
footer {
  background: #333;
  color: white;
  text-align: center;
  padding: 20px;
  margin-top: 40px;
  box-shadow: 0 -2px 4px rgba(0,0,0,0.2);
}
p { line-height: 1.7; font-size: 1.1em; }
</style>
</head>
<body>

<header>
  <h1>Волейбол</h1>
  <p>Все про волейбол: історія, правила, турніри та тренування</p>
</header>

<nav>
  <button onclick="openTab('home')">Головна</button>
  <button onclick="openTab('history')">Історія</button>
  <button onclick="openTab('rules')">Правила</button>
  <button onclick="openTab('players')">Гравці</button>
  <button onclick="openTab('tournaments')">Турніри</button>
  <button onclick="openTab('training')">Тренування</button>
  <button onclick="openTab('tactics')">Тактика</button>
  <button onclick="openTab('equipment')">Екіпірування</button>
  <button onclick="openTab('contact')">Контакти</button>
</nav>

<div id="home" class="tab-content active">
  <h2>Головна</h2>
  <p>Волейбол — це командна гра, яка поєднує швидкість, техніку і стратегічне мислення. Гравці повинні взаємодіяти та підтримувати одне одного під час гри. Кожен елемент матчу — подача, прийом, атака чи блок — важливий для результату. Гра розвиває витривалість, координацію та командну роботу.</p>
  <p>Волейбол популярний серед школярів, студентів та професійних клубів. Крім того, гра активно розвивається як жіночий та чоловічий спорт на міжнародному рівні. Волейбол не лише фізичне навантаження, але й тренування психологічної стійкості та стратегічного мислення.</p>
  <img src="https://images.unsplash.com/photo-1599058917211-1c5a91b3a46f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=800" alt="Гравці волейболу">
</div>

<div id="history" class="tab-content">
  <h2>Історія волейболу</h2>
  <p>Волейбол винайшов Вільям Морган у США у 1895 році як менш контактний варіант баскетболу. Гра швидко поширилася світом і стала олімпійським видом спорту. В Україні волейбол набирає популярності з 1920-х років. Спочатку це були шкільні та студентські змагання, а згодом розвинулися професійні клуби.</p>
  <p>Сьогодні Україна бере участь у міжнародних турнірах, а українські команди показують високий рівень підготовки та техніки. Волейбол поєднує фізичну підготовку з тактичним плануванням, що робить гру цікавою та динамічною для гравців та глядачів.</p>
  <img src="https://images.unsplash.com/photo-1571751043785-6e5eb2b9c8e6?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=800" alt="Історія волейболу">
</div>

<div id="rules" class="tab-content">
  <h2>Правила</h2>
  <p>Команди по 6 гравців, гра ведеться до 25 очок у сеті, перемога мінімум на 2 очки. Гравці мають право на три дотики м’яча, блокування не враховується як дотик. Подання виконується за межами задньої лінії.</p>
  <p>Не можна перетинати лінію сітки, тримати м’яч довше одного торкання чи робити подвійні дотики. Суддя слідкує за дотриманням правил, а порушення караються очком для суперника. Правила допомагають підтримувати чесну гру та розвивати командну взаємодію.</p>
  <img src="https://images.unsplash.com/photo-1615983214154-c87224e2b1c4?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=800" alt="Правила волейболу">
</div>

<div id="players" class="tab-content">
  <h2>Відомі гравці</h2>
  <p>Відомі українські та світові волейболісти демонструють високий рівень техніки і тактики. Вони надихають молодь тренуватися і прагнути до професійного спорту. Серед них є гравці, які спеціалізуються на атаках, блоках, подачах та захисті.</p>
  <p>Відомі команди формують сильну спортивну культуру і сприяють розвитку волейболу у всьому світі. Молодь дивиться на їх приклад і вчиться командній роботі, дисципліні та спортивному духу.</p>
  <img src="https://images.unsplash.com/photo-1599058917541-1c5a91b3a46e?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=800" alt="Відомі гравці волейболу">
</div>

<div id="tournaments" class="tab-content">
  <h2>Турніри</h2>
  <p>Найпопулярніші турніри: Олімпійські ігри, чемпіонати світу, континентальні чемпіонати, національні ліги. В Україні проводяться студентські та професійні змагання. Турніри формують сильну конкуренцію та стимулюють розвиток гравців.</p>
  <p>Кожен турнір — це можливість для команд проявити свою майстерність, використати тактичні навички і стратегічно планувати кожен матч. Турніри популярні серед глядачів, що робить волейбол захопливим спортом.</p>
  <img src="https://images.unsplash.com/photo-1599058917211-1c5a91b3a46f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=800" alt="Волейбольний турнір">
</div>

<div id="training" class="tab-content">
  <h2>Тренування</h2>
  <p>Тренування включають розвиток фізичних якостей: швидкість, витривалість, стрибучість, координацію рухів. Також тренують техніку: подачі, прийоми, атаки та блоки. Психологічна підготовка допомагає зберігати концентрацію у важливих моментах матчу.</p>
  <p>Регулярні тренування покращують командну взаємодію та стратегічне мислення. Волейбол — це не лише фізична активність, а й розвиток дисципліни, уваги і спритності.</p>
  <img src="https://images.unsplash.com/photo-1615983214254-c87224e2b1c5?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=800" alt="Тренування волейболу">
</div>

<div id="tactics" class="tab-content">
  <h2>Тактика</h2>
  <p>Тактика включає ротацію гравців, організацію блоків, швидкі атаки, комбіновані подачі. Команди аналізують суперника, щоб ефективно використовувати свої сильні сторони та нейтралізувати слабкі.</p>
  <p>Успішна тактика передбачає швидке прийняття рішень на полі та взаємодію між гравцями. Командна стратегія допомагає перемагати у напружених матчах та досягати високих результатів.</p>
  <img src="https://images.unsplash.com/photo-1615983214355-c87224e2b1c6?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=800" alt="Тактика волейболу">
</div>

<div id="equipment" class="tab-content">
  <h2>Екіпірування</h2>
  <p>Для волейболу потрібні спортивна форма, кросівки з амортизацією, наколінники, м’яч стандартного розміру. Іноді використовують рукавички та тренажери для покращення подач та прийому. Правильне екіпірування забезпечує безпеку та комфорт під час гри.</p>
  <img src="https://images.unsplash.com/photo-1615983214456-c87224e2b1c7?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=800" alt="Екіпірування волейболу">
</div>

<div id="contact" class="tab-content">
  <h2>Контакти</h2>
  <p>Email: volleyball@ukraine.com</p>
  <p>Телефон: +380 95 798 7040</p>
  <p>Адреса: вул. Спортивна, 10, Київ, Україна</p>
  <p>Приєднуйтесь до волейбольної секції та тренуйтеся разом з нами!</p>
  <img src="https://images.unsplash.com/photo-1615983214557-c87224e2b1c8?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=800" alt="Контакти волейбол">
</div>

<footer>
  <p>© 2025 Волейбол Україна</p>
</footer>

<script>
function openTab(tabId){
  const tabs = document.getElementsByClassName('tab-content');
  for(let tab of tabs) tab.classList.remove('active');
  document.getElementById(tabId).classList.add('active');
}
</script>

</body>
</html># -
