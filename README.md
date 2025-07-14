# hsu-fmb

Foundational Model Benchmark

This repository defines Foundation Models benchmark domain models, a gRPC interface and libraries for client and server so that different benchmarks can be implemented in a consistent way.

The Foundation Models benchmarks domain model:
![Domain Model](api/proto/domain_model.drawio.svg)

The API is defined in [api/proto/fmb.proto](api/proto/fmb.proto).

TODO:
- implement the server stubs generation
- implement the go-lang client (list benchmarks, run benchmark, store results into database)
- implement the SQLite and PostgreSQL databases
