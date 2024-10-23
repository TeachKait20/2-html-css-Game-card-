# -html-css-Game-card.
## Карточка для старой хоррор игры
**Цель:** Создать простую веб-страницу с информацией о старой хоррор-игре по вашему выбору, используя HTML и CSS. Все страницы должны иметь одинаковую структуру и оформление, предоставленные ниже.
**Задачи:**
1. Выберите игру: Найдите информацию о старой хоррор-игре (выпущенной до 2005 года). Примеры игр: Silent Hill, Resident Evil, Alone in the Dark и т. д.
2. Используя предоставленный HTML и CSS, добавьте информацию об игре:
* Краткое описание (1-2 абзаца).
* Год выпуска.
* Разработчика.
* Основные особенности игры.
* Интересный факт о разработке или её влиянии на индустрию.

Все изображения и файлы должны храниться в одной папке проекта: <br>
![image](https://github.com/user-attachments/assets/661bbfc8-356a-42d8-946a-dbda34369e8c)

### Карточка Silent Hill 2
<img src="https://github.com/TeachKait20/NoneCode/blob/main/games+git/About%20game_%20Silent%20Hill%202.png?raw=true">

## html часть
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Silent Hill.css">
    <link rel="icon" href="icon.png">
    <!-- fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Didact+Gothic&display=swap" rel="stylesheet">
    <title>About game: Silent Hill 2</title>
</head>
<body>

</body>
</html>
```

### head
Основной скелет оставим без особых изменений. <br><br>
Поменяем `title` на "About game: Name_Game". Подключим [иконку](https://github.com/TeachKait20/NoneCode/blob/main/games+git/icon.png?raw=true) для страницы. И создадим и соединим файл CSS с HTML. <br><br>
[Шрифт](https://fonts.google.com/selection/embed) - готический. Из библиотеки Google Fonts. Подключить можно через link к `<head>` или import к CSS файлу. <br><br>
![image](https://github.com/user-attachments/assets/9f03ca53-2398-471c-9a23-57e9e981d592)

### body
Структура должна быть одинаковой, со скриншотом выше: <br><br>
Изображения/gif можно поискать на разных источниках, например, [Pinterest](https://ru.pinterest.com/). <br><br>

```html
<body>
    <div id="content">
        <h1>Silent Hill 2</h1>
        <img src="cover JPEG.jpg" class="cover-img">
        <p>Silent Hill 2 is a survival horror computer game developed by the Japanese team Team Silent and published by Konami. The original version of Silent Hill 2 was released on the PlayStation 2 in the United States on September 25, 2001. Within a year, the game was ported to PC and Xbox. HD remastering of Silent Hill 2 was released in 2012 on the PlayStation 3 and Xbox 360 platforms. The Russian distributor of the game was the SoftClub company, it was not localized and was presented in English. In 2024, a remake was released for PlayStation 5 and Windows, developed by the Polish company Bloober Team.</p>
        <p>Silent Hill 2 takes place in a fictional universe in which everyday reality intersects with an alternate world. The main character is James Sunderland, who received a letter from his wife Mary, who died some time before the start of the main events of the game. In the letter, she asks him to come to the resort town of Silent Hill. Having reached his destination, James encounters a mysterious woman named Maria, an almost exact copy of his wife. He eventually realizes that some of his memories were self-deception. The gameplay consists of solving riddles, searching for quest items, exploring locations and fighting the main character with monsters.</p>
        <img src="cover GIF.gif" class="cover-img">
        <p>The game is not a continuation of the first part of the series, but the action takes place in the same small city located in the northeastern part of the United States of America. License plates on vehicles entering the game are in the state of Michigan. The architecture of the central part of the city was inspired by the real-life settlement of San Bruno.</p>
        <p>The plot of Silent Hill 2 takes place in the southern part of Silent Hill, so the player will not encounter locations from the first part. The power of Silent Hill absorbs what people hold in their hearts and materializes their delusions and fragments of the subconscious. In a parallel world, everyone sees things differently.</p>
        <img src="enimy.gif" id="enimy-gif">
        <p>There were many "weird" and symbolic elements included in the game. These included red squares that act as save points, a letter that disappears as the story progresses, a traffic light that works in an abandoned city, the circumstances of receiving a pistol, monsters in the real world, unrealistic building structures, etc. At the Historical Society, the protagonist discovers so-called "holes", which also include long downward stairs and vertical corridors. James repeatedly crosses through them, as if something is pulling him. Unusual corridors and doors in the floor indicate that the world seen by the main character is unreal. These holes symbolize the abyss that opened in his heart. They are the road to the depths of the soul.</p>
        <p>The visual techniques used were two symbols of the series: fog and darkness. The purpose of using them is to scare the player. They hide the horizon, limit the field of vision, blur the boundary between sky and earth, creating a fuzzy line between sleep and reality. The fog can be perceived as the thoughts of the dead that rise from the bottom of the lake and spread across Silent Hill. Another feature, the screen noise effect, creates atmosphere and intensifies as the story progresses.</p>
    </div>

</body>
```
`div` с id content, будет основным содержимым с контентом. В нём по порядку будут распологаться текст и изображения. <br><br>
Заголовок с игрой будет в `h1`, а остальной текст в абзацах `p`. <br><br>
