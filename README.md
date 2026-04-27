# Team カルテ

🔒 パスワード保護されたチーム育成ダッシュボード。

中身はクライアントサイド AES-GCM-256 で暗号化されています。
- KDF: PBKDF2-SHA256 (200,000 iterations)
- Cipher: AES-GCM-256
- 復号: ブラウザの Web Crypto API
