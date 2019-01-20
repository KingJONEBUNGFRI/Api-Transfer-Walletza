# Original Source Code by maythiwat
- Original template : maythiwat
- Github : https://github.com/maythiwat/WalletAPI //default template

# Url API Transfer by Noxturnix
- Original template : Noxturnix
- Github : https://github.com/Noxturnix/0x02Wallet

## Example Usage
This is an example to Login and Logout
```php
use Maythiwat\walleTransfer;
require_once(__DIR__ . '/TMW.php');
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
- DOWNLOAD DEMO : https://gamexs.xyz/
