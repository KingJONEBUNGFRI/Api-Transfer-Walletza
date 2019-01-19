# Original Source Code by maythiwat
original template : maythiwat
github : https://github.com/maythiwat/WalletAPI //default template

## Example Usage
This is an example to Login and Logout
```php
use Maythiwat\walleTransfer;
require_once(__DIR__ . '/WalletAPI.php');
$transfer = new walleTransfer();

// Login with Email & Password
$token = $transfer->GetToken('example@example.com', 'password');

// Login with Phone & PIN
$token = $transfer->GetToken('0911111111', '1234', 'phone');

// Logout
$transfer->Logout($token);
```

## โดเนท
คุณสามารถโดเนทได้ที่ 
- Truemoneywallet [ 0917631018 ]
