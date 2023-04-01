МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»
Лабораторная работа №5
"JS"

Выполнил: Акиомов И.В.

Проверил: Соболев Е. И.

г. Южно-Сахалинск
2023 год

Введение
Лабораторная работа по созданию скриптов на языке JavaScript.

Цели и задачи
1. Создайте переменную str и присвойте ей значение 'hdfgv'. Обращаясь к отдельным символам этой строки выведите на экран символ 'h', символ 'd', символ 'v'.
2. Напишите скрипт, который считает количество секунд в часе. 
3. Переделайте приведенный код так, чтобы в нем использовались операции +=, -=, *=, /=, ++, --. Количество строк кода при этом не должно измениться. Код для переделки: var num = 1; num = num + 12; num = num - 14; num = num * 5; num = num / 7; num = num + 1; num = num - 1; alert(num);
Создайте переменную num и присвойте ей значение 3. Выведите значение этой переменной на экран с помощью метода alert.
Создайте переменные a=10 и b=2. Выведите на экран их сумму, разность, произведение и частное (результат деления).
Создайте переменные c=15 и d=2. Просуммируйте их, а результат присвойте переменной result. Выведите на экран значение переменной result.
Создайте переменные a=10, b=2 и c=5. Выведите на экран их сумму.
Создайте переменные a=17 и b=10. Отнимите от a переменную b и результат присвойте переменной c. Затем создайте переменную d, присвойте ей значение 7. Сложите переменные c и d, а результат запишите в переменную result. Выведите на экран значение переменной result.
Напишите скрипт, который считает количество секунд в часе, в сутках, в месяце.
Создайте три переменные - час, минута, секунда. С их помощью выведите текущее время в формате 'час:минута:секунда'.
Создайте переменную, присвойте ей число. Возведите это число в квадрат. Выведите его на экран.
Напишите однострочное решение, которое вычисляет сумму квадратных корней для всех чётных чисел целочисленного массива.
Яблоко стоит 1.15, апельсин стоит 2.30. Сколько они стоят вместе – чему равна сумма 1.15 + 2.30 с точки зрения JavaScript?
Какое будет выведено значение: let x = 5; alert(x++); ?
Чему равно такое выражение: [ ] + false - null + true ?
Что выведет этот код: let y = 1; let x = y = 2; console.log(x); ?
Чему равна сумма [ ] + 1 + 2?
Создайте переменные a6, a7, a8, a9, a10. Поместите в них результат выражений: 5 % 3, 3 % 5, 5 + '3', '5' - 3, 75 + 'кг'
Напишите скрипт, который находит площадь прямоугольника высота 23см. (в числовую переменную height), шириной 10см (в числовую переменную width), значение площади должно хранится в числовой переменной s.
Напиши скрипт, который находит объем цилиндра высотой 10м (переменная heightC) и диаметром основания 4м (dC), результат поместите в переменную v.
Даны размер ипотечного кредита (S — 2 млн.руб), процентная ставка (p — 10%), кол-во лет (years — 5). Найти переплату по кредиту, значение переплаты должно содержаться в переменной perepl.
Определите переменные str, num, flag и txt со значениями «Привет», 123, true, «true». При помощи оператора определения типа убедитесь, что переменных принадлежат типам: string, number, boolean.
Дано число, необходимо вернуть противоположное число.
https://www.codewars.com/kata/56530b444e831334c0000020

https://www.codewars.com/kata/583710ccaa6717322c000105

https://www.codewars.com/kata/5a805d8cafa10f8b930005ba

https://www.codewars.com/kata/5763bb0af716cad8fb000580

https://www.codewars.com/kata/578a8a01e9fd1549e50001f1

https://www.codewars.com/kata/57eae20f5500ad98e50002c5

Решить предложенные задачи.
Научиться создавать переменные, проводить над ними операции (сложения, вычитания и т.д.), выводить переменные или результат операций.
Решение задач
              
              <p>задание 1</p>
                <script>
                let str='hdfgv';
                document.write(str[0]+','+str[1]+','+str[4]);
                </script>

<p>задание 2</p>
               
               <script>
                let secondHous=60*60;
                document.write('в часу '+secondHous+ ' секунд');
                </script>

<p>задание 3 выплывающее окно</p>
              
              <script>
                var num=1;
                num+=12;
                num-=14;
                num*=5;
                num/=7;
                num++;
                num--;
                alert(num);
                </script>

<p>задание 4 выплывающее окно</p>
                
                <script>
                var num=3;
                alert(num);
                </script>

