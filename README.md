# zio-world-conference-constraintless


## Configuration Details


|FieldName|Format                     |Description|Sources|
|---      |---                        |---        |---    |
|         |[all-of](fielddescriptions)|           |       |

### Field Descriptions

|FieldName                       |Format                      |Description        |Sources|
|---                             |---                         |---                |---    |
|[authentication](authentication)|[any-one-of](authentication)|                   |       |
|region                          |primitive                   |a text property    |       |
|port                            |primitive                   |an integer property|       |
|host                            |primitive                   |a text property    |       |

### authentication

|FieldName                 |Format               |Description|Sources|
|---                       |---                  |---        |---    |
|[Credentials](credentials)|[all-of](credentials)|           |       |
|[Token](token)            |[nested](token)      |           |       |

### Credentials

|FieldName|Format   |Description    |Sources|
|---      |---      |---            |---    |
|username |primitive|a text property|       |
|password |primitive|a text property|       |

### Token

|FieldName|Format   |Description    |Sources|
|---      |---      |---            |---    |
|value    |primitive|a text property|       |
