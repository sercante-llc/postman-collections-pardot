# Sercante's Pardot API Postman collection

Postman Collection demonstrating how to use the [Pardot](https://www.pardot.com/) API.
More information about the API can be found on [developer.pardot.com](https://developer.pardot.com/).

If you need help with the setup, someone to bounce questions off of, or just a second set of eyes, you're in luck: Sercante has helped many companies build integrations into Pardot. [Let's Chat >](https://www.sercante.com/contact-us/)

## Installation

To use the latest published version, click one of the following buttons to import the Pardot API as a collection. Each button sets up a Collection as well as an Environment.

#### Pardot with Salesforce SSO
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/253c060bb4f6ac7263db#?env%5BPardot%20API%20-%20Salesforce%20SSO%5D=W3sia2V5IjoidXNlcm5hbWUiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoicGFzc3dvcmQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5Ijoic2VjdXJpdHlfdG9rZW4iLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiY29uc3VtZXJfaWQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiY29uc3VtZXJfc2VjcmV0IiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6ImJ1c2luZXNzX3VuaXRfaWQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoicGFyZG90X2RvbWFpbiIsInZhbHVlIjoicGkucGFyZG90LmNvbSIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiYXBpX3ZlcnNpb24iLCJ2YWx1ZSI6IjMiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6Im91dHB1dF9mb3JtYXQiLCJ2YWx1ZSI6Impzb24iLCJlbmFibGVkIjp0cnVlfV0=)
#### Pardot Only User
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/c677687dc696d9357d01#?env%5BPardot%20API%20-%20Pardot%20Only%20User%5D=W3sia2V5IjoidXNlcm5hbWUiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoicGFzc3dvcmQiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoidXNlcl9rZXkiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoicGFyZG90X2RvbWFpbiIsInZhbHVlIjoicGkucGFyZG90LmNvbSIsImVuYWJsZWQiOnRydWV9LHsia2V5Ijoib3V0cHV0X2Zvcm1hdCIsInZhbHVlIjoianNvbiIsImVuYWJsZWQiOnRydWV9LHsia2V5IjoiYXBpX3ZlcnNpb24iLCJ2YWx1ZSI6IjMiLCJlbmFibGVkIjp0cnVlfV0=)

You can also download the collection and environment files from this repo, then import directly into Postman.

### Prerequisites

- *Postman* The collection is for use by the Postman app. Postman is a utility that allows you to quickly test and use REST APIs. More information can be found at [getpostman.com](https://www.getpostman.com/).
- *Pardot* To use Pardot's API, you must have access to Pardot with permissions enabled for which resource you want to use.

## Usage

Each collection is designed to ease you into becoming comfortable with using the Pardot API.

Almost all requests require a valid user credentials.  The collection requests have headers setup for this.
This should be set in your [Postman environment](https://www.getpostman.com/docs/v6/postman/environments_and_globals/manage_environments) i.e. outside the collection itself. This should help avoid accidental commits of API keys to repos.

Once imported, manage the Postman environment variables to get going.

#### Pardot with Salesforce SSO

|Variable  |Default value               |Example|
|----------|----------------------------|-------|
|`username` |                            | `apiuser@company.com`      |
|`password`| | `somethingSecureIHope` |
|`security_token`| | `fdse4sdf243sdf354sda345` |
|`consumer_id`| | |
|`consumer_secret`| | |
|`business_unit_id`| | |
|`pardot_domain`| `pi.pardot.com` | `demo.pardot.com` |
|`api_version`| `3` | `4` |
|`output_format`| `json` | `xml` |

#### Pardot Only User Environment Variables

|Variable  |Default value               |Example|
|----------|----------------------------|-------|
|`username` |                            | `apiuser@company.com`      |
|`password`| | `somethingSecureIHope` |
|`user_key`| | `fdse4sdf243sdf354sda345` |
|`pardot_domain`| `pi.pardot.com` | `demo.pardot.com` |
|`api_version`| `3` | `4` |
|`output_format`| `json` | `xml` |

## See Also

[Pardot API documentation](https://developer.pardot.com/)

[Postman API development tool](https://www.getpostman.com/)
