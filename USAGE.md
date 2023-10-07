<!-- Start SDK Example Usage -->


```typescript
import { TestLanguageTags } from "test-language-tags";

(async() => {
  const sdk = new TestLanguageTags();

  const res = await sdk.pets.createPets();

  if (res.statusCode == 200) {
    // handle response
  }
})();
```
<!-- End SDK Example Usage -->