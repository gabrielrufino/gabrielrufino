## Gabriel Rufino's API

Where you can know a little about me

### Getting started

> GET `/api/infos/general`

**Request:**
```bash
$ BASE_URL=https://raw.githubusercontent.com/gabrielrufino/gabrielrufino
$ curl $BASE_URL/api/general \
    -H Accept: application/json
```

**Response 200:**
```json
{
  "name": "Gabriel Rufino",
  "profession": "Software Engineer",
  "from": "Recife, PE, Brazil",
  "email": "contato@gabrielrufino.com",
  "blog": "www.gabrielrufino.com",
  "created_at": "1999-07-04"
}
```

### Another endpoints

> GET `/api/infos/stack`

**Request:**

```bash
$ curl $BASE_URL/api/infos/stack \
    -H Accept: application/json
```

> GET `/api/infos/hobbies`

**Request:**

```bash
$ curl $BASE_URL/api/infos/hobbies \
    -H Accept: application/json
```

> GET `/api/infos/contact`

**Request:**

```bash
$ curl $BASE_URL/api/infos/contact \
    -H Accept: application/json
```

---

<p align="center">
  <a href="https://www.linkedin.com/in/gabrielrufinojs" target="_blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@6.21.0/icons/linkedin.svg" height="20" width="20" /></a>
  <a href="https://hashnode.com/@gabrielrufino" target="_blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@6.21.0/icons/hashnode.svg" height="20" width="20" /></a>
  <a href="https://t.me/gabrielrufino" target="_blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@6.21.0/icons/telegram.svg" height="20" width="20" /></a>
</p>
