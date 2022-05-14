## Gabriel Rufino's API

<img align="left" alt="Octocat" width="200px" src="./assets/octocat.png" />

Read is sometimes boring, making HTTP requests is always awesome. **The challenge is getting to know me using requests to this API.** You ready?

### Getting started

I'll help you with the first endpoint: general informations about me.

> GET `/api/infos/general`

<br />

The base URL for all endpoints is `https://raw.githubusercontent.com/gabrielrufino/gabrielrufino/master`. Remember to preffix the endpoint using that base URL.

Let's make the request using `curl`:

**Request:**
```bash
$ BASE_URL="https://raw.githubusercontent.com/gabrielrufino/gabrielrufino/master"
$ curl $BASE_URL/api/infos/general \
    -H "Accept: application/json"
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

### Endpoints

| Method | Endpoint             | Description                                                      |
| ------ | -------------------- | ---------------------------------------------------------------- |
| GET    | `/api/infos/general` | Returns general information about me                             |
| GET    | `/api/infos/stack`   | Returns the list of technologies that I work with                |
| GET    | `/api/infos/hobbies` | Returns the list of things I love to do when I'm not programming |
| GET    | `/api/infos/contact` | Returns the list of ways you can talk to me                      |

---

<p align="center">
  <a href="https://www.linkedin.com/in/gabrielrufinojs" target="_blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@6.21.0/icons/linkedin.svg" height="20" width="20" /></a>
  <a href="https://hashnode.com/@gabrielrufino" target="_blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@6.21.0/icons/hashnode.svg" height="20" width="20" /></a>
  <a href="https://t.me/gabrielrufino" target="_blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@6.21.0/icons/telegram.svg" height="20" width="20" /></a>
</p>
