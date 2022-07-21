# API gold oil lotto
สามารถ สนับสนุน ได้ที่ 0983437435 กสิกรไทย 

ชื่อ บัญชี ด.ช ปฏิภาณ ศรีเอี่ยมกุล
# gold
http://103.141.68.98:8000/gold
# โค้ดสำหรับดึงรายการภาษา PHP
```php
$curl = curl_init();
curl_setopt_array($curl, array(
  CURLOPT_URL => 'http://103.141.68.98:8000/gold',
  CURLOPT_RETURNTRANSFER => true,
  CURLOPT_ENCODING => '',
  CURLOPT_MAXREDIRS => 10,
  CURLOPT_TIMEOUT => 0,
  CURLOPT_FOLLOWLOCATION => true,
  CURLOPT_HTTP_VERSION => CURL_HTTP_VERSION_1_1,
  CURLOPT_CUSTOMREQUEST => 'GET',
));
$response = curl_exec($curl);
curl_close($curl);
echo $response;
```
# Response
```javascript
{
  "status": "success",
  "Develop by": "Patiphan Srieamkul",
  "response": {
    "date": "ปรับราคาเมื่อ xx x.x. xx (xx:xx น.)",
    "endpoint": "https://www.sanook.com/money/goldrate/",
    "details": [
      {
        "name": "ทองคำแท่ง",
        "details": "ความบริสุทธิ์ทองคำ 96.5%",
        "purchase_price": "xx,xxx.xx",
        "selling_price": "xx,xxx.xx"
      },
      {
        "name": "ทองรูปพรรณ",
        "details": "ความบริสุทธิ์ทองคำ 96.5%",
        "purchase_price": "xx,xxx.xx",
        "selling_price": "xx,xxx.xx"
      }
    ]
  }
}
```

# oil
http://103.141.68.98:8000/oil
```php
$curl = curl_init();
curl_setopt_array($curl, array(
  CURLOPT_URL => 'http://103.141.68.98:8000/oil',
  CURLOPT_RETURNTRANSFER => true,
  CURLOPT_ENCODING => '',
  CURLOPT_MAXREDIRS => 10,
  CURLOPT_TIMEOUT => 0,
  CURLOPT_FOLLOWLOCATION => true,
  CURLOPT_HTTP_VERSION => CURL_HTTP_VERSION_1_1,
  CURLOPT_CUSTOMREQUEST => 'GET',
));
$response = curl_exec($curl);
curl_close($curl);
echo $response;
```
# Response
```javascript
{
  "status": "success",
  "Develop by": "Patiphan Srieamkul",
  "response": {
    "date": "xx x.x. xx",
    "endpoint": "https://www.sanook.com/money/oil-price/",
    "details": [
      {
        "name": "แก๊สโซฮอล์ 95",
        "price": "xx.xx",
        "image": "https://s.isanook.com/sr/0/images/money/oil/gasohol_95.png"
      },
      {
        "name": "แก๊สโซฮอล์ 91",
        "price": "xx.xx",
        "image": "https://s.isanook.com/sr/0/images/money/oil/gasohol_91.png"
      },
      {
        "name": "แก๊สโซฮอล์ E20",
        "price": "xx.xx",
        "image": "https://s.isanook.com/sr/0/images/money/oil/gasohol_E20.png"
      },
      {
        "name": "แก๊สโซฮอล์ E85",
        "price": "xx.xx",
        "image": "https://s.isanook.com/sr/0/images/money/oil/e85plus.png"
      },
      {
        "name": "ดีเซลพรีเมี่ยม",
        "price": "xx.xx",
        "image": "https://s.isanook.com/sr/0/images/money/oilhyforce_diesel.png"
      },
      {
        "name": "ดีเซล B7",
        "price": "xx.xx",
        "image": "https://s.isanook.com/sr/0/images/money/oil/delta.png"
      }
    ]
  }
}
```

# lotto
http://103.141.68.98:8000/lotto
```php
$curl = curl_init();
curl_setopt_array($curl, array(
  CURLOPT_URL => 'http://103.141.68.98:8000/lotto',
  CURLOPT_RETURNTRANSFER => true,
  CURLOPT_ENCODING => '',
  CURLOPT_MAXREDIRS => 10,
  CURLOPT_TIMEOUT => 0,
  CURLOPT_FOLLOWLOCATION => true,
  CURLOPT_HTTP_VERSION => CURL_HTTP_VERSION_1_1,
  CURLOPT_CUSTOMREQUEST => 'GET',
));
$response = curl_exec($curl);
curl_close($curl);
echo $response;
```
# Response
```javascript
{
  "status": "success",
  "Develop by": "Patiphan Srieamkul",
  "response": {
    "date": "xx xx xxxx",
    "endpoint": "https://news.sanook.com/lotto/",
    "prizes": [
      {
        "id": "prizeFirst",
        "name": "รางวัลที่ 1",
        "reward": "6000000",
        "amount": 1,
        "number": [
          "xxxxxx"
        ]
      },
      {
        "id": "runningNumberFrontThree",
        "name": "รางวัลเลขหน้า 3 ตัว",
        "reward": "4000",
        "amount": 2,
        "number": [
          "xxx",
          "xxx"
        ]
      },
      {
        "id": "runningNumberBackThree",
        "name": "รางวัลเลขท้าย 3 ตัว",
        "reward": "4000",
        "amount": 2,
        "number": [
          "xxx",
          "xxx"
        ]
      },
      {
        "id": "runningNumberBackTwo",
        "name": "รางวัลเลขท้าย 2 ตัว",
        "reward": "2000",
        "amount": 1,
        "number": [
          "xx"
        ]
      }
    ]
  }
}
```
