
# Bank Management System
Bank Management System applying the concept of File Handling in C

The Coord structure has been implemented in the program.
Windows header file is included 
the getoxy(a,b) assigns the cursor position at(a,b) on the buffer screen

the data provided on the API is to be stored in a .txt File 

This programming teaches us application of file handling for quick projects in C.



## API Reference

#### Get all items

```http
  GET /api/win32 API
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `a,b`      | `int` | **Required**. Supplies values of X=coord.x and Y= coord.y |

#### getoxy(a,b)

Takes two numbers (a,b) and returns the positon of the cursor on the buffer screen.


## Authors

- https://github.com/RamNarayandatta



## Appendix

Any additional information goes here


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.
