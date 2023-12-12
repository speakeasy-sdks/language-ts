<!-- Start SDK Example Usage [usage] -->
```typescript
import { TestLanguageTags } from "test-language-tags";

async function run() {
    const sdk = new TestLanguageTags();

    const res = await sdk.pets.createPets();

    if (res.statusCode == 200) {
        // handle response
    }
}

run();

```
<!-- End SDK Example Usage [usage] -->