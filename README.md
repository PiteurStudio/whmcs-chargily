# Chargily Payment Module for WHMCS (Archived)

This module is deprecated as Chargily has moved to v2 API. The v1 API is no longer supported, and users are encouraged to switch to the official module for the v2 API.

Please visit the official repository for the latest version: [https://github.com/Chargily/chargily-pay-whmcs](https://github.com/Chargily/chargily-pay-whmcs)

**Note:** This repository is archived and is no longer maintained.

--------------

## Chargily payment module for WHMCS

![chargily-activate](https://github.com/n4ss1m/chargily-whmcs/assets/1750845/6511657e-82df-4177-ae1c-7ddaf35ce45b)


Chargily Pay ™ support the most popular payment methods in Algeria and around the world: The CIB Banking Card, EDAHABIA.

### Installation

Copy modules folder into your whmcs root installation

```
 modules/gateways/
  |- callback/chargily.php
  |- chargily/generate_link.php
  |- chargily/whmcs.json
  |- chargily/logo.png
  |  chargily.php
```


### Activate

First you need to Create an account on <a target='_BLANC' href='https://pay.chargily.com/register'>Chargily</a>.
- Then go to <a href='https://pay.chargily.com/secure/admin/epay-api'>API Integration</a> and Generate API Key.

On your WHMCS Admin

-  Go to Apps > Search for "Chargily" > Click on Activate.

![chargily-activate](https://github.com/n4ss1m/chargily-whmcs/assets/1750845/86b07dc7-2a38-4fec-8aab-585dda72d3d4)


- Add your API keys and save settings.

![chargily-activated](https://github.com/n4ss1m/chargily-whmcs/assets/1750845/649d8dcb-c641-4b67-97e0-3527a65a3cc6)

Now it's active and work your clients can pay you using CIB / EDAHABIA




### Contributing

Pull requests are welcome.


### License

[MIT](https://choosealicense.com/licenses/mit/)
