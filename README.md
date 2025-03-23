# Kriptografi Çalışma Dökümanı

## Konu Başlıkları

1. Kriptografinin Temel Kavramları
2. Simetrik Anahtar Kriptografisi
3. Asimetrik Anahtar Kriptografisi
4. Kriptografik Hash Fonksiyonları
5. Dijital İmzalar
6. Anahtar Değişim Protokolleri
7. Sertifika ve Güven Zinciri
8. AES Şifreleme Modları

## Alt Başlıklar

### 1. Kriptografinin Temel Kavramları
- Kriptografinin Tanımı
- Kriptografinin Tarihi
- Kriptografinin Önemi

### 2. Simetrik Anahtar Kriptografisi
- Simetrik Anahtar Nedir?
- Simetrik Anahtar Algoritmaları
  - DES
  - AES

### 3. Asimetrik Anahtar Kriptografisi
- Asimetrik Anahtar Nedir?
- Asimetrik Anahtar Algoritmaları
  - RSA
  - DSA

### 4. Kriptografik Hash Fonksiyonları
- Hash Fonksiyonlarının Tanımı
- MD5, SHA-1, SHA-256

### 5. Dijital İmzalar
- Dijital İmzanın Tanımı
- Dijital İmza Algoritmaları

### 6. Anahtar Değişim Protokolleri
- Diffie-Hellman Anahtar Değişim Protokolü
- Güvenli Anahtar Değişiminin Önemi

### 7. Sertifika ve Güven Zinciri
- Dijital Sertifikaların Tanımı
- Güven Zinciri ve Sertifika Otoriteleri

### 8. AES Şifreleme Modları
- AES Algoritmasının Tanımı
- AES Şifreleme Modları
  - ECB (Electronic Codebook)
  - CBC (Cipher Block Chaining)
  - CTR (Counter)
  - GCM (Galois/Counter Mode)

## Özet

### 1. Kriptografinin Temel Kavramları
Kriptografi, bilgilerin gizlilik, bütünlük ve doğruluk gibi güvenlik özelliklerini sağlamak amacıyla matematiksel teknikler kullanarak şifrelenmesi ve şifresinin çözülmesi bilimidir. Tarih boyunca savaşlarda ve diplomatik yazışmalarda kullanılmıştır.

### 2. Simetrik Anahtar Kriptografisi
Simetrik anahtar kriptografi, aynı anahtarın hem şifreleme hem de şifre çözme için kullanıldığı bir yöntemdir. DES ve AES en bilinen simetrik anahtar algoritmalarıdır.

### 3. Asimetrik Anahtar Kriptografisi
Asimetrik anahtar kriptografi, iki farklı anahtarın kullanıldığı bir yöntemdir. RSA ve DSA gibi algoritmalar asimetrik kriptografiye örnektir.

### 4. Kriptografik Hash Fonksiyonları
Hash fonksiyonları, verileri sabit uzunlukta özet değerlerine dönüştüren matematiksel fonksiyonlardır. MD5, SHA-1 ve SHA-256 en bilinen hash fonksiyonlarıdır.

### 5. Dijital İmzalar
Dijital imzalar, bir mesajın veya belgenin doğruluğunu ve bütünlüğünü garanti eden kriptografik tekniklerdir. Dijital imza algoritmaları arasında RSA ve DSA bulunur.

### 6. Anahtar Değişim Protokolleri
Anahtar değişim protokolleri, iki tarafın güvenli bir şekilde kriptografik anahtarlar değiş tokuş etmesini sağlar. Diffie-Hellman protokolü en bilinen örneklerdendir.

### 7. Sertifika ve Güven Zinciri
Dijital sertifikalar, bir kullanıcının veya cihazın kimliğini doğrulayan dijital belgelerdir. Güven zinciri, sertifika otoriteleri tarafından oluşturulan ve dijital sertifikaların güvenilirliğini sağlayan yapıdır.

