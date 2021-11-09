# Proof of Concept Rust BBQ

The mix of Rust, [ByteBase], [Questdb], and web technologies.

## Objectives

- Simple CRUD api with 1 type built using [Postgres crate](https://docs.rs/postgres/0.19.2/postgres/index.html)
    > Partial Failure, no update or delete.
- 1 table for CRUD built on [ByteBase] & [QuestDB]
    > Partial Failure, no update or delete.
- Docker compose to handle networking

## Notes

Skipped the rust implementation due to lack of deleting or updating data.

[QuestDB]: https://questdb.io/
[Questdb]: https://questdb.io/
[ByteBase]: https://github.com/bytebase/bytebase
