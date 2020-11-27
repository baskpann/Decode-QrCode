# Decode-QrCode
This is used to decrypt a JWT token which is encoded in the form of QR code.
# Algorithms Used
RS256
# JWT
### [jwt.io](https://www.jwt.io)
JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed.
# Why JWT
JSON Web Tokens(JWT) for securely transmitting the information. This information can be verified and trusted because it is digitally signed using a public/private key pair.
# Usage
This QrCode Decoder is only to decode the QRCode generated by **Aarogya Setu** app. The **public key** used to verify the signature of the JWT is available in **decrypt_jwt.py**
# How to run 
The following are the commands
```
git clone https://github.com/baskpann/Decode-QrCode.git
cd path_to/Decode-QrCode.git
pip install -r requirements.txt
python decode_webcam.py
```
