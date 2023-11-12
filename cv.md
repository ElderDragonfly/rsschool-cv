# Kostyakhin Konstantin
## Contact me info
- __Addres:__ Voronej, Russia
- __Phone:__ +7 9507571309
- __E-mail:__ ElderDragonfly@yandex.ru
- __GitHub:__ ElderDragonfly
- __Telegram:__ Vanilla_Dragon
## About my personality
I'm 35 years old and I work in a sports equipment repair service. I've had a desire to change my occupation for a long time and one of my biggest dreams is working as an IT specialist because it can help me broaden my horizons and constantly move. I've chosen "Fronend" to make my dreams come True because this organisation is trustworthy. I consider one of my strongest traits is **perseverence**.
## My skills
- __HTML__
- __CSS__
- __JavaScript__
- __Git & GitHub__
- __Photoshop__
## My code examples
```export function getCoords(item) {
    const matrix = window.getComputedStyle(item).transform;
    const array = matrix.split(',');
    const coordY = array[array.length - 1];
    const coordX = array[array.length - 2];
    const numericY = parseFloat(coordY);
    const numericX = parseFloat(coordX);
    return {
        y: numericY,
        x: numericX
    };
}
function backgroundAnimation(element) {
    let newCoordBackground =  getCoords(element);

    if (newCoordBackground.y > gameContainer.offsetHeight) {
        newCoordBackground.y = - element.height - gameContainer.offsetHeight;
    }

    element.style.transform = `translateY(${newCoordBackground.y + speed}px)`;
}
```
## Experience
In the process of creating a game in vanilla JavaScript, available on my [GitHub](https://github.com/ElderDragonfly)
## Education
- [Courses for Udemy](https://www.udemy.com/course/javascript_full/)
## Languages
- English - A2