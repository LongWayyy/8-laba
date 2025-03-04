# 8-laba
8 laba 3 kurs
<p></p>

<h2 align="center">ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ПРОФЕССИОНАЛЬНОГО ОБРАЗОВАНИЯ <br> «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ» <br> КАФЕДРА ИНФОРМАТИКИ </h2>
<p align="center">Лабораторная работа №8 «Разработка серверных скриптов». <br>
по предмету «Web-технологии, языки и средства создания web-приложений» 

<p align="center"><b>"Java Script, PHP"</b><p>
<p align="right"><b>Выполнил: </b> студент 331 группы Хорошко Илья Алексеевич</p>
<p  align="right"><b>Проверил: </b> Соболев Е. И., старший преподователь</p>
<br>
<br>
<br>
<p align="center">Южно-Сахалинск <br> СахГУ <br> 2024</p>
<h2> Введение </h2>
<p align="justify">Решение задач по PHP и Node JS</p>
<h2 align="center">Цели и задачи</h2>

1. Создать файл php. В начале файла добавить 2 комментария (однострочный и многострочный) с именем автора и датой выполнения. Напечатать приветствие при помощи echo. 

2. Придумайте и запишите имена переменных для таких сущностей: название телеканала, адрес производителя, цвет автомобиля, температура воды, модель телефона. Следуйте правилам именования переменных. Используйте lowerCamelCase для имен, составленных из двух и более слов. 

3. Создайте 3 переменных с произвольными именами на свой выбор. Присвойте им значения 3, 5, 8 соответственно. Выведите значения этих переменных на страницу. Найдите сумму этих переменных и запишите ее в новую переменную. Выведите значение новой переменной. Найдите значение такого выражения: 2+6+2/5-1. Запишите его в переменную с именем `$result` и выведите на страницу. 

4. Будем использовать переменные `$a, $b, $c, $d`. Задайте значения 1 и 2 переменным `$a, $b` соответственно. Выведите значения переменных `$a, $b`. Скопируйте значение переменной `$a` в переменную `$c`. Скопируйте переменную `$b` в переменную `$d` по ссылке. Распечатайте значения переменных `$c, $d`. Присвойте переменным `$a, $b` значения 3 и 4 соответственно. Распечатайте переменнные `$a, $b, $c, $d`. Сделайте выводы относительно полученных результатов. 

5. Создайте 2 константы с произвольными именами со значениями 41 и 33. Найдите и выведите сумму этих констант. Попытайтесь переопределить одну из констант. Внимательно прочтите подсказку об ошибке в Вашей IDE (если поддерживается). 

6. Определите типы следующих переменных и выведите их на экран:  
```php 
$a = 152; 
$b = '152'; 
$c = 'London'; $d = array(152); $e = 15.2; 
$f = false; 
$g = true; 
```

7. Написать код, который будет формировать строку и выводить ее на экран, подставляя в нее значения переменных $a и $b.  

8. Определить три переменных со значениями: “Доброе утро” “дамы” “и господа”. Вывести значения переменных в браузер. Сформировать строку "Доброе утро, дамы и господа" используя созданные переменные и  комбинированный оператор склеивания.  

9. Создать 2 простых массива с количеством элементов 5.  В первый массив добавить один элемент с индексом (!) element и произвольным значением. Из второго массива удалить элемент с индексом 0. Используйте функцию unset();  Вывести на экран элементы под индексом 2 из первого и второго массива.  Вывести на экран содержимое массивов полностью.  Найти количество элементов в каждом массиве. Используйте функцию count(). Вывести результаты на экран.  

10. Вывести на экран N случайных чисел (каждое с новой строки) из диапазона [-21, 35] 

11. Вывести на экран сумму N случайных чисел. 

12. Вывести на экран N случайных чисел (каждое с новой строки). Для каждого числа, начиная со второго, рядом выводить - больше ли оно предыдущего или меньше.  

13. Вывести на экран n-ное число Фибоначчи.  

14. Дано некоторое число длиной от 1 до 5 цифр - вывести его цифры в обратном порядке. Подсказка: используйте цикл while и операцию получения остатка. 

15. Дано некоторое число длиной от 1 до 5 символов, вывести все его "нечётные" цифры в обратном порядке (аналогично предыдущей задаче), если же таких цифр не найдёт, вывести сообщение "Нечетных цифр не обнаружено!" 

16. Задать массив из 7-ми элементов, заполнить его случайными значениями в одном цикле, а в другом цикле вывести эти значения на экран. 

17. Задать двумерный массив размерностью m на n (MxN) элементов (m и n вынести в область определения констант), заполнить его случайными значениями и вывести их на экран уже после того, как весь массив будет заполнен (т.е. заполнять и выводить в разных группах циклов). 

