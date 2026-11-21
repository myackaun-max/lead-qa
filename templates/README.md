# QA-шаблони

Порядок роботи: спершу ризики, потім план, кейси, виконання, звіт.

| Файл | Коли використовувати |
|---|---|
| [01-test-plan.md](01-test-plan.md) | Старт фічі або релізу: ризики, обсяг, підхід, критерії |
| [02-test-case-template.md](02-test-case-template.md) | Написання тест-кейсів |
| [03-smoke-checklist.md](03-smoke-checklist.md) | Приймання кожної нової збірки (15–30 хв) |
| [04-regression-checklist.md](04-regression-checklist.md) | Перед релізом, повна або вибіркова регресія |
| [05-bug-report-template.md](05-bug-report-template.md) | Оформлення дефекту |
| [06-release-test-report.md](06-release-test-report.md) | Підсумок тестування і рішення Go / Go з ризиками / No-Go |

Шкали, спільні для всіх шаблонів:
- Severity: Critical / Major / Minor / Trivial
- Priority: P1–P4 (P1 найтерміновіший)
- Ризик: Ймовірність (1–5) × Вплив (1–5)
