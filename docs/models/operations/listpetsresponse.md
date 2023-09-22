# ListPetsResponse


## Fields

| Field                                                   | Type                                                    | Required                                                | Description                                             |
| ------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------- |
| `contentType`                                           | *string*                                                | :heavy_check_mark:                                      | N/A                                                     |
| `error`                                                 | [shared.ErrorT](../../models/shared/errort.md)          | :heavy_minus_sign:                                      | unexpected error                                        |
| `headers`                                               | Record<string, *string*[]>                              | :heavy_minus_sign:                                      | N/A                                                     |
| `pets`                                                  | [shared.Pet](../../models/shared/pet.md)[]              | :heavy_minus_sign:                                      | A paged array of pets                                   |
| `statusCode`                                            | *number*                                                | :heavy_check_mark:                                      | N/A                                                     |
| `rawResponse`                                           | [AxiosResponse](https://axios-http.com/docs/res_schema) | :heavy_minus_sign:                                      | N/A                                                     |