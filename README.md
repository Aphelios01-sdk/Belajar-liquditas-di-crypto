# Belajar-liquditas-di-crypto
Perhitungan likuiditas token biasanya melibatkan pemahaman tentang jumlah token yang tersedia (total supply) dan bagaimana token tersebut didistribusikan atau digunakan dalam ekosistem. Namun, secara spesifik, likuiditas sering kali dihitung dalam konteks pasar, seperti dalam penyediaan likuiditas pada platform Decentralized Exchange (DEX) atau dalam pool likuiditas.

### Perhitungan Dasar Likuiditas Token
Untuk menghitung likuiditas dasar dalam suatu pool likuiditas, misalnya pada Uniswap, berikut adalah formula dasarnya:

1. **Nilai Total Likuiditas (Total Value Locked - TVL):**
   - \( TVL = \text{Jumlah Token A dalam Pool} \times \text{Harga Token A} + \text{Jumlah Token B dalam Pool} \times \text{Harga Token B} \)
   - Misalnya, jika ada 100 Token A dengan harga $10/token dan 200 Token B dengan harga $5/token, maka:
   - \( TVL = (100 \times 10) + (200 \times 5) = 1000 + 1000 = 2000 \) USD.

2. **Liquidity Ratio:**
   - Untuk DEX seperti Uniswap, likuiditas biasanya diukur dalam rasio, yang adalah perbandingan antara jumlah token A dan token B dalam pool.
   - Jika likuiditas untuk token A dan token B setara, maka rasio likuiditasnya adalah 1:1. Misalnya, jika ada 100 token A dan 1000 token B, rasio likuiditasnya akan 1:10.

3. **Slippage:**
   - Likuiditas yang lebih rendah akan menyebabkan slippage yang lebih besar. Slippage adalah perbedaan antara harga yang diharapkan dan harga yang didapatkan saat perdagangan dieksekusi.

### Faktor Lain yang Mempengaruhi Likuiditas:
- **Volume Perdagangan:** Volume perdagangan yang tinggi biasanya berarti likuiditas yang lebih baik.
- **Distribusi Token:** Jika sebagian besar supply token terkonsentrasi di tangan sedikit orang atau entitas, likuiditas bisa rendah.
- **Penguncian Token (Token Locking):** Jika ada token yang dikunci untuk jangka waktu tertentu (seperti dalam staking), ini dapat mempengaruhi likuiditas yang tersedia di pasar.

source: Chatgpt4
