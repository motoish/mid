# mid

Edit docker-compose.yml with `midPoint + postgres` fitable versions.

## Introduction

- Versions of midPoint fit with different postgres.

```text
> midPoint(4.0.3) + postgres(12) <
> midPoint(4.4) + postgres(14) <
```

- To build `docker-compose-{midPoint_version}.yml`

```sh
$ docker-compose -f docker-compose-{midPoint_version}.yml up
```

- Remove container

```sh
$ docker-compose docker-compose-{midPoint_version}.yml down
```
