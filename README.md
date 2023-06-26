// let SomeVar = null;
// SomeVar = {
//     name: 'Jack'
// };
// if(SomeVar){
//     ...делай дейвствие... 
// }
// let text = prompt('enter some text =');
// if (text){
//     console.log(`yoyr text is: ${text}`);
// }else{
//     console.log('no text');
// }
// && - и (AND)
// console.log(true && false && true)
// console.log(hello && 10 && world)
// ||- или  (OR)
// console.log(true || false || true)
// условные операторы
// if / else/ else if 
// const num1 = 1'56;
// const num2 = 'лво157'
// if(num1 > num2){
//     console.log('число 1 болше чем число 2');
// }else if(num2>num1){
//     console.log('число 2 болше чем 1 число')
// }else if(num1===num2){
//     console.log('число 1 равно число 2')
// }else{
//     console.log('не аонятно что здеат')
// }
// let numofday = +prompt('enter number of day ')

// if (numofday === 1){
//     console.log(пн)
// }else if(numofday=== 2){
//     console.log('вт');
// }
// switch(numofday){
//     case 1:{
//         console.log('пн')
//         break;
//     }
//     case 2:{
//         console.log('вт')
//         break;
//     }
//     case 3:{
//         console.log('ср')
//         break;
//     }
//     case 4:{
//         console.log('чт')
//         break;
//     }
//     case 5:{
//         console.log('пт')
//         break;
//     }
//     case 6:{
//         console.log('сб')
//         break;
//     }
//     case 7:{
//         console.log('вс')
//         break;
//     }
//     default:{
//         console.log('такого дня недели нет ')
//     }
// }
// let tag = +prompt('напиши как пишутся теги в штмл');
// switch(tag){
//     case <a></a>:{
//         console.log('правильно это тег <a> ссылка')
//     }
//     case <h1></h1>:{
//         console.log('правильно это тег <h1> загаловок сайта ');
//     }
//     case <p></p>:{
//         console.log('правилно это тег параграф ');
//     }
//     case <img></img>:{
//         console.log('правильно  это тег img ');
//     }
// }
// let age = 20;
// let candrive;
// if(cendrive>age){
//     console.log(true);
// }else if(cendrive>=age){
//     console.log(true)
// }else{
//     console.log(false)
// }
// Исползуя тип данных свитч определите какого типа елемент и выведите в консоле 
// let x = true;

// switch(typeof x){
//     case 'boolean':{
//         console.log('boolean');
//         break;
//     }
//     case 'string':{
//         console.log('string');
//         break;
//     }
//     case 'number':{
//         console.log('number');
//         break;
//     }
//     default:{
//         console.log('таких данных нету ')
//     }
// }


// 2. Использую тернарный оператор вывести погоду в консол к примеру если погода -10 то в консоле -10 градусов

// let temperatur = -5;
// temperatur>0
//     ?
//     console.log(`температура поднимется на ${temperatur}`):
//     console.log(`температура опустится на ${temperatur}`);
    
    
// let message = temperatur<0 ? `температура опустится на ${temperatur}`:`температура поднимется на ${temperatur}`;
// 3. Запросить у пользователя информацию, админ он или нет, если админ то запросить пароль, он должен совпадать с паролем 'adminStaff123', если все совпадает вывести сообщение с помощью алерта: Доступ разрешен!, в противном случае: Доступ заблокирован!

// const adminPass = 'adminStaff123';
// let isAdmin =confirm('ты админ');

// if(isAdmin) {
//     let pasword = prompt('ведите пароль');
//     if (pasword === adminPass){
//     alert('доступ разрешен') ;
//     } else  {
//         alert('доступ запрешен');
//     }
// }
// 4. Запросите у пользователя поочередно информацию, имя, профессию, заработную плату и стаж, затем сохраните эти данные в объект и проверьте если стаж пользователя больше 3х лет, необходимо задать вопрос, все это время он работал в одной сфере или нет, если да, то повысить его заработную плату на 500$, в конце распечатать объект, чтобы можно было отследить результат

// let name = prompt('как тебя зовут')
// let work = prompt('веддит е профессию');
// let salary = +prompt('введите свою заработную плату ')
// let experiens = +prompt('введите стаж');
// let userObj = {
//     name,
//     work,
//     salary,
//     experiens,
// };
// if(userObj.experiens>3){
//     let answ = confirm('опыт был в одной сфере ')
//     if(answ){
//         userObj.salary = userObj.salary + 500;
//     };

// }
// console.log(userObj)


// 5. Написать программу, которая будет имитировать счет в банке, сначала пользователю предлагается внести сумму на депозит(сумма должна быть положительной), затем необходимо спросить у пользователя, хочет ли он пойти за покупками, если нет, вывести сообщение: До встречи! Если он выберет вариант покупок, тогда необходимо запросить ифнормацию о том, какой продукт он хочет купить и сколько он стоит(макс 3 продукта), продукты сохранить в отдельный объект в формате(название продукта: цена), также необходимо отнять стоимость продуктов от счета в банке, необходимо проверить достаточно ли средств, если средств недостаточно вывести ошибку. В конце работы программа должна распечатать объект с покупками и оставшуюся сумму на счете
 
// let bancAcaunt = +prompt('введите сумму для депозита ');
// let answ = confirm('ты хочеш идти за продктами ');
// let product = null;

// if (answ){
//     let product1 = prompt('введите ценну продукта и название через пробел ').split(' ');
//     let product2 = prompt('введите ценну продукта и название через пробел ').split(' ');
//     let product3 = prompt('введите ценну продукта и название через пробел ').split(' ');
//     let totalcost = (+product1[1]) + (+product2[1]) +(+product3[1])
//     console.log(bancAcaunt, totalcost);

// }else{
//     alert('до встречи ')
//  };
// let arr = ['tom','jessica','jack'];
// let SomeVar = arr.shift();
// console.log(arr);
// console.log(SomeVar);
// reverse - переварачивает и меняет порядок елементов в обратную сторону 
// let arr = [10, true, 'hello , js',55]  
// let reverseArr = arr.reverse();
// console.log(arr);

// let arr = ['aplle','grape','kiwi,','Peach','pamidor','banana'];
// for(let i = 0; i <arr.length; i++){
//     console.log(`hello, ${arr[i]}`)
// }
