# Laporan Uji Hipotesis Z-Score

## 1. Tujuan Pengujian

Pengujian dilakukan untuk mengetahui apakah rata-rata tagihan belanja per invoice pada dataset *Online Retail* benar sama dengan **£50** atau berbeda secara signifikan.

Karena yang diuji adalah perbedaan dari nilai klaim, maka digunakan **uji dua arah** (*two-tailed test*) dengan **z-score**.

## 2. Rumusan Hipotesis

**H0:** μ = 50  
Rata-rata tagihan per invoice adalah **£50**.

**H1:** μ ≠ 50  
Rata-rata tagihan per invoice bukan **£50**.

## 3. Data dan Parameter Uji

| Komponen | Nilai |
|---|---:|
| Jumlah invoice (n) | 19.960 |
| Rata-rata sampel (x̄) | £534,4030 |
| Standar deviasi sampel (s) | 1.780,4876 |
| Rata-rata klaim (μ0) | £50 |
| Alpha (α) | 0,05 |
| Critical value two-tailed | z = ±1,96 |


## 4. Perhitungan Z-Score

Standard error dihitung dengan rumus:

`Standard error = s / √n`

Substitusi nilai:

`Standard error = 1780,4876 / √19960 = 12,6026`

Nilai z-score dihitung dengan rumus:

`z = (x̄ - μ0) / standard error`

Substitusi nilai:

`z = (534,4030 - 50) / 12,6026`

`z = 484,4030 / 12,6026`

`z = 38,4369`

p-value untuk uji dua arah:

`p-value two-tailed = 2 × P(Z ≥ |38,4369|)`

`p-value ≈ 0,0000`


## 5. Keputusan dan Kesimpulan

Aturan keputusan:

`Tolak H0 jika p-value ≤ α`

atau

`Tolak H0 jika |z| > 1,96`

Karena:

`p-value ≈ 0,0000 ≤ 0,05`

dan

`|38,4369| > 1,96`

maka **H0 ditolak**.


## Kesimpulan

Terdapat cukup bukti statistik bahwa rata-rata tagihan belanja per invoice berbeda signifikan dari **£50**.

Jadi, klaim bahwa rata-rata tagihan per invoice adalah **£50** tidak didukung oleh data.
