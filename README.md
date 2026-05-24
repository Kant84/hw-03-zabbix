# Домашнее задание: Система мониторинга Zabbix. Часть 2

**Выполнил:** Санакин Андрей

## Задание 1 — Шаблон мониторинга CPU и RAM

Шаблон: **Test Template**

| Item | Key | Интервал |
|------|-----|----------|
| CPU utilization | system.cpu.util[,user] | 1m |
| Memory utilization | vm.memory.size[pused] | 1m |

### Скриншот шаблона:
![Задание 1 — Шаблон CPU RAM](screenshots/zadanie-1.png)