18. Задайте случайным образом массив из N элементов. Выведите его на экран "ёлочкой". Вот начало такого вывода: 

 

1 

2 

3 

4 

5 

1 

2 3 

4 5 6 

7 8 9 10 

11 12 ...... 

Второй вариант - сделайте то же самое, но не используйте массив: у вас есть переменная N, выведете на экран, все числа до N, по тому же принципе что и выше, например, если N=9, то получим: 

1 

2 

3 

4 

1 

2 3 

4 5 6 

7 8 9 

19. Задайте случайным образом массив из N элементов (целых чисел). Найдите максимальное число и напечатайте его. 

20. Задайте случайным образом массив из 20-ти элементов (целых чисел). Найдите минимальное число и напечатайте его. 

21. Даны два массива по 20 элементов каждый (заполните случайными числами, так чтобы среди элементов массива при очередном запуске программы могли встретиться и отрицательные и положительные числа). 

Сравните каждый 3-ий элемент 1-ого массива с каждый 2-ым элементов 2-ого массива - сравнение проводите пока не закончится та выборка, которая короче. 

22. Создайте функцию, которая принимает на вход массив случайных чисел из диапазона [5..12]. Обходит этот массив и делает для каждого элемента следующее (пусть она оказывает побочный эффект прямо в своём теле): 
Если это число равно 5 -- то выведете на экран строку "пять", если 6 -- то строку "шесть", если 7 то число "7", иначе -- строку "какое-то другое число". Используйте для решения задачи оператор switch(link is external) 

23. Есть два массива "a" и "b". На вход вашей программе подаётся массив "a" случайных чисел (10 элементов) из диапазона от 1 до 20. Задача: вывести на экран все числа, которые не содержатся в массиве "b" 

1 
```php
$b = [12, 5, 17, 6, 4]; 
```

Решите эту задачу двумя способами: Без использования in_array()(link is external). С использованием in_array() 

 

 

### Задачи Node JS 

1. Реализуйте функцию, которая будет парсить JSON-файлы и выводить их содержимое в консоль. 

2. Напишите скрипт, который будет перебирать файлы в заданной директории и выводить их имена в консоль. 

3. Реализуйте функцию, которая будет отправлять email-уведомления при определенных событиях. 

4. Создайте модуль для работы с API сторонних сервисов (например, Google Maps). 

5. Создайте модуль для работы с графическими изображениями (обработка, изменение размеров и т.д.). 



<h2 align="center">Решение задач</h2>

