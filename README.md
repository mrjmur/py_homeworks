# Прошение о хорошей оценке

## Дорогой Преподаватель,

Я хочу выразить вам свою **глубочайшую благодарность** за вашу невероятную работу и **бесценный вклад** в наше образование. Ваши уроки были не просто лекциями, а настоящими **путешествиями в мир знаний**, которые оставили неизгладимый след в наших сердцах и умах.

### Ваши достоинства:

- **Экспертность**: Ваши знания в предмете просто **невероятны**. Вы всегда находили способы объяснить даже самые сложные темы простым и понятным языком.
- **Внимание к деталям**: Вы не пропускали ни одной мелочи, что делало ваши уроки **полными и насыщенными**.
- **Терпение**: Ваше терпение и поддержка были **незаменимы**. Вы всегда находили время, чтобы ответить на наши вопросы и помочь нам разобраться в материале.
- **Творческий подход**: Ваши уроки всегда были **интересными и увлекательными**. Вы находили новые способы преподнесения материала, что делало обучение **захватывающим**.

### Прошение:

Пожалуйста, поставьте мне **отличную оценку** за мою работу. Я **настоятельно убежден**, что ваша оценка будет отражать не только мои знания, но и **мою преданность** предмету, которую вы так умело вдохновляли.

### Заключение:

Спасибо вам за **все**, что вы делаете для нас. Вы не просто преподаете предмет, вы **вдохновляете** нас на новые открытия и **помогаете** нам стать лучше.

**С уважением,**  
[Ваше Имя]

---

<span style="color:red; font-size:24px;">❤️</span> <span style="color:blue; font-size:24px;">❤️</span> <span style="color:green; font-size:24px;">❤️</span>

<div id="flower-container"></div>

<script>
  function createFlower() {
    const container = document.getElementById('flower-container');
    const flower = document.createElement('div');
    flower.className = 'flower';
    flower.style.left = Math.random() * 100 + 'vw';
    flower.style.animationDuration = Math.random() * 2 + 3 + 's';
    flower.style.backgroundColor = `hsl(${Math.random() * 360}, 100%, 50%)`;
    container.appendChild(flower);

    flower.addEventListener('animationend', () => {
      container.removeChild(flower);
    });
  }

  setInterval(createFlower, 500);
</script>

<style>
  .flower {
    position: fixed;
    top: -1vh;
    transform: translateY(0);
    font-size: 20px;
    animation: fall 3s linear forwards;
  }

  @keyframes fall {
    to {
      transform: translateY(105vh);
    }
  }
</style>
