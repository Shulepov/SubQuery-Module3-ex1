
# Code to run

```shell
query{
  transfers(first: 3){
    nodes{
      id
      amount
      blockNumber
      to{
        id
      }
      }
    }
  }
```

# Result

```json
{
  "data": {
    "transfers": {
      "nodes": [
        {
          "id": "645657-4",
          "amount": "102000000000000000",
          "blockNumber": "645657",
          "to": {
            "id": "13SkL2uACPqBzpKBh3d2n5msYNFB2QapA5vEDeKeLjG2LS3Y"
          }
        },
        {
          "id": "645697-3",
          "amount": "99000000000000000",
          "blockNumber": "645697",
          "to": {
            "id": "13SkL2uACPqBzpKBh3d2n5msYNFB2QapA5vEDeKeLjG2LS3Y"
          }
        },
        {
          "id": "303284-59",
          "amount": "90000000000000000",
          "blockNumber": "303284",
          "to": {
            "id": "1vTfju3zruADh7sbBznxWCpircNp9ErzJaPQZKyrUknApRu"
          }
        },
        {
          "id": "303284-65",
          "amount": "85936000000000000",
          "blockNumber": "303284",
          "to": {
            "id": "14Xs22PogFVE4nfPmsRFhmnqX3RqdrUANZRaVJU7Hik8DArR"
          }
        },
        {
          "id": "303284-71",
          "amount": "80000000000000000",
          "blockNumber": "303284",
          "to": {
            "id": "14AoK8VSrHFxZijXhZGSUipHzZbUgo2AkmEaviD9yxTb1ScX"
          }
        }
      ]
    }
  }
}
```