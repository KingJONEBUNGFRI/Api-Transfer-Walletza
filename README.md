# Original Source Code by maythiwat

Example. !

use Maythiwat\walleTransfer;
require_once('TMW.php');
$tw = new walleTransfer();

// Login with Email & Password
$token = $tw->GetToken('email@provider.com', 'your_p@ssw0rd');

// Login with Phone & PIN
$token = $tw->GetToken('0698765432', '1234', 'phone');

// Logout
$tw->Logout($token);

อื่นๆอัพเดททีหลัง #DONATION : 091-763-1018 TruemoneyWallet
