### Profile
| Parameter | Type   | Format | Description                       |
|-----------|--------|--------|-----------------------------------|
| id        | string | uuid   | Unique identifier for the profile |
| firstName | string | -      | First name of the user            |
| lastName  | string | -      | Last name of the user             |
| phone     | string | -      | Phone number of the user          |
| email     | string | email  | Email address of the user         |
| address   | object | -      | User's address information        |

### Address
| Parameter  | Type   | Format | Description                      |
|------------|--------|--------|----------------------------------|
| street     | string | -      | Street address                   |
| city       | string | -      | City                             |
| country    | string | -      | Country code (ISO 3166, Alpha-2) |
| postalCode | string | -      | Postal code                      |

### Error
| Parameter | Type    | Format | Description        |
|-----------|---------|--------|--------------------|
| code      | integer | int32  | Numeric error code |
| message   | string  | -      | Error message      |
