Purpose
=======

Output headers and RAW content body from any POST

Usage
=====

    httpsniff 9999

Sample Output
=============

    "POST / HTTP/1.1" 200 -Host: 127.0.0.1:9999
    Connection: keep-alive
    Content-Length: 648
    Cache-Control: max-age=0
    Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8
    Origin: http://127.0.0.1:9999
    Upgrade-Insecure-Requests: 1
    User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_11_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/48.0.2564.116 Safari/537.36
    Content-Type: multipart/form-data; boundary=----WebKitFormBoundarybCpJRp5UT9C6EIlM
    DNT: 1
    Referer: http://127.0.0.1:9999/
    Accept-Encoding: gzip, deflate
    Accept-Language: en-US,en;q=0.8

    000: 2d 2d 2d 2d 2d 2d 57 65 62 4b 69 74 46 6f 72 6d  |------WebKitForm|
    010: 42 6f 75 6e 64 61 72 79 62 43 70 4a 52 70 35 55  |BoundarybCpJRp5U|
    020: 54 39 43 36 45 49 6c 4d 0d 0a 43 6f 6e 74 65 6e  |T9C6EIlM··Conten|
    030: 74 2d 44 69 73 70 6f 73 69 74 69 6f 6e 3a 20 66  |t-Disposition: f|
    040: 6f 72 6d 2d 64 61 74 61 3b 20 6e 61 6d 65 3d 22  |orm-data; name="|
    050: 66 69 6c 65 22 3b 20 66 69 6c 65 6e 61 6d 65 3d  |file"; filename=|
    060: 22 74 65 73 74 2e 74 78 74 22 0d 0a 43 6f 6e 74  |"test.txt"··Cont|
    070: 65 6e 74 2d 54 79 70 65 3a 20 74 65 78 74 2f 70  |ent-Type: text/p|
    080: 6c 61 69 6e 0d 0a 0d 0a 55 54 46 2d 38 20 65 6e  |lain····UTF-8 en|
    090: 63 6f 64 65 64 20 73 61 6d 70 6c 65 20 66 69 6c  |coded sample fil|
    0A0: 65 20 66 6f 72 20 50 6f 73 74 73 63 72 69 70 74  |e for Postscript|
    0B0: 20 70 6c 61 69 6e 2d 74 65 78 74 20 66 69 6c 65  | plain-text file|
    0C0: 20 66 6f 72 6d 61 74 74 65 72 73 0a 2d 2d 2d 2d  | formatters·----|
    0D0: 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d  |----------------|
    0E0: 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d  |----------------|
    0F0: 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d  |----------------|
    100: 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 2d 0a  |---------------·|
    110: 0a 54 68 65 20 66 6f 6c 6c 6f 77 69 6e 67 20 74  |·The following t|
    120: 61 62 6c 65 20 63 6f 6e 74 61 69 6e 73 20 69 6e  |able contains in|
    130: 20 69 74 73 20 74 68 72 65 65 20 63 6f 6c 75 6d  | its three colum|
    140: 6e 73 0a 20 20 2d 20 74 68 65 20 68 65 78 61 64  |ns·  - the hexad|
    150: 65 63 69 6d 61 6c 20 55 6e 69 63 6f 64 65 20 76  |ecimal Unicode v|
    160: 61 6c 75 65 0a 20 20 2d 20 74 68 65 20 55 6e 69  |alue·  - the Uni|
    170: 63 6f 64 65 20 63 68 61 72 61 63 74 65 72 20 69  |code character i|
    180: 74 73 65 6c 66 20 28 55 54 46 2d 38 20 65 6e 63  |tself (UTF-8 enc|
    190: 6f 64 65 64 29 0a 20 20 2d 20 74 68 65 20 55 6e  |oded)·  - the Un|
    1A0: 69 63 6f 64 65 20 6e 61 6d 65 20 66 6f 72 20 74  |icode name for t|
    1B0: 68 65 20 63 68 61 72 61 63 74 65 72 0a 0a 30 30  |he character··00|
    1C0: 32 30 20 20 20 53 50 41 43 45 0a 30 30 32 31 20  |20   SPACE·0021 |
    1D0: 21 20 45 58 43 4c 41 4d 41 54 49 4f 4e 20 4d 41  |! EXCLAMATION MA|
    1E0: 52 4b 0a 30 30 32 32 20 22 20 51 55 4f 54 41 54  |RK·0022 " QUOTAT|
    1F0: 49 4f 4e 20 4d 41 52 4b 0a 30 30 32 33 20 23 20  |ION MARK·0023 # |
    200: 4e 55 4d 42 45 52 20 53 49 47 4e 0a 30 30 32 34  |NUMBER SIGN·0024|
    210: 20 24 20 44 4f 4c 4c 41 52 20 53 49 47 4e 0a 2e  | $ DOLLAR SIGN·.|
    220: 2e 2e 0a 32 30 32 30 20 e2 80 a0 20 44 41 47 47  |..·2020 ··· DAGG|
    230: 45 52 0a 32 30 32 31 20 e2 80 a1 20 44 4f 55 42  |ER·2021 ··· DOUB|
    240: 4c 45 20 44 41 47 47 45 52 0a 32 30 32 32 20 e2  |LE DAGGER·2022 ·|
    250: 80 a2 20 42 55 4c 4c 45 54 0a 0d 0a 2d 2d 2d 2d  |·· BULLET···----|
    260: 2d 2d 57 65 62 4b 69 74 46 6f 72 6d 42 6f 75 6e  |--WebKitFormBoun|
    270: 64 61 72 79 62 43 70 4a 52 70 35 55 54 39 43 36  |darybCpJRp5UT9C6|
    280: 45 49 6c 4d 2d 2d 0d 0a                          |EIlM--··        |