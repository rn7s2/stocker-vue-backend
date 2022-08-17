# stocker-vue-backend
Naive program to help tracking batches of goods.

## Guide
### Prerequisite
- Rust toolchain
- MariaDB/MySQL

### Steps
- Create database `stocker-vue`
- Run `models/create_tables.sql` to create data tables.
- Set `DATABASE_URL` environment variable, format: `mysql://<user>:<password>@<host>:<port>`
- `cargo run`

## License
```
Copyright © 2022 雷瑞祺 mail@rn7s2.cn
This work is free. You can redistribute it and/or modify it under the
terms of the Do What The Fuck You Want To Public License, Version 2,
as published by Sam Hocevar. See the COPYING file for more details.
```
