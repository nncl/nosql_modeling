
```json
{
    "users_quiz" : {
        "email" : "",
        "password" : "",
        "cpf" : "",
        "birth" : "",

        "phone" : [
            "5511952053515",
            "5511952053515",
            "5511952053515",
        ],

        "address" : {
            "street" : "",
            "number" : "",
            "neighborhood" : "",
            "city" : "",
            "state" : "",
            "country" : "",
            "zipcode" : "",
        },

        "accept_regulation" : [
            {
                "quiz_id" : 1,
                "status"  : false
            },
            {
                "quiz_id" : 2,
                "status"  : true
            },
        ]
    }
}
```
**Obs**:

- USERS_QUIZ n:n PHONE
- The questions matters

## References

- [NOMADEV I](http://nomadev.com.br/mongodb-como-mudar-seu-jeito-relacional-de-pensar/)
- [NOMADEV II](http://nomadev.com.br/mongodb-como-mudar-seu-jeito-relacional-de-pensar-parte-2/)
