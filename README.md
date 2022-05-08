git merge Bag_Reports - мержим

6. Запушить main на внешний репозиторий.
*
git push origin -u main

7. В ветке CheckLists набросать структуру чек листа.
*
git checkout CheckLists  - прыгаем в ветку
touch CheckLists.txt - создаем тексовый документ
vim CheckLists.txt - добавляем текст
жмем а - для печать, добавляем текст, esc _ :wq  _ enter

8. Запушить структуру на внешний репозиторий
*
git add . - добавляем файл
git commit -m "add" - коммитим, фотографируем на репозиторий
git push - отправляем файл на внешний репозиторий

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
*
В разделе Pull request - жмем new Pull request 
Меняем ветки base: main - compare: checklsts
Дополняем коммент (write) : checklist struckture и жмем "Create pull request"

10. Синхронизировать Внешнюю и Локальную ветки Main
*
В консоле git:
git checkout main - прыгаем в ветку 
git fetch - смотрим изменения в реозитории
git pull - синхронизирум изменения в репозиториях