```php
//	1.
//	Автор: Хорошко Илья Алексеевич
/*	Дата выполнения:  20.01.2024
*/
echo "Задание 1 ";
echo "Это приветсвие! <br>";

//	2.
echo "Задание 2 <br>";
$nameTVChannel = "STS";
$manafacturerAddress = "Sakhalinskaya street";
$carColor = "Red";
$waterTemperature = 26;
$phoneModel = "Iphone 11";

//	3.
echo "Задание 3 <br>";
$three = 3;
$five = 5;
$eight = 8;
echo "$three, $five, $eight";
echo "<br>";

$sum = $three + $five + $eight;
echo $result = 2 + 6 + 2 / 5 - 1;
echo "<br><br>";

//	4.
echo "Задание 3 <br>";
$a = 1;
$b = 2;
echo "$a, $b";
echo "<br>";
$c = $a;
$d = $b;
echo "$c, $d";
echo "<br>";
$a = 3;
$b = 4;
echo "$a, $b, $c, $d";
echo "<br><br>";

// 5.
echo "Задание 5 <br>";
define("const1", 41);
define("const2", 33);
echo const1 + const2;
echo "<br><br>";

//	6.
echo "Задание 6 <br>";
$a = 152;
$b = '152';
$c = 'London';
$d = array(152);
$e = 15.2;
$f = false;
$g = true;
var_dump($a, $b, $c, $d, $e, $f, $g);
echo "<br><br>";

//	7.
echo "Задание 7 <br>";
echo "\$a = $a, \$b = $b", PHP_EOL;
echo "<br><br>";

//	8.
echo "Задание 8 <br>";
$first = "Доброе утро";
$second = "дамы";
$third = "и господа";
echo $first . " " . $second . " " . $third, PHP_EOL;
echo "<br><br>";

// 9.
echo "Задание 9 <br>";
$arr1 = [1, 2, 3, 4, 5];
$arr2 = [6, 7, 8, 9, 10];
$arr1["element"] = 25;

unset($arr2[0]);
echo $arr1[2], $arr2[2];
echo "<br>";

var_dump($arr1, $arr2);
echo count($arr1), count($arr2);
echo "<br><br>";

//	10.
echo "Задание 10 <br>";
define("N", 5);

for ($i = 0; $i < N; $i++) {
	echo random_int(-21, 35);
	echo "<br>";
}
echo "<br><br>";

//	11.
echo "Задание 11 <br>";
$sum = 0;
for ($i = 0; $i < N; $i++) {
	$sum += random_int(-21, 35);
}
echo $sum;
echo "<br><br>";

// 12.
echo "Задание 12 <br>";
for ($i = 0, $last = null; $i < N; $i++) {
	$num = random_int(-50, 50);
	echo $num;

	if ($last != null)
		if ($num > $last)
			echo " - Больше предыдущего";
		else if ($num < $last)
			echo " - Меньше предыдущего";
		else
			echo " - Равны";
	$last = $num;
	echo "<br>";
}
echo "<br><br>";

//	13.
echo "Задание 13 <br>";
function Fibb($n)
{
	if ($n <= 1) return 0;

	if ($n == 2) return 1;

	return Fibb($n - 1) + Fibb($n - 2);
}

echo N, " число Фибоначчи = ", Fibb(N);
echo "<br><br>";

//	14.
echo "Задание 14 <br>";
$number = 12345;
do {
	echo $number % 10;
	$number = ($number - $number % 10) / 10;
} while ($number > 0);
echo "<br><br>";

//	15.
echo "Задание 15 <br>";
$number = 12345;
$hasOdds = false;
do {
	$num = $number % 10;
	if ($num % 2 != 0) {
		$hasOdds = true;
		echo $num;
	}
	$number = ($number - $number % 10) / 10;
} while ($number > 0);
if (!$hasOdds) echo "Нечетных цифр не обнаружено!";
echo "<br><br>";

//	16.
echo "Задание 16 <br>";
for ($i = 0; $i < 7; $i++) {
	$arr[$i] = random_int(-10, 10);
}
for ($i = 0; $i < 7; $i++) {
	echo $arr[$i], " ";
}
echo "<br><br>";

//	17.
echo "Задание 17 <br>";
$m = 5;
$n = 5;
for ($i = 0; $i < $m; $i++) {
	$arr[$i] = [];
	for ($j = 0; $j < $n; $j++) {
		$arr[$i][$j] = random_int(-10, 10);
	}
}
echo "<br>";
for ($i = 0; $i < $m; $i++) {
	for ($j = 0; $j < $n; $j++) {
		echo str_pad($arr[$i][$j], 4, " ");
	}
	echo "<br>";
}
echo "<br><br>";

//	18.
echo "Задание 18 <br>";
$N = 20;
for ($i = 1; $i <= $N; $i++) {
	$arr[$i - 1] = $i;
}

//1
echo "1)<br>";
for ($i = 0, $j = 0, $k = 1; $i < $N; $i++) {
	echo $arr[$i], " ";
	if (++$j >= $k) {
		echo "<br>";
		$j = 0;
		$k++;
	}
}

//	2)
echo "<br>2)<br>";
for ($i = 1, $j = 0, $k = 1; $i <= $N; $i++) {
	echo $i, " ";
	if (++$j >= $k) {
		echo "<br>";
		$j = 0;
		$k++;
	}
}
echo "<br><br>";

//	19.
echo "Задание 19 <br>";
echo max($arr);
echo "<br><br>";

//	20.
echo "Задание 20 <br>";
echo min($arr);
echo "<br><br>";

//	21.
echo "Задание 21 <br>";
$arr1 = [];
$arr2 = [];

for ($i = 0; $i < 20; $i++) {
	$arr1[$i] = $arr2[$i] = random_int(-10, 10);
}
for ($i = 2, $j = 1; $i < 20; $i += 3, $j += 2) {
	if ($arr1[$i] > $arr2[$j])
		echo "$arr1[$i] больше $arr2[$j] <br>";
	else if ($arr1[$i] < $arr2[$j])
		echo "$arr1[$i] меньше $arr2[$j] <br>";
	else
		echo "$arr1[$i] и $arr2[$j] равны <br>";
}
echo "<br><br>";

//	22.
echo "Задание 22 <br>";
function func($arr)
{
	foreach ($arr as $num) {
		switch ($num) {
			case 5:
				$res = "пять";
				break;
			case 6:
				$res = "шесть";
				break;
			case 7:
				$res = 7;
				break;
			default:
				$res = "какое-то другое число";
				break;
		}

		echo $res;
		echo "<br>";
	}
}
echo func([4,5,6,7,8]);
echo "<br><br>";

// 23.
echo "Задание 23 <br>";
$a = [];
for ($i = 0; $i < 10; $i++) {
	$a[$i] = random_int(1, 20);
}
$b = [12, 5, 17, 6, 4];

//	1)
echo "1)<br>";
$counter = [];
for ($i = 0; $i < count($b); $i++) {
	$counter[$b[$i]] = 1;
}
for ($i = 0; $i < 10; $i++) {
	if (empty($counter[$a[$i]])) echo $a[$i], " ";
}
//	2)
echo "<br>2)<br>";
for ($i = 0; $i < 10; $i++) {
	if (!in_array($a[$i], $b)) echo $a[$i], " ";
}
?>
```
### Задачи Node JS 
1. Реализуйте функцию, которая будет парсить JSON-файлы и выводить их содержимое в консоль. 
```javascript 
let data = require('./file.json');
let string = JSON.stringify(data);
let res = JSON.parse(string);
for (var key in res){
    var value = res[key];
    console.log(key + ": " + value);
}

```
2. Напишите скрипт, который будет перебирать файлы в заданной директории и выводить их имена в консоль. 
```javascript 
const fs = require('fs');
const path = require('path');

const directoryPath = './';

fs.readdir(directoryPath, (err, files) => {
  if (err) {
    console.error('Возникла ошибка при чтении директории:', err);
    return;
  }
  
  files.forEach(file => {
    console.log(file);
  });
});
```
3. Реализуйте функцию, которая будет отправлять email-уведомления при определенных событиях. 
```javascript 
const express = require('express');
const app = express();
const axios = require('axios');

const readline = require('readline');
const nodemailer = require('nodemailer');

const rl = readline.createInterface({
  input: process.stdin,
  output: process.stdout
});


async function sendEmail() {
  
  let transporter = nodemailer.createTransport({
    host: 'smtp.mail.ru',
    port: 587,
    secure: false,
    auth: {
      user: 'khoroshko12@mail.ru',
      pass: 'password',
    }
  });

  
  let mailOptions = {
    from: 'khoroshko12@mail.ru',
    to: 'khoroshko4@mail.ru',
    subject: 'Тема письма',
    text: 'Какой-то текст с котиками ฅ^•ﻌ•^ฅ',
   
  };

  try {
    // Отправляем письмо
    let info = await transporter.sendMail(mailOptions);
    console.log('Письмо из хогвартса доставлено успешно!', info.messageId);
  } catch (error) {
    console.error('ошибка! у вас лапки вместо рук!:', error);
  }
}

rl.question('Отпавляем заявку в хогвартс? (Y/N): ', async (answer) => {
  
  answer = answer.toUpperCase();

 
  if (answer === 'Y' || answer === 'YES') {
    await sendEmail();
  } else {
    console.log('Заявка не отправлена :(');
  }

  rl.close();
});
```
4. Создайте модуль для работы с API сторонних сервисов (например, Google Maps). 
```javascript 
const axios = require('axios');

// Функция для выполнения GET-запроса к API
async function getFromAPI(url) {
  try {
    const response = await axios.get(url);
    return response.data;
  } catch (error) {
    console.error('Ошибка при выполнении GET-запроса:', error);
    throw error;
  }
}

//  для выполнения POST-запроса к API
async function postToAPI(url, data) {
  try {
    const response = await axios.post(url, data);
    return response.data;
  } catch (error) {
    console.error('Ошибка при выполнении POST-запроса:', error);
    throw error;
  }
}
//модули
module.exports = {
  getFromAPI,
  postToAPI
};

const apiService = require('./27');

// Выполнение GET-запроса к GitHub API
async function getUser(username) {
  try {
    const url = `https://api.github.com/users/${username}`;
    const userData = await apiService.getFromAPI(url);
    console.log('Данные пользователя:', userData);
  } catch (error) {
    console.error('Ошибка при получении данных пользователя:', error);
  }
}

// Выполнение POST-запроса к GitHub API
async function getUserRepos(username) {
  try {
    const url = `https://api.github.com/users/${username}/repos`;
    const repos = await apiService.getFromAPI(url);
    console.log('Репозитории пользователя:', repos);
  } catch (error) {
    console.error('Ошибка при получении списка репозиториев:', error);
  }
}


getUser('LongWayyy');
getUserRepos('LongWayyy');
```
5. Создайте модуль для работы с графическими изображениями (обработка, изменение размеров и т.д.).
```javascript 
const jimp = require('jimp');

async function chaosedImage(path){
    let image = await jimp.read(path);
    image.invert(); //инвертирование цвета
    image.dither565();//сглаживание
    image.rotate(180);
    image.writeAsync(path);//записываем обратно изображение
}

module.exports = {chaosedImage};

chaosedImage('./public/cat.jpg');
console.log('вы успешно поменяли кота!');

```



<h2 align="center">Вывод</h2>
Изучил как парсить Json файлы, перебирать файлы в дериктории, отправлять Email по запросу, создавать Api модуль, и модуль для работы с изображениями и закрепил знания по PHP. 
