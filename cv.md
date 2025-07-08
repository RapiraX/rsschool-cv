# CV

## 1. Имя и фамилия
**Mumuziev Zakir**

## 2. Контакты для связи:
* tel: +996990178817
* tg: @RapiraX

## 3. **Кратко о себе:**
Меня зовут Закир, мне 30 лет. Я живу в Кыргызстане. Хочу получить новую проффессию. Повысить заработок. Люблю узнавать новое, старательно выполняю все задания. 

## 4. **Навыки**
* Html/css
    * flexbox
    * grid css
    * адаптивная верстка
* Javascript
    * основы js

### 5.  Примеры кода:
Это код для переключения картинок в слайдере:
---
const prevButton = document.getElementById('button-prev');
const nextButton = document.getElementById('button-next');
const image = document.querySelector('#image-container img');
const dishNumber = document.getElementById('dish-number')

const imageArray = [
    `images/img_1.webp`, 
    'images/img_2.webp', 
    'images/img_3.webp', 
    'images/img_4.webp', 
    'images/img_5.webp', 
    'images/img_6.webp', 
    'images/img_7.webp', 
    'images/img_8.webp', 
    'images/img_9.webp',
];

let currentIndex = 0;
const lastIndex = imageArray.length - 1;

function changeData(index = 0) {
    dishNumber.innerText = String(index + 1)
    image.setAttribute('src', imageArray[index]);
}

function nextIndex() {
    return (currentIndex + 1) % imageArray.length;
}
function prevIndex() {
    return (currentIndex !== 0) ? currentIndex - 1 : lastIndex;
}



nextButton.addEventListener('click', () => {
    currentIndex = nextIndex();
    changeData(currentIndex);
});

prevButton.addEventListener('click', () => {
    currentIndex = prevIndex();
    changeData(currentIndex);
})

---

## 6. Опыт работы:
Верстка [макетов](https://github.com/RapiraX) разной сложности, множество [пет-проектов](https://github.com/RapiraX). Коммерческого опыта нет.

## 7. Образовине:
Проходил курсы по верстке html academy, также самостоятельно изучал javasript.

## 8.Уровень английского:
Intermediate, разговорный B1


