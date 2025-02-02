# example-teamcity
# Домашнее задание к занятию "09.04 Teamcity"
This is a fork of ["mnt-homeworks"](https://github.com/netology-code/mnt-homeworks/tree/master/09-ci-04-teamcity).
 It contains following changes:
* Создайте новый проект в teamcity на основе fork
* Сделайте autodetect конфигурации
* Сохраните необходимые шаги, запустите первую сборку master'a
* Поменяйте условия сборки: если сборка по ветке master, то должен происходит mvn clean package, иначе mvn clean test
* Мигрируйте build configuration в репозиторий

Brunch feature/add_reply contains :
* Создайте отдельную ветку feature/add_reply в репозитории
* Напишите новый метод для класса Welcomer: метод должен возвращать произвольную реплику, содержащую слово hunter
* Дополните тест для нового метода на поиск слова hunter в новой реплике
* Сделайте push всех изменений в новую ветку в репозиторий
* Убедитесь что сборка самостоятельно запустилась, тесты прошли успешно
* Внесите изменения из произвольной ветки feature/add_reply в master через Merge
* Убедитесь, что нет собранного артефакта в сборке по ветке master
* Настройте конфигурацию так, чтобы она собирала .jar в артефакты сборки
* Проведите повторную сборку мастера, убедитесь, что сбора прошла успешно и артефакты собраны
* Проверьте, что конфигурация в репозитории содержит все настройки конфигурации из teamcity
* В ответ предоставьте ссылку на репозиторий
