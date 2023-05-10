# Open Charge Point Protocol (OCPP) v1.6 type declarations

This package provides TypeScript type declarations for the OCPP (Open Charge Point Protocol) version 1.6. It includes type definitions for all OCPP message types and their properties.

## Installation

```bash
npm install --save @types/ocpp
```

## Usage

Once installed, you can import the provided type definitions into your TypeScript project:

```typescript
import { OCPPMessage, StatusNotificationRequest } from '@types/ocpp';

// Use the types in your code
const message: OCPPMessage = {
    // ...
};

const statusRequest: StatusNotificationRequest = {
    // ...
};
```

## Contributing

Contributions are welcome! If you find any issues or would like to add new features or improvements, please open an issue or submit a pull request on the GitHub repository.

## License
This package is licensed under the MIT License.