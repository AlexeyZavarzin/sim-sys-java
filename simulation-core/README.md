Event - основной класс, описывающий событие

Agent - представляет некоторую сущность, которая имеет состояния, может переходить из одного
состояния в дугое. Фактически агент задается графом переходов. Возможны вероятностные переходы.

Агент генерит события, которые связаны с ним - AgentEvent, каждое такое событие содержит ссылку на
Agent. Переход из одного состояния в другое происходит по некоторому событию.

Агент может рассматриваться как совокупность независимых процессов в дискретно событийном ИМ.
Подробности в agent-based modeling.

Описание работы агента:
Агент содержит состояние Это состояние может меняться В момент изменения состояния вызывается
обработчик Это фактически означает, что агент содержит некоторый Event, который он передает в
провайдер Мы передаем только ближайшие эвенты 
