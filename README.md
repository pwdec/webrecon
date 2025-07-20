# Recon Web UI Tool

Gelişmiş bir bug bounty recon otomasyon aracıdır. Web arayüzü üzerinden tek domain girdisiyle aşağıdaki işlemleri gerçekleştirir:

## Özellikler

- Subdomain Enumeration (`subfinder`)
- Live Host Detection (`httpx`)
- Port Scan (`naabu`, `nmap`)
- JS File Discovery (`gospider`)
- Parameter Discovery (`arjun`)
- Tech Fingerprinting (`whatweb`)
- Vulnerability Scanning (`nikto`)
- DNS & WHOIS Info
- Google Dork Links
- HTML rapor çıktısı
- Telegram Bildirim Entegrasyonu
- Ayarlar sayfası (Telegram Token ve Chat ID girilebilir)

## Gereksinimler

```bash
pip install flask jinja2
apt install subfinder httpx naabu gospider arjun whatweb nmap nikto whois dnsutils
```

## Kullanım

```bash
python3 app.py
```

Web tarayıcıdan `http://localhost:5000` adresine giderek kullanabilirsiniz.

## Yapım

Hazırlayan: [Bug Bounty Recon Tool by OpenAI ChatGPT]