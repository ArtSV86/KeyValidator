Отчёт о тестировании <Инструкция по установке OpenJDK11 для Windows>


<08.03.2021> - <08.03.2021> было проведено <ручное тестирование> приложения <Инструкция по установке OpenJDK11 для Windows>.

На тестирование затрачено: <0.25h>

В результате тестирования дефекты не выявлены.


Описание процесса тестирования
* Шаг 1. Перейдите на сайт adoptopenjdk.net.

* Шаг 2. Выберите опции как на скриншоте ниже и нажмите на кнопку скачивания: 
![Screenshot](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/pic/win-adoptopenjdk.png)
* Шаг 3. Запустите на установку скачанный MSI-файл и нажмите кнопку "Next": 
![Screenshot](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/pic/win-step1.png)

* Шаг 4. Прочитайте и согласитесь с условиями лицензии:
![Screenshot](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/pic/win-step2.png) 

* Шаг 5. Выберите опции как на экране (удостоверьтесь, что установка происходит в Program Files и опция Add to PATH выбрана):
![Screenshot](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/pic/win-step3.png)

* Шаг 6. Нажмите на кнопку "Install":
![Screenshot](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/pic/win-step4.png)

* Шаг 7. Дождитесь окончания установки и нажмите на кнопку "Finish":
![Screenshot](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/pic/win-step5.png)

* Откройте терминал и выполните команду:
```
java -version
```
* Появится:
```
openjdk version "11.0.5" 2019-10-15
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.5+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.5+10, mixed mode)
```







В качестве тестовых данных использовались данные <https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md>:

#### Ожидаемый результат. 
При выполнении команды "java -version" появится следующий результат:
```
openjdk version "11.0.5" 2019-10-15
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.5+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.5+10, mixed mode)
```
#### Фактический результат.
При выполнении команды "java -version" появится следующий результат:
```
openjdk version "11.0.10" 2021-01-19
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.10+9)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.10+9, mixed mode)
```


Тестирование производилось в следующем окружении:

    <Windows 64>
    <версия Java "11.0.10">
    