<p>задание 5</p>
       
       <script>
        var a=10, b=2;
        document.write(a+b);
        document.write(a-b);
        document.write(a*b);
        document.write(a/b);
        </script>

<p>задание 6</p>
       
               <script>
                var c=15, d=2;
                resut=c+d;
                document.write(resut);
                </script>

<p>задание 7</p>

                <script>
                var c=5, a=10, b=2;
                resut=c+a+b;
                document.write(resut);
                </script>

<p>задание 8</p>
                
                <script>
                var a=17, b=10;
                c=a+b;
                d=7;
                result=c+d;
                document.write(result);
                </script>

<p>задание 9</p>
              
              <script>
                let secondHous=60*60;
                let secondSut=secondHous*24;
                let secondManth=secondSut*31;
                document.write('в часу '+secondHous+ ' секунд'+' в сутках '+secondSut+ ' секунд'+' в месяце '+secondManth+ ' секунд');
                </script>

<p>задание 10</p>
                
                <script>
                let hour=12;
                let minute=50;
                let second=37;
                document.write(hour+':'+minute+':'+second);
                </script>

<p>задание 11</p>
              
              <script>
                var a=17
                result=a*a;
                document.write(result);
                </script>

<p>задание 12</p>
             
             <script>
                document.write(  [1, 2, 3, 4, 5, 6, 7,8,9,10].filter(n => n % 2 == 0).reduce( (sum, n) => sum + n**0.5, 0 ));
                </script>

<p>задание 13<p>
               
               <script>
                var apple = 1.15, orange = 2.30
                result= apple + orange;
                document.write(result);
                </script>

<p>задание 14<p>
               
               <script>
                var x=5;
                alert(x++);
                </script>

<p>задание 15<p>
              
              <script>
                var result = []+false-null+true;
                document.write(result);
                </script>

<p>задание 16</p>
              
              <script>
                let y=1;
                let x=y=2;
                console.log(x);
                </script>

<p>задание 17<p>

                <script>
                var result = []+1+2;
                document.write(result);
                </script>

<p>задание 18<p>
               
               <script>
                a6=5%3;
                a7=3%5;
                a8=5+'3';
                a9='5'+3;
                a10=75+'kg'
                document.write(a6);
                document.write(a7);
                document.write(a8);
                document.write(a9);
                document.write(a10);
                </script>

<p>задание 19<p>
               
               <script>
                const heigth =23;
                const width =10;
                const s= heigth * width;
                document.write(s);
                </script>

<p>задание 20<p>
               
               <script>
                const heigthC =23;
                const dC =10;
                const v= Math.PI*Math.pow(dC/2,2)*heigthC;
                document.write(v);
                </script>

<p>задание 21<p>
              
              <script>
                let s = 2e6, p=10, years=5;
                let pereki = (s*(p/100)*years);
                document.write('сумма переплат '+ pereki +' руб');
                </script>

<p>задание 22<p>
              
              <script>
                let str="привет", num=123, flag=true, txt="true";
                document.write(typeof str =='string');//true
                document.write(typeof num =='number');//true
                document.write(typeof flag =='boolean');//true
                document.write(typeof txt =='string');//true
                </script>

<p>задание 23<p>
             
             <script>
                const num = 5;
                result = num*-1;
                document.write(result);
                </script>
Код задач:

                function chromosomeCheck(chrom) {
                if (chrom == 'X'){alert('Поздравляю у вас дочь');}
                else if (chrom == 'Y'){alert('Поздравляю у вас сын');}
                else {alert('введите правильную хромосому');}
                }
                }
        
                function simpleMultiplication(number) {
                if (number % 2 == 0)
                {console.log(number*8);}
                else {console.log(number*9);}

                    } 
                    
                function nearestSq(n){
                        return Math.pow(Math.round(Math.sqrt(n)),2);
                    } 

                var countSquares = function(cuts){
                  return cuts != 0 ? (cuts+1)**3 - (cuts-1)**3 : 1;
                    }
        
              
              function periodIsLate(last, today, cycleLength) {
                  var temp = Math.ceil((today - last)/(1000 * 60 * 60 * 24));
                  if (temp > cycleLength) return true; else return false;
                    }
        
        
                        function noSpace(x){
                          return x.replaceAll(" ","");
                            }
                            
Вывод: При помощи таких средств как HTML, CSS, и программы visual studio получилось создать страницы по образцу. Задача выполнена.                      
