1.请求地址: host -> http://www.e-mxing.com
2.所以请求头部加token字段，token值为用户登录注册后返回值，默认值0

{'host': 'openapi.aligenie.com', 'x-acs-version': 'iap_1.0', 'x-acs-action': 'CheckThirdRightSendPlan', 'user-agent': 'AlibabaCloud (Windows; AMD64) Python/3.11.3 Core/0.3.6 TeaDSL/1', 'x-acs-date': '2024-04-18T02:37:27Z', 'x-acs-signature-nonce': 'a30dafeac9a121e7acaa8e7d3b48de5c', 'accept': 'application/json', 'x-acs-content-sha256': 'e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855', 'Authorization': 'ACS3-HMAC-SHA256 Credential=826540ac925d5d1ba48ff528ad5381ef,SignedHeaders=accept;host;user-agent;x-acs-action;x-acs-content-sha256;x-acs-date;x-acs-signature-nonce;x-acs-version,Signature=9dc427a4b2d5c31a87a30be0700d7962886070bb00c1ff3519b32002f204723e'}
