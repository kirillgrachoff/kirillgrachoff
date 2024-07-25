# Грачев Кирилл

Infrastructure/Database Internals Engineer (C++, Go, Rust, Zig)

Бакалавр МФТИ'24 (ФПМИ) \
Студент ШАД (инфраструктура) \
[ICPC MRC 2021](https://icpc.global/regionals/finder/MRC-2022/standings) Second award (Stone Ocean) \
Интересно следующее:
- Распределённые системы
- Concurrency ([PR](https://github.com/scylladb/seastar/pull/1944))
- Database internals
- Продвинутые алгоритмы и структур данных
- Внутренности облачных сервисов
- Публичные выступления (на конференциях)

PR в OpenSource: [scylladb/seastar](https://icpc.global/regionals/finder/MRC-2022/standings), [ydb-platform/ydb](https://github.com/ydb-platform/ydb/commits?author=kirillgrachoff), [bazelbuild/rules_java](https://github.com/bazelbuild/rules_java/commits?author=kirillgrachoff) 

## Контакты
tg: [kirillgrachoff](https://t.me/kirillgrachoff) \
vk: [@k4](https://vk.com/k4) \
email: (base64) a2lyaWxsLmdyYWNob2ZmQGdtYWlsLmNvbQo= \
linkedin: [kirillgrachoff](https://www.linkedin.com/in/kirillgrachoff/)

# Опыт
- ВКонтакте | Движки \
  лето 2023 - сейчас \
  **Разработчик C++** \
  Движок сообщений - самописное специализированное распределённое NoSQL хранилище для личных сообщений ВКонтакте (15'000'000'000 messages/day) насчитывает 12000 шардов и ~800 TiB данных
  - Ускорил создание snapshot'а (в терминах Raft) с 70 до 20 минут
  - Задизайнил и сделал возможность выставлять TTL у некоторых записей (распределённого таймера нет)
  - Добавил метрики, которые сильно увеличили наблюдаемость, во все движки
  - Подготовил доклад (был спикером) "Co- \& Go- routines: что внутри и зачем" на внутренний митап

- МФТИ | Кафедра алгоритмов и технологий программирования \
  февраль - июнь 2023 \
  **Ассистент преподавателя** \
  Курс "Технологии программирования"
  - Ревьюил решения задач по паттернам, CMake, GTest и подобным "взрослым" технологиям
  - Отвечал на вопросы в чатике/был ментором

- МФТИ | [SNARK project](https://github.com/SciProgCentre/snark) \
  февраль - июнь 2023 \
  **Kotlin Lead SWE** \
  SNARK - open source платформа для публикации статей. Был эксперимент с альтернативной архитектурой, где я выполнял роль тимлида/ведущего инженера
  - Писал дизайн документы, предлагал архитектуру
  - Принимал ключевые решения
  - Смог придумать достаточно неплохую модель storage

- Yandex.Cloud | Yandex Cloud Marketplace \
  июль - декабрь 2022 \
  **Golang/Python Intern SWE**
  - Добавил [`Ubuntu 22.04 LTS`](https://cloud.yandex.ru/marketplace/products/yc/ubuntu-22-04-lts) и [`openSUSE Leap 15.04`](https://cloud.yandex.ru/marketplace/products/yc/opensuse-15-4) в Облако с пом. HashiCorp Packer.
  - Изменил код сервиса сборки образов для боллее бережливого масштабирования
  - Переписал многопоточную синхронизацию внутри сервиса сборки образов
  - Добавил возможность использовать hcl language (terraform language), а не только json для сервиса сборки образов
  - Добавил метрики и примитивы синхронизации в новый микросервис

- **Личный ментор** \
  май - декабрь 2022
  - Отвечал на вопросы по Concurrency
  - Ревьюил задачи, помогал разобраться с ошибками

- Huawei Russian Research Institute | Moscow R\&D \
  июнь - август 2021 \
  **C/C++, Golang intern dev/researcher** \
  Math Modeling Lab | Algorithm challenges team
  - 5G networks [PDCCH](https://www.sharetechnote.com/html/5G/5G_PDCCH.html) protocol optimization.
  - Ideas are implemented in Huawei 5G base stations.

# Образование
- [ШАД](https://shad.yandex.ru/) (2023 - now) | Инфраструктура больших данных
- [МФТИ](https://mipt.ru) ФПМИ (2020 - 2024) | Прикладная Математика и Информатика | Кафедра финансовых технологий (Tinkoff)
- Moscow Worksops Juniors 2020

# Open Source Contributions
- [scylladb/seastar](https://github.com/scylladb/seastar/pull/1944)
- [bazelbuild/rules_java](https://github.com/bazelbuild/rules_java/commits?author=kirillgrachoff)
- [ydb-platform/ydb](https://github.com/ydb-platform/ydb/commits?author=kirillgrachoff)
- [snark](https://github.com/SciProgCentre/snark/commits?author=kirillgrachoff)

# Hard Skills
- C++ 11-20, Go, Rust, Scala 2/3
- Distributed systems theory and practice (AB, RSM, \[Multi\]Paxos/Raft (Chubby/ZK), DFS (FB Tectonic), 2PC, Calvin, Nakamoto Consensus, PBFT/HotStuff)
- Database Internals
- [Concurrency](https://gitlab.com/Lipovsky/concurrency-course)
- Operating Systems (Linux)
- Advanced Algorithms and Data Structures
- bpftrace
- Docker, CMake, Bazel, Protobuf, gRPC
- GRASP Patterns, SOLID, ACID, CI/CD, Testing, Git, Gitlab CI, GitHub Actions, Agile practices
- Familiar with:
  - [TLA+](https://github.com/kirillgrachoff/tlaplus-examples)
  - Kotlin (+ Coroutines), Python 3
  - Android (Jetpack Compose)
  - Hadoop (HDFS, Hive, Spark (Scala), Map Reduce)
  - [YDB](https://ydb.tech), [YTsaurus](https://ytsaurus.tech)

# Соревнования, самообразование, ачивки
- Участник "Ордена Феникса" ВКонтакте (сообщество спикеров)
- [ICPC MRC 2021](https://icpc.global/regionals/finder/MRC-2022/standings) - Second award (`Stone Ocean` team)
- Codeforces Problemsetter ([Rounds](https://codeforces.com/contests/writer/kirill.grachoff))
- Восстановил Linux/Manjaro ноутбук после ошибок с использованием Timeshift с btrfs (пришлось править /boot)

# Projects
- [github](https://github.com/kirillgrachoff)
  - [TLA+ examples](https://github.com/kirillgrachoff/tlaplus-examples)
  - [load tester](https://github.com/kirillgrachoff/load_tester)
  - [quic-server](https://github.com/kirillgrachoff/go-quic-potato)
  - [MIPT C++ Algorithms](https://github.com/kirillgrachoff/mipt-cpp-algorithms)
- [codeforces](https://codeforces.com/profile/kirill.grachoff)

