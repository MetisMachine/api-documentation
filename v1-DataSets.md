# Datasets

## GET `/datasets`
Returns JSON array of Data Set rows.

### Resource URL
_ht<span>tps://</span>dev.argus.metismachine.io/v1/datasets_

### Parameters
Name | Required | Description | Default | Example
| --- | --- | --- | --- | --- |
`limit` | optional | positive number of items to return, after `offset` is processed | 100 | _20_
`offset` | optional | used for pagination, specify the positive number of rows to skip | 0 | _200_
`datasetName` | optional | name of the Dataset, currently mutually exclusive with `modelName` | | _combinedHashingLDA_
`modelName` | optional | name of the model, currently mutually exclusive with `datasetName` | | _targetCreators_

If neither `datasetName` nor `modelName` are provided, `/datasets` will return all records up to the `limit`

### Example Requests
_ht<span>tps://</span>dev.argus.metismachine.io/v1/datasets?limit=10&offset=0&datasetName=combinedHashingLDA_
_ht<span>tps://</span>dev.argus.metismachine.io/v1/datasets?modelName=targetCreators_

### Example Response
```json
[
    {
        "created_on": "2017-06-05T20:09:32.938560Z",
        "id": 21,
        "meta": {
            "datasetName": "targetCreators",
            "modelName": "combinedHashingLDA",
            "version": "1.0"
        },
        "modified_on": "2017-06-05T20:09:32.938560Z"
    }
]
```

## GET `/datasets/:data_set_id/data`
Returns JSON array of Data rows for a given `:data_set_id`

### Resource URL
_ht<span>tps://</span>dev.argus.metismachine.io/v1/datasets/:id/data_

### Parameters
Name | Required | Description | Default | Example
| --- | --- | --- | --- | --- |
`limit` | optional | positive number of items to return, after `offset` is processed | 100 | _20_
`offset` | optional | used for pagination, specify the positive number of rows to skip | 0 | _200_

### Example Request
_ht<span>tps://</span>dev.argus.metismachine.io/v1/datasets/21/data?limit=10&offset=0_

### Example Response
```json
[
    {
        "created_on": "2017-06-05T20:09:32.938560Z",
        "data_set_id": 21,
        "id": 16168,
        "payload": {
            "creatorProb": 1.0,
            "id": 335141638,
            "isCreator": 1,
            "url": "https://twitter.com/intent/user?user_id=335141638"
        }
    },
    {
        "created_on": "2017-06-05T20:09:32.938560Z",
        "data_set_id": 21,
        "id": 16169,
        "payload": {
            "creatorProb": 0.99999917,
            "id": 2156278138,
            "isCreator": 1,
            "url": "https://twitter.com/intent/user?user_id=2156278138"
        }
    },
    {
        "created_on": "2017-06-05T20:09:32.938560Z",
        "data_set_id": 21,
        "id": 16170,
        "payload": {
            "creatorProb": 0.99994457,
            "id": 132774626,
            "url": "https://twitter.com/intent/user?user_id=132774626"
        }
    }
]
```