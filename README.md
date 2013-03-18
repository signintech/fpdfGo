fpdfGo
======

This is a fork of [FPDF](http://www.fpdf.org/) Library for generate font file to use with gopdf


------

fork มาจาก FPDF เพื่อสำหรับ makefont ให้กับ gopdf



# Usages

```php
	require('makefont/makefont.php');

	MakeGoFont('THSarabunNew','/var/www/fpdf17/ttf/THSarabunNew.ttf','cp874',true);
	MakeGoFont('THSarabunNewBold','/var/www/fpdf17/ttf/THSarabunNew Bold.ttf','cp874',true);
```

