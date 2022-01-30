# version 1.0.0

## Features:

### Search:

#### Request:
```
GET /API4H/1.0.0/search?q={query}&skip=[|0]&limit=[|10]
```

#### Response:
```json
{
  "posts": [
    {
      "title": "foo",
      "description": "bar",
    },
    "...[9 items more]"
  ]
}
```

#### try it:

```sh
curl -X GET https://foo.bar/API4H/1.0.0/search?q=foo
```
