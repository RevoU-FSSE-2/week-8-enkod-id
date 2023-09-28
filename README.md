
# CRUD with node js & typescript

welcome, this is a simple application with typescript, please visit www.week8.enkod.site


## Deployment

To deploy this project run

```bash
  git clone https://github.com/RevoU-FSSE-2/week-8-enkod-id.git
```

```bash
  change directory
```

```bash
  import database mysql
```

```bash
  run application using nodemon index.js
```


## API Reference

#### Get all user

```http
  GET /user
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get user by id

```http
  GET /user/id
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |


