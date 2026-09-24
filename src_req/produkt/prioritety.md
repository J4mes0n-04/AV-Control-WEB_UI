# Приоритеты экранных возможностей (P0 / P1 / P2)

> **Статус:** заготовка.  
> **Аудитория:** PDE (что в MVP веба), планирование первых changes.

## Назначение документа

Сводка **только WEB UI/UX**: что показываем в P0 (MVP), что в P1, что откладываем в P2. Не дублировать всю продуктовую матрицу Scope.

## Как читать приоритет

<!-- TODO: кратко из Scope §0.2 — P0/P1/P2 = версия; отличие от Out-of-Scope -->

## P0 — MVP веб (первая очередь)

### Конфигуратор (`vozmozhnosti/konfigurator`)

<!-- TODO: пункты из Scope §0.5 блок M-PRJ, только UI -->

### Клиент комнаты (`vozmozhnosti/klient-komnaty`)

<!-- TODO: пункты из Scope §0.5 блок M-ROOM -->

### Admin и сквозной UI

<!-- TODO: FR-ADM / FR-SEC на экране, obshchiy-interfejs — только перечень -->

## P1 — релизная версия 1 (экран)

<!-- TODO: сводка по трём поверхностям -->

## P2 — следующие версии (экран)

<!-- TODO: сводка; явно «не в текущем репозитории / change» -->

## Трассировка к capability OpenSpec

| Приоритет | Capability | Первый change (идея) |
|-----------|------------|----------------------|
| P0        | konfigurator |                    |
| P0        | klient-komnaty |                  |
| P0        | admin-kontroller |                |
| P0        | obshchiy-interfejs |              |

**Источник:** Scope §0.5, §1.1–1.2 (M-PRJ, M-ROOM), FR с пометкой веб в PRD.

## Связь с OpenSpec

Помогает заполнить **Capabilities** в proposal и выбрать порядок `/opsx:propose`.
