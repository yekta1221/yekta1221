- 👋 Hi, I’m @yekta1221
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
yekta1221/yekta1221 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
int ledPin = 13;  // LED'in bağlı olduğu pin

void setup() {
  pinMode(ledPin, OUTPUT);  // LED pinini çıkış olarak ayarla
}

void loop() {
  digitalWrite(ledPin, HIGH);   // LED'i aç
  delay(1000);                   // 1 saniye bekle
  digitalWrite(ledPin, LOW);    // LED'i kapat
  delay(1000);                   // 1 saniye bekle
}
