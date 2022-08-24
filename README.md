# kottans-frontend

## Git Basics
* Скріншоти з курсу [Introduction to Git and GitHub](https://www.coursera.org/learn/introduction-git-github):
  * [Week#1](./taks_git_basics/../task_git_basics/Introduction_to_Git_and_GitHub_week1.png)
  * [Week#2](./taks_git_basics/../task_git_basics/Introduction_to_Git_and_GitHub_week2.png)
* Скріншоти з ресурсу [learngitbranching](https://learngitbranching.js.org/?locale=uk):
  * [Основи](task_git_collaboration/git-branching_1.png)
  * [Віддалені репозиторії](task_git_collaboration/git-branching_2.png)

__Міркування__: свої міркування після ресурсів цього навчального блоку я описав нижче, у розділі __Git Collaboration__ після того, як повністю їх усі пройшов.

## Linux CLI, and HTTP
Скріншоти тестів на [Linux Survival](https://linuxsurvival.com/linux-tutorial-introduction/):
* [Quiz #1](./task_linux_cli/Linux-Survival_Quiz-1.png)
* [Quiz #2](./task_linux_cli/Linux-Survival_Quiz-2.png)
* [Quiz #3](./task_linux_cli/Linux-Survival_Quiz-3.png)
* [Quiz #4](./task_linux_cli/Linux-Survival_Quiz-4.png)

__Міркування:__ частину команд я знав до того, як почав проходити Linux Survival. Зокрема, `ls`, `mkdir`, `cd`. Новою для мене була можливість копіювати, переміщувати, створювати та видаляти файли та директоріїї через консоль. Кльовою штукою є можливість перенаправляти команди (`>`, `>>`) та групи і рівні доступу до файлів (user, group, other; read, write, execute). Планую їв використовувати надалі по мірі необхідності.

## Git Collaboration
Скріншоти пройдених матеріалів:
* [learngitbranching](https://learngitbranching.js.org/?locale=uk)
  * [Основи](task_git_collaboration/git-branching_1.png)
  * [Віддалені репозиторії](task_git_collaboration/git-branching_2.png)
* [Introduction to Git and GitHub](https://www.coursera.org/learn/introduction-git-github/home/info)
  * [Week#1](task_git_collaboration/Introduction-to-Git-and-GitHub_1.png) 
  * [Week#2](task_git_collaboration/Introduction-to-Git-and-GitHub_2.png) 
  * [Week#3](task_git_collaboration/Introduction-to-Git-and-GitHub_3.png) 
  * [Week#4](task_git_collaboration/Introduction-to-Git-and-GitHub_4.png) 

__Міркування:__ 
* у __[learngitbranching](https://learngitbranching.js.org/?locale=uk)__ для мене новим були переважно можливості, описнані у 9-16 завданнях розділ "Віддалені репозиторії". Великою перевагою цього ресурсу, є його візуалізація процесів і структури репозиторію. Здивувало те, що віддалені гілки представляються собою не гілку на віддаленому репозиторії, а це ніби локальна гілка, яка містить інформацію простатус відповідної гілки на GitHub. Гадаю, всі описані там команди і підходи буду використовувати :)
* __[Introduction to Git and GitHub](https://www.coursera.org/learn/introduction-git-github/home/info)__ корисним було те, що всі команди і процеси були наглядними, продемонстрованими на реальних робочих задачах. Але для розуміння основ попередній ресурс значно кращий. Новою для мене була можливість подивитися історію комітів і гілок у "графічному представленні" (команда `git log --graph --oneline`). Особливо корисним був розділ про те, як скасовувати внесені зміни (у Working Tree, історії комітів, скасування злиття гілок у випадку конфлікту через `git merge --abort `). Гадаю, все з цього курсу мені знадобиться.

## Intro to HTML and CSS
Скріншот з переліком пройдених курсів можна подивитися за цим [посиланням](task_html_css_intro/learn-html-css.png).

__Міркування:__ нічого нового для мене тут не було. Все це знав уже. Але в процесі освіжив знання про `@font-face`. Всі ці знання буду використовувати, це ж база вебу.

## Responsive Web Design
+ Усіх жаб [посадив](./task_responsive_web_design/froggy.png) на листя;
+ Виростив [достатньо](./task_responsive_web_design/garden.png) моркви, щоб спекти знаменитий 20-морквяний пиріг.

__Мірування:__ флексами володів до цього, тут нічого коментувати. Grid був абсолютно новим для мене. Не сказав би, що мене щось здивувало. Просто новий матеріал. Напевно все буду використовувати, що дізнавня про гріди. Спочатку без спрощених записів (накшталт `grid-template` і те, що за ним слідує), а тоді як газу дам, тупо еееееееммммммм...

## HTML CSS Practice
Реалізував [pop-up](https://ivan-chukhalo.github.io/Kottans_Pop-up/) на чистому HTML-CSS.

## JS Basics
Скріншоти опрацьованих матеріалів:
* [Вступ до JS (лекції)](./task_js_basics/1%20introducting%20to%20js.png);
* [freeCodeCamp: Basic JavaScript](./task_js_basics/2%20basic%20js.png);
* [freeCodeCamp: ES6 Challenges](./task_js_basics/3%20es6.png);
* [freeCodeCamp: Basic Data Structures ](./task_js_basics/4%20Basic%20Data%20Structure.png);
* [freeCodeCamp: Basic Algorithm Scripting ](./task_js_basics/5%20basic%20algorithm.png);
* [freeCodeCamp: Functional Programming](./task_js_basics/6%20Functional%20Programming.png);
* [freeCodeCamp: Algorithm Scripting Challenges ](./task_js_basics/7%20intermediate%20algorithm%20scripting.png);

__Міркування:__ певними основами JS я володів до проходження цих лекцій і завдань. Але мене здивувало те, як працює рекурсія в JS. Я знав у загальних словах, що в програмуванні називається рекурсією, але не мав чіткого уявлення, як це працює в мовах програмування (зокрема JS). Коли в завданні на freeCodeCamp побачив приклад рекурсивної фукції, дивився і не розумів як це взагалі може працювати. Потім загуглив, зрозумів, як стеки викликів функції накладаються один на одного і все стало зрозуміло. Цікавами були алгоритмічні завдання і концепції функціонального програмування. Новими для мене були де-які функції масива, зокрема `Array.prototype.filter()`, `Array.prototype.reduce()`, `Array.prototype.map()`. Планую всі знання, які тут освіжив чи здобув нові, використовувати в майбутньому. Бо 'pure JS' це база).

## DOM
Скріншоти опрацьованих матеріалів:
+ [Document Object Model Manipulation](https://www.coursera.org/learn/html-css-javascript-for-web-developers/home/week/5) - [скріншот](./task_js_dom/dom-manipulation.png);
+ [freecodecamp Algorithm Scripting Challenges](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/intermediate-algorithm-scripting) - [скріншот](./task_js_dom/algorithm-scripting-challenges.png);
+ Реалізував [side-menu](https://ivan-chukhalo.github.io/Kottans_side-menu/).

__Міркування:__ цікавими були алгоритмічні завдання із freeCodeCamp, новими були JS команди для маніпуляції з DOM-деревом. Буду використовувати їх в майбутньому.
