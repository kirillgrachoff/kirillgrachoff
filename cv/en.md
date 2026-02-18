# [Grachev Kirill](https://github.com/kirillgrachoff)

Database Internals/Infrastructure Engineer (C++, Go, Rust, Zig)

Bachelor degree MIPT'24 (DIHT) \
[YSDA](https://dataschool.yandex.com/)'25 (big data infrastructure) \
Master course MIPT 2024 - now (DIHT)

Interested in Distributed systems, Concurrency ([scylladb/seastar PR](https://github.com/scylladb/seastar/pull/1944)) and public speech (conf speaker) \
[ICPC MRC 2021](https://icpc.global/regionals/finder/MRC-2022/standings) Second award (Stone Ocean)

tg: [kirillgrachoff](https://t.me/kirillgrachoff), email: (base64) `a2lyaWxsLmdyYWNob2ZmQGdtYWlsLmNvbQo=`, linkedin: [kirillgrachoff](https://www.linkedin.com/in/kirillgrachoff/)

# Experience (in starting order)
- YSDA Teacher \
  september 2025 - december 2025 (fall semester) \
  **"Distributed Systems" Lecturer**
  - Lecture "ABD"
  - Seminar "Chubby"
  - Lecture "FLP"
  - Lecture "Paxos & Multi-Paxos"

- &#9989; Yandex Monitoring Logging \
  june 2025 - present time \
  **Go developer**
  - Created a new service
  - Made some performance improvements: better ser/de protocol, faster log canonization algorithm
  - Worked as an YT dyntables bundle responsible
  - Implemented new internal log format to send between collector and processor
  - Added an ability to ban "heavy" users/queries manually
  - Fixed 100% `query thread` usage at dyntables side

- Yandex YT/[YTsaurus](https://ytsaurus.tech) \
  september 2024 - june 2025 \
  **Database C++ developer** \
  YTsaurus is a Map-Reduce platform which can serve petabytes of data. Dyn. tables is a distributed database build on the top of the YTsaurus platform \
  [commits](https://github.com/ytsaurus/ytsaurus/commits?author=kirillgrachoff) (each commit is a PR) \
  I was working as a BundleContrller developer. Bundle controller is a component which is responsible for bundles maintenance and availability while running 3-dc mode. Bundle is an incapsulation abstraction which is used to prevent users from harming each other.
  - Tuned "ground" clusters as a BundleController developer
  - Fixed issues with race condition while maintenance operations
  - Adapted BundleController to clusters without tablet node allocation mechanism
  - Worked with YT capacity-planner to migrate from bit/s to Byte/s network limits

- [VKontakte](https://vk.com) | Engines \
  july 2023 - august 2024 \
  **Database C++ developer** \
  Messages Engine (Messenger Database) - a home - grown distributed KV database for messages (15'000'000'000 messages/day); 12000 shards, ~900 TiB of Data
  - Accelerated snapshot creation from 70m to 20m (x3 speed up)
  - Designed and implemented new future equal to TTL
  - Added metrics that improved observability of the whole data layer
  - Meetup **speaker** "Co- \& Go- routines: internals and constraints"

- MIPT | Algorithms and Programming Technologies chair \
  february - june 2023 (spring semester) \
  **Teacher assistant** \
  Programming Technologies course
  - Review homework tasks
  - Work as a mentor

- MIPT | [SNARK project](https://github.com/SciProgCentre/snark) \
  february - may 2023 (4 months project) \
  **Kotlin Lead SWE** \
  SNARK is an open-source platform for science articles: publishing/reviewing/discussion, where I worked as a Team Lead / Senior Engineer
  - Write design docs
  - Split whole work into tickets and assign them to another 3 team members
  - Added quite good storage abstraction

- Yandex.Cloud | Yandex \
  Marketplace group \
  july - december 2022 (6 months internship) \
  **Golang/Python Intern SWE**
  - Add [`Ubuntu 22.04 LTS`](https://cloud.yandex.ru/marketplace/products/yc/ubuntu-22-04-lts) and [`openSUSE Leap 15.04`](https://cloud.yandex.ru/marketplace/products/yc/opensuse-15-4) to Cloud using HashiCorp Packer.
  - Improve autopublishing new OS versions. (scale using one builder instance instead of many)
  - Refactor Go service (repair Concurrency code).
  - Add hcl language (terraform language) to autopublishing service.
  - Write a part of a new Go microservice (Concurrent part + monitoring).

- Huawei Russian Research Institute | Moscow R\&D \
  Math Modeling Lab | Algorithm challenges team \
  june - august 2022 (2 months internship) \
  **C/C++, Golang intern dev/researcher**
  - 5G networks [PDCCH](https://www.sharetechnote.com/html/5G/5G_PDCCH.html) protocol optimization.
  - Ideas are implemented in Huawei 5G base stations.

# Education
- [MIPT](https://phystech.edu) DIHT (2024 - 2026) Master course | Data analysys chair (YSDA/Yandex)
- [YSDA](https://dataschool.yandex.com/) (2023 - 2025) | Big Data Infrastructure
- [MIPT](https://phystech.edu) DIHT (2020 - 2024) Bachelor course | Applied Mathematics and Computer Science | Financial Technologies chair (Tinkoff)

# Open Source Contributions
[scylladb/seastar](https://github.com/scylladb/seastar/pull/1944), [bazelbuild/rules_java](https://github.com/bazelbuild/rules_java/commits?author=kirillgrachoff), [ydb-platform/ydb](https://github.com/ydb-platform/ydb/commits?author=kirillgrachoff), [ytsaurus/ytsaurus](https://github.com/ytsaurus/ytsaurus/commits?author=kirillgrachoff)

# Hard Skills
- C++, Go, Rust
- Distributed systems theory and practice
- [Concurrency](https://gitlab.com/Lipovsky/concurrency-course) theory and practice
- Advanced Algorithms and Data Structures
- Familiar with: **bpftrace**, TLA+ ([Repo](https://github.com/kirillgrachoff/tlaplus-examples)), Zig, Operating Systems Internals

# Competitions
- [ICPC MRC 2021](https://icpc.global/regionals/finder/MRC-2022/standings) - Second award (`Stone Ocean` team)
- Codeforces 2100+ [kirill.grachoff](https://codeforces.com/profile/kirill.grachoff)
- Codeforces Problemsetter ([Rounds](https://codeforces.com/contests/writer/kirill.grachoff))
