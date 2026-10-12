EVOLERA FARMER - bot di browser (Vercel, gratis)
================================================

CARA DEPLOY (2 menit)
1. Buka https://vercel.com/new  (login pakai GitHub/Google/email, gratis)
2. Drag & drop FOLDER ini ke halaman itu
3. Klik Deploy -> dapat link https://<nama>.vercel.app
4. Buka link-nya, tempel private key, pilih wallet, klik Start

ISI FOLDER (cuma 2 file)
  index.html          - seluruh bot (login SIWE + farming loop)
  ethers.umd.min.js   - buat tanda tangan login (localhost, nggak keluar)

CATATAN
- Jalanin HANYA dari laptop/IP rumah. 1 wallet per IP, jangan 2 tab 2 wallet.
- Private key cuma masuk localStorage laptop kamu. Halaman ini nggak punya server/backend,
  jadi nggak ada yang dikirim selain tanda tangan login ke evolera.world.
- colyseus.js diambil dari CDN (jsdelivr, fallback esm.sh + skypack). Butuh internet.
- Wallet harus pegang >= 5.000 EVO buat lolos gate. Wallet 1 udah punya 21.600 EVO.
- Rate sekarang 15 EVO/gold. 500 gold = 7.500 EVO.
