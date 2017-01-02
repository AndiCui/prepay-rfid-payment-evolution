- `/transactions/new`

Creates a new transaction.
  
Parameters:

1. `userId`
2. `amount`
3. `terminalId`

Returns:

    {
        "err": 0,
        "msg": "OK",
        "transactionId": "187d9698-5923-42d1-a64a-ea8e52168b1b"
    }

- `/transactions/cancel`

Cancels a transaction.

Parameters:

1. `transactionId`

Returns:

    {
        "err": 0,
        "msg": "OK"
    }
