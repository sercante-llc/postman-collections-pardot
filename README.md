# Sercante's Pardot API Postman collection

Postman Collection demonstrating how to use the [Pardot](https://www.pardot.com/) API.
More information about the API can be found on [developer.pardot.com](https://developer.pardot.com/).

If you need help with the setup, someone to bounce questions off of, or just a second set of eyes, you're in luck: Sercante has helped many companies build integrations into Pardot. [Let's Chat >](https://www.sercante.com/contact-us/)

## Installation

To use the latest published version, click the following button to import the Pardot API as a collection. It will set up a Collection as well as an Environment.

[![Run in Postman](https://run.pstmn.io/button.svg)](https://go.sercante.com/postman-collection/pardot-salesforce-sso)

You can also download the collection and environment files from this repo, then import directly into Postman.

### Prerequisites

- *Postman* The collection is for use by the Postman app. Postman is a utility that allows you to quickly test and use REST APIs. More information can be found at [getpostman.com](https://www.getpostman.com/).
- *Pardot* To use Pardot's API, you must have access to Pardot with permissions enabled for which resource you want to use.
- Salesforce Connected App and User - You need to be able to authenticate via Salesforce. This postman collection works best with a Connected App set up for Username/Password flow, however for Production code you should look at another flow which is more secure (such as JWT Bearer or Web Server flows)

## Usage

The collection is designed to ease you into becoming comfortable with using the Pardot API.

Almost all requests require a valid user credentials.  The collection requests have headers setup for this.
This should be set in your [Postman environment](https://www.getpostman.com/docs/v6/postman/environments_and_globals/manage_environments) i.e. outside the collection itself. This should help avoid accidental commits of API keys to repos.

Once imported, manage the Postman environment variables to get going.

#### Environment Variables

**Note:** - This Collection uses the Salesforce Username/Password OAuth flow, which is good for browsing around and **not** great for Production-grade code.

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
|`output_format`| `json` | `xml` or `json` |

## See Also

[Pardot API documentation](https://developer.pardot.com/)

[Postman API development tool](https://www.getpostman.com/)
