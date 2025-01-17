# Помощник по работе с Git

### Основные команды:
**pwd** - показать текущую папку  
**$**   - программа ждет команду  
**~**  - обозначение домашней директории  
**cd**  - сменить директорию  
**ls**  - вывести содержимое директории  
**..**  - чтобы вернуться в родительскую директорию, т.е. на уровень выше  
**.**   - обращение к текущей директории  

**Параметр** показывает над чем выполняется команда  
**Флаг или Ключ** добавляют к команде, чтобы модифицировать ее выполнение

**ls -a** - вызов расширенного списка содержимого (отобразятся все скрытые файлы)
**ls ~**  - выведет содердимое домашней директории вне зависимости от того что показывает pwd
**ls..**  - покажет содержимое родительской дирекции

**touch** - команда для создания файла
```
$ touch test.txt
```

**mkdir (make directiry)** - создать директорию
```
$ mkdir new-dir
```

**-p** - флаг для создания целой структуры директория одной командой
```
$ mkdir -p dir1/dir-inside/dir-deepir-inside
```
**mkdir ~/my-git-projects** создаст папку my-git-projects внутри домашней директории

**touch ../../file.txt** создаст файл file.txt на две папки выше по иерархии

Допустим, если находимся в директории projects/git/hello, команда **touch ../..file.txt** создаст файл по пути projects/file.txt

**cp (copy)** - команда для копирования файлов
синтаксис: что_копируем куда_копируем
```
$ cp index.html src/
```

**mv (move)** - переместить
синтаксис: что_переместить куда_переместить
```
$ mv ../file.txt me.png important files
```



