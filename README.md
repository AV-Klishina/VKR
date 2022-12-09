# Тема ВКР: «Разработка автоматизированного рабочего места администратора номерного фонда отеля»

**Тип ВКР** – прикладная работа.

**Цель исследования** – повышение качества функций администратора номерного фонда отеля на основе разработки его автоматизированного рабочего места.

**Объект исследования** – процессы администрирования номерного фонда отеля.

**Предмет исследования** – автоматизация процессов администрирования номерного фонда отеля.

**Методы исследования** – системный анализ, функциональное моделирование процессов.

**Задачи исследования:**

* Анализ процессов администрирования номерного фонда отеля и обоснование необходимости разработки автоматизированного рабочего места.
* Разработка функциональных моделей и требований к программному средству и базе данных рабочего места администратора номерного фонда отеля.
* Реализация программного средства и базы данных рабочего места администратора номерного фонда отеля.

## UML Use Case

![img](http://www.plantuml.com/plantuml/png/BCQn3SGm20NGdYaOvLP1c0ienaJuU_yqUTNxRKZZvAHzntga9JbhbNfN6gEFaSSmrcYTtzFWDJPD-uDHt74vU4IR8cgHAEgjeufrcmY2Q7zViRe-4NTd5pGHHPGkKduX0hSKMFHn3BXmI10L5I311vZu3bdEvVmBR_w8zxIxOgA38hllTj-RUJEpyPjmKONBUIZn2IrwxF28dItisgwmiMiCTbKcudaYVkFLWAq85FGK3EW2br_eR843rnKwnK5N5aLuEv-zl9pFmbdIV-VbrYNvG7mNU3IOZkvA9wcZvBEj6PrU0bhP2ZZ817upnpqsolLKroIhvBHPAPyzEkNqrCcOIZ3WmBy7HMONEZpO3HvjRU-3BMt1poMsFieqrxQnXSgdHmBsZmxxM1bsx4OMd5QfCcReuct0Jtp1r_8lfnvpeYt7QVx1QTKIsKL7WInnPM6ytJZfP2HrJGgnRC9t67ZiXTEnq3wAYxrcIhwoB-qsG7bNF5ooTbVzSzzqlfpuskmcA1WEqkq8ysHTsvxzJuczWDwMIgNizid8VOpAlIglPsUfMwMYxZ5mXkgVcpxwUEl3rScIikfUfXLIwZsFMgrUa6Rs8wSYLIdad1zhjkgYEZewEQlINgUzAOhpU97sEkrDsYTfdnO5_zkEZqzEgmpg39eC9XcGNN0YX0oa3cTK9KHO4oekpITKl9YzViLVf3y0)

### Участники (actors) и цели (goals)

| Участник  | Категория  | Цель (goal) |
|---|---|---|
| Администратор | Основной  | Регистрация гостя, Подбор номера, Выбор дат проживания |
| Программное обеспечение  | Инструмент  | Предоставить администратору возможность зарегестрировать гостя, подобрать номер, определить даты проживания. Программное обеспечение подбирает дополнительные услуги и расчитывает стоимость проживания |

### Предусловия (pre-conditions)

Администратор запускает программу.

### Постусловия (post-conditions)

Оформленный гость.

### Основной поток (main flow)

| Участник  | Действие (activity)  | Ожидаемый результат |
|---|---|---|
| Администратор | Открывает программу | Интерфейс, с помощью которго осуществляется работа |
| Администратор | Вносит данные| Оформленный гость |

### Исключения (exceptions)

| Условие (риск) | Последствия | Реакция |
|---|---|---|
| |  |  |

### Альтернативы (alternates)

### Временные параметры

* Триггер (событие, стартующее прецедент): начало работы программы
* Номинальная частота повторения прецедента: 30 раз в день
* Продолжительность прецедента: 5 минут

## UML Use Sequence

![img](https://www.plantuml.com/plantuml/png/fPHDhjf048JtSuhMs-S2MKJlAlDWf5Y9RMGFPCjFI1GHAJ-Rx43SO49mOWamL-Y-KRgC20P1dYmMMC8pzLLrpS1Zxctc-_5Rax-9afxDR4nncgITrraQE_9PtndRyMb6_9NNlEMITrpAICOov21ZhcH8DgT-xZAZSXzrefvDF3tmWkV4uPQ8mmDqxzpJXMp9XQwkyAntA7XWkjRR9vixNV-cp3ySIC51iJkPoRJUY7M37FJY5RZqalYxxYXWp6L3m0LnHVoBgtgfm8JHm7e7MIl4ZYlUre6B5Zh-IR2krQl312GJVR6HYQOACcqLOgsOlNusQ1dpAEVpTQnH7h0e5TmVYjhB46amJ23aWHCNW75nLlEjra2xdzmiysxQynNV7xXLyR217MxfqUwelMPmQXSAWqSpxP8h32cVJk9A4yli0beICjQb1lc05wRhpj50DgxQud02o28VKKEfWTxNFzbjat7jy75hmPZB6EbWoh__9PJHUMZvGlZwtuGADeykwUe_r5y0.png)


## UML Use Class

![img](http://www.plantuml.com/plantuml/png/SoWkIImgAStDuIhEpimhI2nAp5N8pS_BJyueoizDLIWfAatbkh3WmjOBUoxikx3tOfE2JOskhiA5kK3UdWjRBpPmNLXyOUE5VHSRBkowi84OoOL0VjF5XelD5xPSs7jXnuLTACRZLZJzmeQBZK25ku4O9BGLtJBSIXO3HNS3pTfyOGDkHRE08a0Uo15S5oPUR02xfmUl98OB75BpKe112G00)
