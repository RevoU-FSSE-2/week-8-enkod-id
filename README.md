
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
  run application using nodemon app.js
```


## API Reference

#### Get all movies

```http
  GET /movies
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get movies by id

```http
  GET /movies/id
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |


#### POST insert movies 
```http
  POST /movies/
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |


#### PUT update movies 
```http
  PUT /movies/id
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |


#### PUT delete movies 
```http
  DELETE /movies/id
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |


