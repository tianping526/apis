# apis
The API collection defined by Protocol Buffers

## Project Structure

```
.
├── api  // API&Error Proto files
│   └── foo // API collection
│     └── bar // API collection
│       └── service // API collection
│         └── v1 // API version
│           ├── damo.proto // API definition
│           └── damo_error.proto // Error definition
```

## API Collection

- [eventbridge.service.v1](./api/eventbridge/service/v1/README.md)
- [eventbridge.dispatcher.v1](api/eventbridge/dispatcher/v1/README.md)

### OpenAPI

- [openapi.yaml](openapi.yaml)
