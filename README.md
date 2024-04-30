# Проектная работа №2 для SkillFactory DevOps

Данный репо размещен на github
Для работы с проектом локально используйте команду git clone https://github.com/IlyaPleshachev/project_work_2.git

Настройки blame
- git config user.name
- git config user.email

Файл конфига /project_work_2/gitconfig

Для любих изменений обязательно(!) заводим тикет в Jira, правило для именования PW2-XXXX, где XXXX циферное обозначение порядкового номера тикета.

Стандартный сценарий для работы с изменениями в гите:
- Создать ветку с именем PW2-XXXX под тикет в Jira из свежего мастера
  1) git pull master
  2) git checkout -b "PW2-XXXX"  
- Поработать в ней.
  1) git add . (либо выборочно файлы по имени)
  2) git commit -m "Внятный коммит"
  3) git push origin PW2-XXXX
- Оформить merge request.
- Получить аппрув от коллег, решить все треды.
- Выкатить релиз(при необходимости сделать ребейз из свежего мастера)