### 8. AES Şifreleme Modları
AES (Advanced Encryption Standard), simetrik bir şifreleme algoritmasıdır ve çeşitli şifreleme modları ile kullanılabilir:
- **ECB (Electronic Codebook)**: Her blok bağımsız olarak şifrelenir.
- **CBC (Cipher Block Chaining)**: Her blok, bir önceki şifreli blok ile XOR işlemine tabi tutulur.
- **CTR (Counter)**: Her blok, bir sayaç değeri ile birlikte şifrelenir.
- **GCM (Galois/Counter Mode)**: CTR moduna ek olarak veri bütünlüğü sağlamak için Galois alanı kullanılır.

## Önemli Kavramlar ve Tanımlar

- **Kriptografi**: Bilgilerin güvenliğini sağlamak için kullanılan matematiksel teknikler.
- **Şifreleme**: Bilgilerin anlaşılmaz hale getirilmesi işlemi.
- **Şifre Çözme**: Şifrelenmiş bilgilerin orijinal haline döndürülmesi işlemi.
- **Anahtar Yönetimi**: Kriptografik anahtarların oluşturulması, saklanması ve dağıtılması süreci.
- **Simetrik Anahtar**: Aynı anahtarın şifreleme ve şifre çözme için kullanıldığı kriptografik yöntem.
- **Asimetrik Anahtar**: Farklı anahtarların (açık ve gizli anahtar) şifreleme ve şifre çözme için kullanıldığı yöntem.
- **Hash Fonksiyonu**: Verileri sabit uzunlukta özet değerlerine dönüştüren fonksiyon.
- **Dijital İmza**: Bir mesajın veya belgenin doğruluğunu ve bütünlüğünü garanti eden kriptografik teknik.
- **Anahtar Değişim Protokolü**: İki tarafın güvenli bir şekilde kriptografik anahtarlar değiş tokuş etmesini sağlayan protokol.
- **Dijital Sertifika**: Bir kullanıcının veya cihazın kimliğini doğrulayan dijital belge.
- **Güven Zinciri**: Sertifika otoriteleri tarafından oluşturulan ve dijital sertifikaların güvenilirliğini sağlayan yapı.
- **ECB (Electronic Codebook)**: Her blok bağımsız olarak şifrelenir.
- **CBC (Cipher Block Chaining)**: Her blok, bir önceki şifreli blok ile XOR işlemine tabi tutulur.
- **CTR (Counter)**: Her blok, bir sayaç değeri ile birlikte şifrelenir.
- **GCM (Galois/Counter Mode)**: CTR moduna ek olarak veri bütünlüğü sağlamak için Galois alanı kullanılır.

## Formüller ve Algoritmalar

### DES (Data Encryption Standard) Algoritması
- **Şifreleme**: `C = E(K, P)`
- **Şifre Çözme**: `P = D(K, C)`

### RSA Algoritması
- **Şifreleme**: `C = M^e mod n`
- **Şifre Çözme**: `M = C^d mod n`

### SHA-256 Hash Fonksiyonu
- **Hash Hesaplama**: `H = SHA-256(M)`

### Diffie-Hellman Anahtar Değişim Protokolü
- **Anahtar Hesaplama**: `A = g^a mod p` ve `B = g^b mod p`

## Örnekler

### Simetrik Anahtar Kriptografi Örneği
- **DES ile Şifreleme**: `C = E(K, "HELLO")`
- **DES ile Şifre Çözme**: `P = D(K, C)`

### Asimetrik Anahtar Kriptografi Örneği
- **RSA ile Şifreleme**: `C = "HELLO"^e mod n`
- **RSA ile İmza Doğrulama**: `M = S^e mod n`

### Hash Fonksiyonu Örneği
- **SHA-256 ile Hash Hesaplama**: `H = SHA-256("HELLO")`

### Dijital İmza Örneği
- **RSA ile Dijital İmza**: `S = M^d mod n`
- **RSA ile İmza Doğrulama**: `M = S^e mod n`

### Anahtar Değişim Örneği
- **Diffie-Hellman Anahtar Değişimi**: `A = g^a mod p`, `B = g^b mod p`
