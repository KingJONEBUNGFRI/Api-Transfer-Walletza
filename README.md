# Original Source Code by maythiwat

## Example Usage
This is an example to Login and Logout
```php
use Maythiwat\walleTransfer;
require_once(__DIR__ . '/WalletAPI.php');
$tw = new walleTransfer();

// Login with Email & Password
$token = $tw->GetToken('email@provider.com', 'your_p@ssw0rd');

// Login with Phone & PIN
$token = $tw->GetToken('0698765432', '1234', 'phone');

// Logout
$tw->Logout($token);
```

## โดเนท
คุณสามารถโดเนทได้ที่ 
- Truemoneywallet [ 0917631018 ]
