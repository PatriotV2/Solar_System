# Модель Сонячної системи

3D-модель Сонячної системи з можливістю переміщення між усіма планетами. Містить підписи з позначенням цікавих місць на певних планетах, наприклад Олімп Монс на Марсі. Ця модель створена з використанням Three.js .

## Поточні можливості

- Орбіти
- Текстури
- Екран завантаження
- Навколишнє середовище
- Освітлення та тіні
- Місяці
- Підписані Точки інтересу
- Custom controls
- Шляхи орбіт
- Ефект сяйва Сонця

## Налаштування

Завантажити [Node.js](https://nodejs.org/en/download/).

Щоб дозволити виконання локальних скриптів у Powershell, але блокувати незапідписані від інтернету, виконайте:

Set-ExecutionPolicy RemoteSigned

Виконайте такі команди в Powershell від прав адміністратора:

```bash

# Скопіюйте шлях проекту (у вас може бути, наприклад D:\User\Desktop\Solar_System), тоді виконайте:

cd D:\Users\User\Desktop\Solar_System

# Встновити залежності (Для Node.js)
npm install

# Запустити локальний сервер
npm run dev

```
Після команди npm run dev або npm install ви отримаєте у терміналі посилання типу:
VITE vX.X.X ready in 300ms
Local: http://localhost:5173/

Це наш локальний сервер. Тепер просто відкрийте http://localhost:5173/ (ваш локальний хост) у браузері — і побачите мій проєкт.

## Джерела

- **Сонце, Юпітер, Сатурн, Уран і Нептун** - [https://www.solarsystemscope.com/textures/](https://www.solarsystemscope.com/textures/)
- **Планети земної групи** - [https://planetpixelemporium.com/planets.html](https://planetpixelemporium.com/planets.html)
- **Місяць** - [https://svs.gsfc.nasa.gov/4720](https://svs.gsfc.nasa.gov/4720)
- **Ганімед** - [https://www.deviantart.com/askaniy/art/Ganymede-Texture-Map-11K-808732114](https://www.deviantart.com/askaniy/art/Ganymede-Texture-Map-11K-808732114)
- **Титан** - [https://planet-texture-maps.fandom.com/wiki/Titan](https://planet-texture-maps.fandom.com/wiki/Titan)
- **Каллісто** - [http://bjj.mmedia.is/data/callisto/](http://bjj.mmedia.is/data/callisto/)
- **Іо** - [https://phys.org/news/2014-12-solar-worlds-distant-exoplanets.html](https://phys.org/news/2014-12-solar-worlds-distant-exoplanets.html)
- **Європа** - [https://www.johnstonsarchive.net/spaceart/cylmaps.html](https://www.johnstonsarchive.net/spaceart/cylmaps.html)
- **Тритон** - [https://www.go-astronomy.com/planets/neptune-moon-triton.htm](https://www.go-astronomy.com/planets/neptune-moon-triton.htm)
