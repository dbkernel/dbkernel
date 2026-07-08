![Profile views](https://komarev.com/ghpvc/?username=dbkernel&color=blueviolet&style=flat-square)

<div align="center">

## Hi 👋, I'm Wenshuang Lu (卢文双)

### Senior Database Kernel Engineer · Building Cloud-Native Distributed Databases

</div>

---

🔭 **Currently working on** cloud-native MySQL kernel R&D — storage engines, replication, query optimization

🧠 **Background** in Postgres-XC, Greenplum, RadonDB, ClickHouse, and mainstream RDBMS internals (MySQL / PostgreSQL)

📝 **Technical blog** → [dbkernel.com](https://dbkernel.com) · [dbkernel.github.io](https://dbkernel.github.io/)

💬 **Ask me about** database internals → [open an issue](https://github.com/dbkernel/dbkernel/issues)

---

### 🏗 Projects

#### SealDB — Enterprise Database Platform

| Project | Description |
|---------|-------------|
| [sealdb/neosql](https://github.com/sealdb/neosql) | MySQL-kernel-based fork with enterprise features — columnar storage, HTAP |
| [sealdb/neodb](https://github.com/sealdb/neodb) | Enhanced [radon](https://github.com/radondb/radon) with **distributed transactions** and **read/write consistency** |
| [sealdb/metatroni](https://github.com/sealdb/metatroni) | Enhanced [patroni](https://github.com/patroni/patroni) — **MySQL & PostgreSQL HA** |
| [sealdb/neoha](https://github.com/sealdb/neoha) | Enhanced [xenon](https://github.com/radondb/xenon) — **MySQL & PostgreSQL HA**, consensus via **Raft** and **etcd** |
| [sealdb/sealdb](https://github.com/sealdb/sealdb) | SealDB platform — unified OLTP + OLAP, storage-compute separation |

#### RadonDB — Foundation

| Project | Description |
|---------|-------------|
| [radondb/radon](https://github.com/radondb/radon) | Distributed SQL database |
| [radondb/xenon](https://github.com/radondb/xenon) | MySQL high availability with Raft-based replication |

---

### 🏗 Project Evolution

```mermaid
flowchart TB
    subgraph Foundation["RadonDB Foundation"]
        radon["radondb/radon<br/><i>Distributed SQL</i>"]
        xenon["radondb/xenon<br/><i>MySQL HA / Raft</i>"]
    end

    subgraph Kernel["Kernel Track"]
        mysql["MySQL Kernel"]
        neosql["sealdb/neosql<br/><i>Enterprise · Columnar · HTAP</i>"]
    end

    subgraph SealDB["SealDB Enhancements"]
        neodb["sealdb/neodb<br/><i>Distributed Txn · Consistency</i>"]
        neoha["sealdb/neoha<br/><i>MySQL + PG HA · Raft / etcd</i>"]
    end

    sealdb["sealdb/sealdb<br/><b>Unified Platform</b><br/><i>OLTP + OLAP · Storage-Compute Separation</i>"]

    mysql --> neosql
    radon -->|"enhance"| neodb
    xenon -->|"enhance"| neoha
    neosql --> sealdb
    neodb --> sealdb
    neoha --> sealdb

    style sealdb fill:#1a1a2e,stroke:#fe428e,stroke-width:2px,color:#fff
    style neosql fill:#16213e,stroke:#4ecca3,color:#fff
    style neodb fill:#16213e,stroke:#4ecca3,color:#fff
    style neoha fill:#16213e,stroke:#4ecca3,color:#fff
```

---

### 📚 Latest Writing

- [MySQL 生态现有计算下推方案汇总](https://dbkernel.com) *(2024)*
- [MySQL 测试框架 MTR 系列教程](https://dbkernel.github.io/) *(2023, 4-part series)*
- [业内 MySQL 线程池主流方案详解](https://dbkernel.github.io/) *(MariaDB / Percona / AliSQL / TXSQL)*

📖 [All articles →](https://dbkernel.github.io/)

---

### 🛠 Tech Stack

<p align="left">
  <a href="https://www.linux.org/" target="_blank"><img src="https://dbkernel-1306518848.cos.ap-beijing.myqcloud.com/icons/linux.svg" alt="linux" width="50" height="50"/></a>
  <a href="https://www.docker.com/" target="_blank"><img src="https://dbkernel-1306518848.cos.ap-beijing.myqcloud.com/icons/docker.svg" alt="docker" width="50" height="50"/></a>
  <a href="https://kubernetes.io" target="_blank"><img src="https://dbkernel-1306518848.cos.ap-beijing.myqcloud.com/icons/kubernetes.svg" alt="kubernetes" width="50" height="50"/></a>
  <a href="https://www.cprogramming.com/" target="_blank"><img src="https://dbkernel-1306518848.cos.ap-beijing.myqcloud.com/icons/cplusplus.svg" alt="c++" width="50" height="50"/></a>
  <a href="https://golang.org" target="_blank"><img src="https://dbkernel-1306518848.cos.ap-beijing.myqcloud.com/icons/golang.svg" alt="go" width="50" height="50"/></a>
  <a href="https://www.python.org" target="_blank"><img src="https://dbkernel-1306518848.cos.ap-beijing.myqcloud.com/icons/python.svg" alt="python" width="50" height="50"/></a>
  <a href="https://www.rust-lang.org/" target="_blank"><img src="https://dbkernel-1306518848.cos.ap-beijing.myqcloud.com/icons/rust.svg" alt="rust" width="50" height="50"/></a>
  <a href="https://www.mysql.com/" target="_blank"><img src="https://dbkernel-1306518848.cos.ap-beijing.myqcloud.com/icons/mysql.svg" alt="MySQL" width="50" height="50"/></a>
  <a href="https://www.postgresql.org/" target="_blank"><img src="https://dbkernel-1306518848.cos.ap-beijing.myqcloud.com/icons/postgresql.svg" alt="PostgreSQL" width="50" height="50"/></a>
  <a href="https://clickhouse.tech/" target="_blank"><img src="https://dbkernel-1306518848.cos.ap-beijing.myqcloud.com/icons/clickhouse.svg" alt="ClickHouse" width="50" height="50"/></a>
  <a href="https://redis.io/" target="_blank"><img src="https://dbkernel-1306518848.cos.ap-beijing.myqcloud.com/icons/redis.svg" alt="Redis" width="50" height="50"/></a>
</p>

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://gh-trophy.cdnsoft.net/?username=dbkernel" alt="trophy" />
</p>

<p align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs?username=dbkernel&layout=compact&theme=radical&langs_count=8" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=dbkernel&show_icons=true&theme=radical" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=dbkernel&theme=radical" alt="GitHub Streak" />
</p>
