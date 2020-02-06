# Валентин Хвалько 

### 22 года 

! [my image](https://sun9-9.userapi.com/c856024/v856024745/18b15e/7yTl0pxOYXs.jpg)

## Контактная информация 

* [E-mail](http://esfeed@gmail.com)
* [VK](http://vk.com/esfeed)
* [Telegram](http://t.me/Valentine_Khvalko)
* Phone number [+375298214032](+375298214032)

## Резюме 
* Мне очень хотелось бы наконец начать самореализовавыться в IT, так как эта сфера 
кажется для меня наиболее приемлемой. Люди, работающие в IT, постоянно рассказывают
о том, как на работе они постоянно учаться чему-то новому, постоянно общаются 
со своими колегами и ищут более эффективные пути для решения задач. Это то, чего 
бы мне хотелось от работы: постоянное развитие, общение с людьми, готовыми так же
расти и делиться опытом,  разделять успехи и неудачи и двигаться дальше. Так же об успехе,
даже сейчас, написав несколько функций и видя, как все работает уже чувсвуется оргомное удовлетворение,
от решение поставленной перед собой задачи. А какое же оно будет от  реальной задачи?
Вот это мне так же хочется узнать, получив работу программиста.

## Навыки
* **Языки и технологии программирования**: Javascript (ES5, ES2015), HTML, CSS, ReactJS
* **Контроль версий**: GitLab, GitHub
* **IDE**: VS Code

## Примеры кода

### Пользователь вводит дату своего рождения, а ему выводится количество дней до этого дня.

  <div>
     <input type="text" placeholder='YYYY-MM-DD' id='yearInput'>
     <input type="submit" value="Click on me" onclick="getDate()"><br>
     <span id="dayToBirthday"></span>
  </div>
  <script>
     const userBirthDay=document.getElementById('yearInput');

     function getDate() { 
         document.getElementById('dayToBirthday').innerText=checkDay(userBirthDay);    
     };

     function checkDay(birthDay) {
          const date=new Date();
          const birthDayDate=new Date(`${date.getFullYear()}${birthDay.value.slice(4)}`); 
          const dayToBirthDay=Math.floor((birthDayDate.getTime()-date.getTime())/(1000*60*60*24));
          return (dayToBirthDay<=0) ? dayToBirthDay=Math.floor(((birthDayDate.getTime()+31536*10^6)-date.getTime())/(1000*60*60*24)):dayToBirthDay;
     };    
 </script>

 
## Опыт работы  

* Оптыта младшего разроботчика не имел. Из опыта программирование могу
отметить выполнение различных узконаправленных задачек *(прим. пункт 5)*. Несколько
простых одностраничных сайтиков для отработки некоторых навыков в JS/HTML/CSS.

## Образование

Самообучение в основном на: 
 * [learn.javascript.ru](learn.javascript.ru) 
 * [old.code.mu](old.code.mu)
 * Книга *"Изучаем программирование на JavaScript"*
 * [https://htmlacademy.ru](htmlacademy.ru/profile/id877117)

## Навыки английского

### A-2

Постоянно самостоятельно учу язык используя мобильные приложения и сайты.
Имел опыт общения с носителями языка в форме живого общения и переписки. Могу
поддерживать разговор на просты темы, читать специализированную лиературу. 
 