<p align="center"><img src="https://cdn-longterm.mee6.xyz/plugins/welcome/images/993177515893981214/b57e56f6e1d7e53e708fd5dfdd23ff886634c4d5b8d0a0a2c9d0390d98a45d06.png" width="150px" height="150px" alt="aventium softworks"></p>

<h1 align="center">FDL StunLife API</h1>


## API Documentation

#### Page D'information de l'API

```php
  GET /about/
```

| Header | Type     | Infos                |
| :-------- | :------- | :------------------------- |
| `Authorization` | `string` | **Requis**. Votre clé d'api |
> **Warning**
> Votre clé d'api est **UNIQUE**, ne la perdez pas ou vous devrez la regénérer
___

### Page D'informations des utilisateurs enregistrée

```php
  GET /api/get/member?id={:discord_id}
```

| Header | Type     | Infos                |
| :-------- | :------- | :------------------------- |
| `Authorization` | `string` | **Requis**. Votre clé d'api |
> **Warning**
> Votre clé d'api est **UNIQUE**, ne la perdez pas ou vous devrez la regénérer

> **Note**
> S'il l'ID n'est pas enregistré, elle sera crée et stocké pour plus tard 
___
