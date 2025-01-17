# Дотримуючись стандартів PHP-FIG релігійно #

FIG розшифровується як Framework Interoperability Group (Група із сумісності фреймворків).

PHP-FIG була створена розробниками фреймворків на конференції php|tek у 2009 році. Відтоді до них звернулася і виступила за цей стандарт ще низка розробників, і група збільшилася з 5 до 20 учасників.

Навколо PHP-FIG існує багато суперечок. Багато хто вважає, що це найкраще, що трапилося в PHP-спільноті, після самого PHP, тоді як інші вважають, що це потрібно забути як страшний сон.

Одна з проблем, пов'язаних із PHP-FIG, це те, як вони самі себе представляють у своєму [FAQ](http://www.php-fig.org/faqs/):

> Ідея групи - надати учасникам можливість говорити про спільність між нашими проектами і знайти способи спільної роботи. Наша основна аудиторія - це ми самі, але ми дуже добре розуміємо, що за нами спостерігає вся інша PHP-спільнота. Якщо інші захочуть прийняти те, що ми робимо, вони можуть це зробити, але це не мета. Ніхто в нашій групі не хоче вказувати вам, як програмісту, як будувати додаток.

Однак коли ми розглядаємо роботу деяких членів групи, ми можемо ясно бачити, що мета абсолютно суперечить наведеній вище тезі. Вони невпинно намагаються зробити з PHP-FIG «Групу PHP стандартів». Це, до речі, і було їхньою первісною назвою. Вони роблять це, позиціонуючи свою роботу «сучасним PHP» у своїх книжках, на сайтах, на різних форумах, блогах, визначаючи всі інші напрямки як застарілі.

Однією з проблем, пов'язаних з PHP-FIG, є те, що хоча багато фреймворків та опенсорсних проєктів прийняли деякі стандарти групи, ці стандарти здебільшого стосуються проблем з точки зору фреймворків. А це часто робить їх непридатними в реальних практичних ситуаціях.

Багато розробників створюють програмне забезпечення для промислового застосування, і воно повинно бути надзвичайно ефективним, надійним та економічно вигідним, таким, щоб клієнти готові були його купувати та використовувати. Вони не повинні відволікатися на стандарти, які розробили фанатики фреймворків. Якщо вони будуть це робити, це стане катастрофою для бізнесу.

Якщо якусь групу і має бути створено, то вона має відображати інтереси всієї PHP-спільноти, а не тільки прихильників фреймворків і опенсорсних CMS. Вона має бути представлена розробниками самого PHP, з набагато більшим числом членів, які мають право голосу.

Якщо ви вирішили прийняти стандарти, розроблені PHP-FIG, ви маєте розуміти, що деякі з цих стандартів, як-от стандарти автозавантажувача PSR-0 і PSR-4 та низка інших стандартів, мають прямий вплив на те, яким у підсумку буде ваш код.

У багатьох сферах потрібні високомасштабовані, економічно ефективні програми, які не потребують багато часу для розроблення і які просто неможливо створити, якщо дотримуватися стандартів PHP-FIG.

**Неправильний шлях**: Дотримуватися стандартів PHP-FIG, релігійно. ![Thumbs down](/img/thumbs-down.png)
