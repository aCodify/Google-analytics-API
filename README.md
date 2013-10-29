## Exp

Setting

	include_once('gaapi.class.php');
	$ga=new gaApi('google username','google password','ga:site id');
	//e.g. ('myname@gmail.com','myPassword','ga:1234567');


ค่าของ `site id` สามารถดูได้จาก 

1 เข้าเว็บ www.google.com/analytics ทำการ  login และเลือก web site ที่เราต้องการดึง

2 กดเมนูทางด้านขวามือ ที่เขียนว่า `การจัดการ`

3 เลือก `ดูการตั้งค่า`

![img](https://lh6.googleusercontent.com/nGNrZqCXsCMByp25EFMcexl186c1SLTgMmFc54Jm_FqrlrXhz0EA8KrswIR_-y82SQ=w1180-h790)


นำตัวเลข `รหัสข้อมูลพร็อพเพอร์ตี้`

มาใส่ใน ga: ....


