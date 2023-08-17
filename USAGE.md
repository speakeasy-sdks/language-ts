<!-- Start SDK Example Usage -->


```typescript
import { TestLanguageTags } from "test-language-tags";
import { CreatePetsResponse } from "test-language-tags/dist/sdk/models/operations";

const sdk = new TestLanguageTags();

sdk.pets.createPets().then((res: CreatePetsResponse) => {
  if (res.statusCode == 200) {
    // handle response
  }
});
```
<!-- End SDK Example Usage -->