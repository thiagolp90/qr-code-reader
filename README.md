### PHP QR Decoder 
> this package is a fork of `zxing/qr-reader` to fix a bug when reading file using GD

### How to install
`composer require thiagolp90/qr-reader`

### How to use
```
include __DIR__.'/vendor/autoload.php';

$qrcode = new \Zxing\QrReader('./qr.png');  //Image path
$text = $qrcode->text(); //Return text 
echo $text;
```

### Requirements
```
PHP >= 5.3
GD Library
```
