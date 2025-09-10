# CYBER_FLAY_TOOLS

Tools OSINT + Utilities by **CYBER FLAY**  
Final checked for bash compatibility and syntax. Do not modify features — only fixes for bash-run compatibility applied (shebang at top, escaped redirection-like arrows).

## Cara Pakai di Termux

```bash
pkg update && pkg upgrade -y
pkg install git curl wget bc openssl dnsutils -y
git clone https://github.com/FLAY511/CYBER_FLAY_TOOLS.git
cd CYBER_FLAY_TOOLS
chmod +x CYBER_FLAY_TOOLS.sh
./CYBER_FLAY_TOOLS.sh
```

## Catatan
- Pastikan menjalankan `./CYBER_FLAY_TOOLS.sh` atau `bash CYBER_FLAY_TOOLS.sh`, jangan `sh`.
- Beberapa fitur bergantung pada paket eksternal/API yang mungkin memiliki rate limit.
- Penggunaan untuk pembelajaran dan testing dengan izin saja.
