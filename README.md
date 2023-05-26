
# Personal Info


Name：Shicong Nie


Phone：(+86) 13026339196


WeChat：[nsc-sunflower](https://github.com/niebayes/niebayes/blob/main/assets/wechat.png)


Mail：[niebayes@gmail.com](mailto:niebayes@gmail.com)


Github：[https://github.com/niebayes](https://github.com/niebayes)


# Summary

- Open source enthusiast participating in Google Summer of Code with Jina AI and Open Source Promotion Plan with Apache Doris.
- Passionate about technology, participated in PingCAP TinyKV Bootcamp and OceanBase miniob Database Competition.
- Interested in distributed storage, implemented Multi-Raft, Multi-Paxos, and LSM-DB.
- Strong self-motivation, studied renowned open courses such as MIT 6.824, CMU 15-445, MIT 6.S081, Harvard CS265.
- Enthusiast in systems programming, familiar with distributed systems, database systems, and operating systems.
- Skilled in fundamental data structures and algorithms, familiar with programming languages such as C/C++, Go, Python, Rust.
- Interested in generative AI, multimodal AI, Neural Search, and AI infrastructure, actively learning related technologies.
- Research experience in robot localization, multi-sensor fusion, and 3D vision, have a strong foundation in mathematics.

# Seeking Jobs


Full-time/Internship, On-site/Remote, Domestic/International Job Positions including but not limited to:

- Distributed Storage Development Engineer
- Cloud-native, AI Infrastructure, MLOps Development Engineer
- Database Kernel Development Engineer
- Software Engineer

# Education


Wuhan University of Technology, Master Degree, Major in Mechanical Engineering, Seq. 2018 - Jul. 2021


Wuhan University of Technology, Bachelor Degree, Major in Mechanical Engineering, Seq. 2014 - Jul. 2028


# Projects


### [Highly-Available Distributed Key-Value Database based on Multi-Raft](https://github.com/niebayes/tinykv-summary)  


_**(Keywords：Distributed Database, Raft, Percolator, Go)**_

- Consensus Layer: Implemented the Raft protocol supporting leader election, log replication, and log compaction. Implemented optimizations such as prevote, automatic step down, async apply, and flow control.
- Service Layer: Supported single-point configuration change and region split. Utilized a scheduler for automatic region scheduling to achieve load balancing. Implemented read index to improve throughput.
- Transaction Layer: Implemented MVCC based on the Percolator protocol.

### [Write-Optimized Key-Value Database based on LSM Tree](https://github.com/niebayes/LSM-DB)  


_**(Keywords：Database, LSM Tree, Rust)**_

- Supported insert, update, delete, and scan operations.
- Implemented the memtable backed by a B-tree and designed the file format, Bloom filter, and sparse index for the
sstable.
- Designed and implemented a unified iterator interface for efficient data retrieval.
- Supported leveled, tiered, and hybrid compaction strategies.
- Implemented crash recovery using Write-Ahead Logging mechanism.

### Other Projects

- [bustub](https://github.com/niebayes/CMU-15-445-2020): Implemented buffer pool manager, B+ tree index, extendable hash index, lock manager, and deadlock prevention for the bustub database. _**(Keywords: Database Storage, C++)**_
- [miniob](https://github.com/niebayes/miniob-summary): Added parsing and execution capabilities for SQL statements such as multi-row insert, multi-col update, cross join, inner join, order by, group by, having, sub-select, and aggregation to the miniob database. _**(Keywords: Database SQL, C++)**_
- [xv6](https://github.com/niebayes/MIT-6.S081-summary): Added features like mmap, kernel thread, copy-on-write, lazy allocation, and compensated round-robin scheduling to the xv6 operating system. _**(Keywords: Operating System Kernel, C)**_
- [balancebeam](https://github.com/niebayes/Balancebeam): A proxy server with features such as health checks, thread pool, connection pool, cache management, rate limiting, and load balancing. _**(Keywords: Proxy Server, Rust)**_
- [deet](https://github.com/niebayes/DEET-Debugger): A debugger with common debugging commands like breakpoints, next, continue, and backtrace. _**(Keywords: Debugger, Rust)**_

# Open Source Projects


### Google Summber of Code - Jina AI - Apr. 2023 - Present  


_**(Keywords: MLOps, Multi-Modal AI, Neural Search, Python, Go)**_

- Enhanced the stateful executor feature based on Raft protocol, wrapping relevant Go code into Python bindings using cgo library.
- Implemented optimizations such as follower read and provided consistency mode options for service deployment in the stateful executor feature.
- Developed a highly available and high-throughput neural search service using the Jina framework and ANNLite library.

### Open Source Promotion Plan - Apache Doris - May. 2023.05 - Present  


_**(Keywords: Analytical Database, C++)**_

- Added SQL parsing and execution support for array functions like `array_contains_all`.
- Added information about Segment Compaction in the Load Profile.

# Technical Skills


Programming Languages: C/C++, Go, Python, Rust


Frameworks or Libraries: Jina, DocArray, Apache Doris, Apache Spark, LevelDB, Hashicorp Raft, etcd Raft


Developer Tools: Linux, Git, Docker, CMake, VS Code, Vim, LaTeX


Languages: Mandarin (Native), English (Fluent)

