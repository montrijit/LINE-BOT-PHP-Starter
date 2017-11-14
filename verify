<?php
$access_token = 'EYvtjTVNxno3oZxnPmpMJ4vAuk0GkxoGW0SyHAjp3n/yk5f5M3t47f8jvHz7cJ532cwRF39DKSorq56jxiPzEyAdq63GthDf9FXD4gHll+QpJWiSDxaPo2bKZtM505e6xZtBqnji9ARokzcTiX1JOAdB04t89/1O/w1cDnyilFU=';

$url = 'https://api.line.me/v1/oauth/verify';

$headers = array('Authorization: Bearer ' . $access_token);

$ch = curl_init($url);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
curl_setopt($ch, CURLOPT_HTTPHEADER, $headers);
curl_setopt($ch, CURLOPT_FOLLOWLOCATION, 1);
$result = curl_exec($ch);
curl_close($ch);

echo $result;
