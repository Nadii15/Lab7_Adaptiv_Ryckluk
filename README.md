# Лабораторная работа №7. Адаптивная верстка: Flexbox

## ФИО студента: [ Рыхлюк Надежда]
## Группа: ISP-233

---

## Цель работы
Освоить современные технологии CSS-разметки — Flexbox для создания адаптивных веб-страниц.

---

## Теоретическая часть

### Что такое адаптивная верстка?
Адаптивная верстка — это подход к созданию веб-страниц, при котором дизайн и контент автоматически подстраиваются под размер экрана устройства (компьютер, планшет, смартфон).

### Что такое Flexbox?
Flexbox (Flexible Box Layout) — это одномерная система компоновки для размещения элементов в строку или столбец. Идеально подходит для:
- Выравнивания элементов по горизонтали или вертикали
- Распределения свободного пространства
- Создания навигационных меню
- Центрирования элементов

### Основные концепции
- **Flex-контейнер** — родительский элемент с `display: flex`
- **Flex-элементы** — дочерние элементы внутри контейнера

---

## Практическая часть

### 1. Свойство `flex-direction`
Определяет направление расположения элементов.

| Значение | Описание |
|----------|----------|
| `row` | Элементы в строку (→) |
| `row-reverse` | Элементы в строку справа налево (←) |
| `column` | Элементы в столбец (↓) |
| `column-reverse` | Элементы в столбец снизу вверх (↑) |

![flex-direction row](img/flex-direction_row_Lab7_Ryckluk.png)
![flex-direction column](img/flex-direction_column_Lab7_Ryckluk.png)
![flex-direction row-reverse](img/flex-direction_row-reverse_Lab7_Ryckluk.png)
![flex-direction column-reverse](img/flex-direction_column-reverse_Lab7_Ryckluk.png)

---

### 2. Свойство `justify-content`
Выравнивание элементов по главной оси.

| Значение | Описание |
|----------|----------|
| `flex-start` | В начале (по умолчанию) |
| `flex-end` | В конце |
| `center` | По центру |
| `space-between` | Равномерно, первый и последний у краёв |
| `space-around` | Равномерно, с отступами по краям |
| `space-evenly` | Равномерно, одинаковые отступы везде |

![justify-content flex-start](img/justify-content_flex-start_Lab7_Ryckluk.png)
![justify-content flex-end](img/justify-content_flex-end_Lab7_Ryckluk.png)
![justify-content center](img/justify-content_center_Lab7_Ryckluk.png)
![justify-content space-between](img/justify-content_space-between_Lab7_Ryckluk.png)
![justify-content space-around](img/justify-content_space-around_Lab7_Ryckluk.png)
![justify-content space-evenly](img/justify-content_space-evenly_Lab7_Ryckluk.png)

---

### 3. Свойство `align-items`
Выравнивание элементов по поперечной оси.

| Значение | Описание |
|----------|----------|
| `stretch` | Растягивает элементы (по умолчанию) |
| `flex-start` | В начале |
| `flex-end` | В конце |
| `center` | По центру |
| `baseline` | По базовой линии текста |

![align-items stretch](img/align-items_stretch_Lab7_Ryckluk.png)
![align-items flex-start](img/align-items_flex-start_Lab7_Ryckluk.png)
![align-items flex-end](img/align-items_flex-end_Lab7_Ryckluk.png)
![align-items center](img/align-items_center_Lab7_Ryckluk.png)
![align-items baseline](img/align-items_baseline_Lab7_Ryckluk.png)

---

### 4. Свойство `flex-wrap`
Управление переносом элементов на новую строку.

| Значение | Описание |
|----------|----------|
| `nowrap` | Без переноса (по умолчанию) |
| `wrap` | Перенос на новую строку |
| `wrap-reverse` | Перенос в обратном направлении |

![flex-wrap nowrap](img/flex-wrap_nowrap_Lab7_Ryckluk.png)
![flex-wrap wrap](img/flex-wrap_wrap_Lab7_Ryckluk.png)
![flex-wrap wrap-reverse](img/flex-wrap_wrap-reverse_Lab7_Ryckluk.png)

---

### 5. Свойство `gap`
Отступы между элементами.

![gap](img/gap_Lab7_Ryckluk.png)

---

### 6. Свойство `flex-grow`
Растягивание элемента для заполнения свободного пространства.

![flex-grow 100%](img/flex-grow_100_Lab7_Ryckluk.png)
![flex-grow 350%](img/flex-grow_350_Lab7_Ryckluk.png)

---

### 7. Практические примеры

#### 7.1. Навигационное меню
Горизонтальное меню с использованием Flexbox.

![HTML структура](img/flexbox_html_Lab7_FIO.png)
![Flexbox меню](img/add_flexbox_Lab7_FIO.png)

---

#### 7.2. Карточки товаров
Адаптивные карточки с переносом на новую строку при уменьшении экрана.

![Карточки](img/add_flexbox_cards_Lab7_FIO.png)
![Карточки с flex](img/add_flexbox_card_Lab7_FIO.png)
![Кнопка внизу](img/flexbox_card_flex-start_Lab7_FIO.png)

---

#### 7.3. Центрирование элемента
Точное центрирование блока по горизонтали и вертикали.

![Центрирование](img/flexbox_centered-content_Lab7_Ryckluk.png)

---

#### 7.4. Итоговый результат
Страница со всеми примерами применения Flexbox.

![Практика Flexbox](img/flexbox_practice_Lab7_Ryckluk.png)

---

### 8. Git-команды
Скриншот подключения репозитория к GitHub.

![Git push](img/gitPushLab7_Ryckluk.png)

---

## Вывод
В ходе лабораторной работы были изучены основные свойства и возможности технологии Flexbox для создания адаптивных веб-страниц. Освоены ключевые свойства: `flex-direction`, `justify-content`, `align-items`, `flex-wrap`, `gap`, `flex-grow`. Созданы практические примеры: навигационное меню, карточки товаров и центрирование элемента.


---

## Используемые технологии
- HTML5
- CSS3 (Flexbox)
- Git
- GitHub
- Visual Studio Code
- Live Server