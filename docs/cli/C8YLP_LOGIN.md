
## c8ylp login

```
Validating c8y token: OK
Usage: c8ylp login [OPTIONS]

  Login and save credentials to an environment file

  You will be prompted for all of the relevant information, i.e. host,
  username, password and TFA code (if required)

  Example 1: Create/update an env-file by trying to login into Cumulocity 
  c8ylp login --env-file mytenant.env

Options:
  --host TEXT            Cumulocity Hostname  [required]
  -t, --tenant TEXT      Cumulocity tenant id  [env var: C8Y_TENANT]
  -u, --user TEXT        Cumulocity username  [env var: C8Y_USER,
                         C8Y_USERNAME]
  -t, --token TEXT       Cumulocity token  [env var: C8Y_TOKEN]
  -p, --password TEXT    Cumulocity password  [env var: C8Y_PASSWORD]
  --tfa-code TEXT        TFA Code. Required when the 'TFA enabled' is enabled
                         for a user  [env var: C8Y_TFA_CODE]
  -v, --verbose          Print Debug Information into the Logs and Console
                         when set
  --env-file PATH        Environment file to load. Any settings loaded via
                         this file will control other parameters
  --store-token          Store the Cumulocity host, tenant and token to the
                         env-file if a file is being used
  -d, --disable-prompts
  --help                 Show this message and exit.

```
        