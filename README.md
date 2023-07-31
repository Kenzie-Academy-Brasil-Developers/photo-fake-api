Uma fake API para uma aplicação de fotos

Base URL: https://photo-fake-api.onrender.com/

## ROTAS

### Fotos /photos GET

Padrão de Resposta

```json
[
   {
      "id": 1,
      "img": "https://images.pexels.com/photos/16767210/pexels-photo-16767210/free-photo-of-aventura-facanha-asfalto-garoto.jpeg",
      "bio": "Bio da foto 1"
   },
   {
      "id": 2,
      "img": "https://images.pexels.com/photos/2043590/pexels-photo-2043590.jpeg",
      "bio": "Bio da foto 2"
   },
   {
      "id": 3,
      "img": "https://images.pexels.com/photos/2466756/pexels-photo-2466756.jpeg",
      "bio": "Bio da foto 3"
   },
   {
      "id": 4,
      "img": "https://images.pexels.com/photos/3310694/pexels-photo-3310694.jpeg",
      "bio": "Bio da foto 4"
   },
   {
      "id": 5,
      "img": "https://images.pexels.com/photos/3651597/pexels-photo-3651597.jpeg",
      "bio": "Bio da foto 5"
   }
]
```

### Foto /photos/:id GET

Padrão de Resposta

```json
 {
      "id": 1,
      "img": "https://images.pexels.com/photos/16767210/pexels-photo-16767210/free-photo-of-aventura-facanha-asfalto-garoto.jpeg",
      "bio": "Bio da foto 1"
   },
```
