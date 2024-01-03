# Minimal_API_DoYo
Minimal Web API for JWT Authentication in ASP.NET Core Web API.

What is JSON Web Token (JWT)?

JSON Web Token (JWT) is a secure and compact way of transmitting information between parties as a JSON object. It consists of three parts: header, payload, and signature. The header contains the algorithm used to sign the token, the payload contains the claims, and the signature is used to verify the authenticity of the token. JWTs are commonly used for authentication and authorization purposes in web applications.

Compared to other token formats, JWT has several benefits:

Compactness: JWT is a compact format that can be easily transmitted over the network.

Self-contained: JWT contains all the necessary information within itself, which means that it does not require any additional lookup to validate the token.

Security: JWT can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA. This makes JWTs secure and tamper-proof.

Ease of use: JWT is easy to use and can be integrated with various programming languages and frameworks.
