# FIGHTING SIMULATOR 2999

* Реализовать сервис `FightService`
* Реализовать по паттерну MVP презентер для `FightViewController`. Использовать в нём реализацию сервиса `FightService`.
* Создать Coordinator. После того, как у игрока или противника hp становится меньше (или равно) 0, должен открываться экран с результатом (`ResultViewController`). Если у игрока hp < 0, то это поражение в любом случае (нет ничьи).
* Доделать реализации контроллеров. Максимум здоровья — 100, поэтому прогресс отображать как `Float(health) / 100`
* Написать 1 UI и 1 Unit test