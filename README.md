# Budget App Models - The Ksquare Group

Reference document for the students of JS Program in The Ksquare Group

## Budget API Models

### Balance

```
GET /v1/balance
```

Example

```interface
{
 balance: number
}
```

### Transaction

```
POST /v1/transaction
```

Example

```interface
{
 balance: number;
 description: string;
}
```

### Transaction

```
POST /v1/clear
```

Example

```interface
{
}
```
