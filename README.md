# 3-ivt-17-t4
Тема 4. 3ИВТ/17

## Тема 4 ИСР https://moodle.herzen.spb.ru/mod/page/view.php?id=123171

4.1. Изучив конкретную систему управления проектами, использовав одну из стратегий ветвления (branching strategies) на основе системы версий Git реализовать добавление функции (рефакторинга существующего кода) в существующем программном проекте, предварительно создать запрос на добавление функционала (issue).

  ##### ThreeFlows
  ##### https://github.com/MarinaSvistunova/test_branching_strategies
    
    ThreeFlows
 <img src="https://github.com/ctel-prj-mng/3-ivt-17-t4-MarinaSvistunova/blob/master/img/1branches.png" width="70%">
 
    Создание файла в ветке master
 <img src="https://github.com/ctel-prj-mng/3-ivt-17-t4-MarinaSvistunova/blob/master/img/2master.png" width="70%">
 
    Создание issue
 <img src="https://github.com/ctel-prj-mng/3-ivt-17-t4-MarinaSvistunova/blob/master/img/3issue.png" width="70%">
 
    Редактирование файла в ветке master для решения issue
 <img src="https://github.com/ctel-prj-mng/3-ivt-17-t4-MarinaSvistunova/blob/master/img/4changed_function.png" width="30%">
 
    Решение issue
 <img src="https://github.com/ctel-prj-mng/3-ivt-17-t4-MarinaSvistunova/blob/master/img/5close_issue.png" width="50%">
 
    Создание релиз-кандидата в ветке candidate
 <img src="https://github.com/ctel-prj-mng/3-ivt-17-t4-MarinaSvistunova/blob/master/img/6merge_from_master_to_candidate.png" width="70%">
 
    Создание релиза в ветке release
 <img src="https://github.com/ctel-prj-mng/3-ivt-17-t4-MarinaSvistunova/blob/master/img/7merge_from_candidate_to_release.png" width="70%">
 
    Ветка candidate
 <img src="https://github.com/ctel-prj-mng/3-ivt-17-t4-MarinaSvistunova/blob/master/img/8branche_candidate.png" width="70%">
 
    Ветка release
 <img src="https://github.com/ctel-prj-mng/3-ivt-17-t4-MarinaSvistunova/blob/master/img/9branche_release.png" width="70%">
 

4.2. Реализация конкретного проекта с нуля (проект согласуется с преподавателем): написание фрагмента технического задания, создание макетов продукта (мобильной, настольной версий), реализация макетов с использованием одного из клиентских фреймворков, создание схемы функционирования продукта, вариантов его использования конечным пользователем, создание плана юзабилити-тестирования продукта, выбор методологии и модели разработки, организация учета и управления задачами и временем (создание диаграммы Гантта). Оформление отчета по результатам работы и презентации с основными результатами. Публичное выступление.

https://drive.google.com/file/d/1boG3pLNZ8WMV1PQmyLM2laBLn1ExRs45/view?usp=sharing

## Тема 4 ВСР https://moodle.herzen.spb.ru/mod/page/view.php?id=123173


4.1. Анализ одной методологии разработки программных продуктов и создание презентации с её кратким описанием. Публичное представление. 

**Ссылка на презентацию: https://docs.google.com/presentation/d/1qosgmyKbZOebcYZGnUdsU98FsLZ1kZHT3TtabWOfdZ0/edit?usp=sharing** 

**Итеративная модель (Iterative model)**

Не все модели жизненного цикла последовательны. Существуют также итеративные (или инкрементальные) модели, в которых используется другой подход. Вместо одной продолжительной последовательности действий здесь весь жизненный цикл продукта разбит на ряд отдельных мини-циклов. Причем каждый из них состоит из все тех же базовых стадий модели жизненного цикла. Эти мини-циклы называются итерациями. В каждой из итераций происходит разработка отдельного компонента системы, после чего этот компонент добавляется к уже ранее разработанному функционалу.

Итеративная модель не предполагает полного объема требований для начала работ над продуктом. Разработка программы может начинаться с требований к части функционала, которые могут впоследствии дополняться и изменяться.  Процесс повторяется, обеспечивая создание новой версии продукта для каждого цикла.

В несколько упрощенном виде, итеративная модель состоит из четырех основных стадий, которые повторяются в каждой из итераций (plan-do-check-act):
* определение и анализ требований;
* дизайн и проектирование – согласно требованиями. Причем дизайн может как разрабатываться отдельно для данной функциональности, так и дополнять уже существующий;
* разработка и тестирование – кодирование, интеграция и тестирование нового компонента;
* фаза ревью – оценка, пересмотр текущих требований и предложения дополнений к ним.

По результатам каждой итерации принимается решение – будут ли использованы ее результаты для дополнения существующей функциональности в качестве входной точки для начала следующей итерации (т.н. инкрементальное прототипирование). В конечном итоге, достигается точка, в которой все требования были воплощены в продукте – происходит релиз.

Плюсы итеративной модели:

+ раннее создание работающего ПО;
+ гибкость – готовность к изменению требований на любом этапе разработки;
+ каждая итерация – маленький этап, для которого тестирование и анализ рисков обеспечить проще, чем для всего жизненного цикла продукта.

Минусы итеративной модели:

+ каждая фаза – самостоятельна, отдельные итерации не накладываются;
+ могут возникнуть проблемы с реализацией общей архитектуры системы, поскольку не все требования известны к началу проектирования.

Когда оптимально использовать итеративную модель?

* Требования к конечной системе заранее четко определены и понятны.
* Проект большой или очень большой.
* Основная задача должна быть определена, но детали реализации могут эволюционировать с течением времени.
