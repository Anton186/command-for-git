https://learngitbranching.js.org/?locale=ru_RU тренажер
clear // Очистить
git init // Инициализирует папку (папку выбрать заранее в комманде ctrl+O)
git --version // Посмотреть версию гита
git status // Показывает в какой ветке и что можно зафиксировать (комит)
git add file // Добавить файл для отслеживания <file>
git commit -m "comment" // Создание нового коммита с комментарием comment
git commit --amend -m "Новое имя" // Переименование последнего созданного коммита
git log // Показывает какие версии существую (журнал событий)
git log --graph // Показывает историю в виде графа/дерева
git checkout (первые четыре символа кода commit или название ветки) // Переключает на версию файла указанных первых четырех символов или на ветку
git checkout master // Переключает на самую актуальную версию (основную, чистовик)
git checkout -b (название ветки) // Создаёт новую ветки (название ветки) и переключает на неё
git diff // Показывает разницу между сохраненным состоянием и текущим (ctrl+s для сохранения)
git branch // Показывает какие ветки существуют и где мы находимся
git branch (название ветки) // Создает новую ветку (название ветки)
git branch -d (название ветки) // Удаляет ветку (название ветки)
git merge (название ветки) // Добавляет в ветку в которой находимся информацию из ветки (название ветки) и совмещает все коммиты
git add .gitignore // Создает папку гитигнор в которую добавляем название файлов с расширением для игнорирования их
git clone ссылка // Копирует репозиторий из сайта на компьютер
git remote -v // Показывает список удаленных репозиториев связанных с локальным
git pull origin (название ветки) // Вливает изменения с локального на удаленные (название ветки)
dotnet new gitignore // создает новый файл .gitignore для dotnet