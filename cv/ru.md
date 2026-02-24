# [Грачев Кирилл](https://github.com/kirillgrachoff)

Database Internals/Infrastructure Engineer (C++, Go, Rust, Zig)

Бакалавр МФТИ'24 (ФПМИ) \
Выпускник ШАД'25 (инфраструктура) \
Студент магистратуры МФТИ (ФПМИ, кафедра анализа данных)

Интересны Распределённые системы, Concurrency ([scylladb/seastar PR](https://icpc.global/regionals/finder/MRC-2022/standings)) и публичные выступления (на конференциях и митапах) \
Занимался олимпиадным программированием [ICPC MRC 2021](https://icpc.global/regionals/finder/MRC-2022/standings) Second award (Stone Ocean), [codeforces Div1](https://codeforces.com/profile/kirill.grachoff)

tg: [kirillgrachoff](https://t.me/kirillgrachoff), email: (base64) `a2lyaWxsLmdyYWNob2ZmQGdtYWlsLmNvbQo=`, linkedin: [kirillgrachoff](https://www.linkedin.com/in/kirillgrachoff/), vk: [@k4](https://vk.com/k4)

# Опыт (в порядке начала)
- ШАД (Лектор)
  сентябрь 2025 - декабрь 2025 (осенний семестр)
  **Лектор курса "Разработка распределённых систем"**
  - Лекция "ABD"
  - Семинар "Chubby"
  - Лекция "FLP"
  - Лекция "Paxos & Multi-Paxos"

- &#9989; Яндекс
  сентябрь 2024 - **сейчас**
  - Monitoring Logging \
    **Разработчик Go**
    - Реализовал новый сервис, настроил CI (интересен бизнес-контекст)
    - Улучшил некоторые алгоритмы: улучшил внутренний протокол передачи логов и написал более быстрый алгоритм канонизации логов
    - Исправил баг, который не могли найти 2 месяца
    - Был администратором YT dyntables bundle для логов
    - Исправил проблему 100% использования `query thread` в бандле
    - Поддержал прямое и обратное кодирование логов Cloud
    - Добавил механизм ручного бана пользователей/запросов
    - Рассказал команде про Log-Structured Merge-tree
  - YT/[YTsaurus](https://ytsaurus.tech) \
    **Разработчик C++/Go** \
    YTsaurus (YT) - Map-Reduce система, хранящая петабайты данных. Дин. таблицы - распределённая база данных поверх этой платформы.
    - Адаптировал bundle controller для open source. Bundle Controller - это сервис, следящий за тем, чтобы у бандлов были ресурсы.
    - Провёл миграцию квот с битов в секунду на байты в секунду на всех кластерах.
    - Исправил ошибки, которые не позволяли уменьшить использование ресурсов бандлами.
    - Исправил проблему race condtion во время maintenance.
    - Поднимал bundle controller на кластерах без аллокаций (т.н. земельные/ground кластера).
    - Доделывал k8s operator.

- ВКонтакте | Движки \
  июль 2023 - август 2024 \
  **Разработчик C++** \
  Движок сообщений - самописное специализированное распределённое KV хранилище для личных сообщений ВКонтакте (15'000'000'000 сообщений в день) насчитывает 12000 шардов и ~900 TiB данных
  - Ускорил создание snapshot'а (в терминах Raft) с 70 до 20 минут, ускорил тесты на реальных данных
  - Задизайнил и сделал возможность выставлять TTL у некоторых записей (распределённого таймера нет)
  - Добавил метрики, которые сильно увеличили наблюдаемость всех движков
  - Подготовил доклад (был спикером) "Co- \& Go- routines: что внутри и зачем" на внутренний митап

- МФТИ | Кафедра алгоритмов и технологий программирования \
  февраль - июнь 2023 \
  **Ассистент преподавателя** \
  Курс "Технологии программирования" \
  Ревьюил решения задач курса (паттерны, CMake, GTest, GitHub Actions, Docker ...), отвечал на вопросы в чатике/был ментором

- МФТИ | [SNARK project](https://github.com/SciProgCentre/snark) \
  февраль - июнь 2023 \
  **Kotlin Lead SWE** \
  SNARK - open source проект для публикации статей. Был эксперимент с альтернативной архитектурой, где я выполнял роль тимлида/ведущего инженера
  - Писал дизайн документы, предлагал архитектуру
  - Распределял задачи по 3 другим людям
  - Смог придумать достаточно неплохую модель storage

- Yandex.Cloud | Yandex Cloud Marketplace \
  июль - декабрь 2022 \
  **Golang/Python Intern SWE**
  - Переписал многопоточную синхронизацию внутри сервиса сборки образов, что позволило сделать cancellation
  - Изменил код сервиса сборки образов для боллее бережливого масштабирования
  - Добавил возможность использовать hcl language (terraform language), а не только json для сервиса сборки образов
  - Добавил [`Ubuntu 22.04 LTS`](https://cloud.yandex.ru/marketplace/products/yc/ubuntu-22-04-lts) и [`openSUSE Leap 15.04`](https://cloud.yandex.ru/marketplace/products/yc/opensuse-15-4) в Облако.

- Huawei Russian Research Institute | Moscow R\&D \
  июнь - август 2021 \
  **C/C++, Golang intern dev/researcher** \
  Math Modeling Lab | Algorithm challenges team
  - 5G mobile networks [PDCCH](https://www.sharetechnote.com/html/5G/5G_PDCCH.html) protocol optimization.
  - Ideas are implemented in Huawei 5G base stations.

# Образование
- [МФТИ](https://mipt.ru) ФПМИ (2024 - now), Магистр | Кафедра анализа данных (ШАД/Яндекс)
- [ШАД](https://shad.yandex.ru/) (2023 - 2025) | Инфраструктура больших данных
- [МФТИ](https://mipt.ru) ФПМИ (2020 - 2024), Бакалавр | Прикладная Математика и Информатика | Кафедра финансовых технологий (Tinkoff)

# Open Source Contributions
[scylladb/seastar](https://github.com/scylladb/seastar/pull/1944), [bazelbuild/rules_java](https://github.com/bazelbuild/rules_java/commits?author=kirillgrachoff), [ydb-platform/ydb](https://github.com/ydb-platform/ydb/commits?author=kirillgrachoff)

# Hard Skills
- C++, Go, Rust
- Distributed systems theory and practice
- [Concurrency](https://gitlab.com/Lipovsky/concurrency-course) theory and practice
- Advanced Algorithms and Data Structures
- Familiar with: **bpftrace**, [TLA+](https://github.com/kirillgrachoff/tlaplus-examples), Zig, Operating Systems Internals

# Соревнования
- [ICPC MRC 2021](https://icpc.global/regionals/finder/MRC-2022/standings) - Second award (`Stone Ocean` team)
- Codeforces 2100+ [kirill.grachoff](https://codeforces.com/profile/kirill.grachoff)
- Codeforces Problemsetter ([Rounds](https://codeforces.com/contests/writer/kirill.grachoff))
