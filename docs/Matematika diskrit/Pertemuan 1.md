---
slug : '/matematikadiskrit'
sidebar_label: 1️⃣
---

# MATEMATIKA DISKRIT📊

## A. Pernyataan
Pernyataan adalah kalimat yang hanya bisa bernilai benar atau salah.

:::info
Pernyataan disebut juga kalimat tertutup
:::

Contoh:
1. 5 adalah bilangan prima (Pernyataan dan Benar)
2. 14 merupakan bilangan kelipatan 5 (Pernyataan dan Salah)
3. Siapakah yang tidak mengerjakan PR? (Bukan pernyataan dan tidak benar tidak juga salah)


>- Lambang pernyataan p, q, r, dst. (Huruf kecil)
>- Nilai kebenaran pernyataan B(benar) dan S(salah)

## B. Ingkaran/Negasi
Ingkaran atau negasi adalah pernyataan yang memiliki nilai kebenaran yang berlawanan dari pernyataan atau proposisi semula.

:::info
- dilambangkan dengan : "~" atau "-"
- dibaca : bukan / tidak
:::

Contoh : 
1. p : 2 + 5 =7
- $\sim$ p : 2 + 5 $\not$ = 7
Tidak benar bahwa 2 + 5 = 7

2. q : Semua pelajar berbaju putih 
- ~q : Tidak semua pelajar berbaju putih
- ~q : Beberapa pelajar tidak berbaju putih
- ~q : Ada pelajar yang tidak berbaju putih 

## C. Pernyataan Majemuk
1. Disjungsi
- s v s = s, selainnya B -> "atau" "+"
:::tip _Tabel kebenaran disjungsi_
|   p   |   q   | p v q |
| :---: | :---: | :---: |
|   B   |   B   |   B   |
|   B   |   S   |   B   |
|   S   |   B   |   B   |
|   S   |   S   |   S   |
:::
- contoh : Ana memesan sandal merah **atau** sepatu basket
2. Konjungsi
- B ʌ B = B, Selainnya S -> "dan" "x"
:::tip _Tabel kebenaran konjungsi_
|   p   |   q   | p ʌ q |
| :---: | :---: | :---: |
|   B   |   B   |   B   |
|   B   |   S   |   S   |
|   S   |   B   |   S   |
|   S   |   S   |   S   |
:::
- Contoh : Ayah membaca koran tempo **dan** kompas
3. Implikasi
- B $\to$ S = S selainnya B -> "Jika.. Maka.."
:::tip _Tabel Kebenaran Implikasi_
|   p   |   q   | p → q |
| :---: | :---: | :---: |
|   B   |   B   |   B   |
|   B   |   S   |   S   |
|   S   |   B   |   B   |
|   S   |   S   |   B   |
:::
- **Jika** hari ini adalah hari senin **maka** siswa memakai seragam putih-putih
4. Biimplikasi
- B ↔ B = S ↔ S, Selainnya B -> "Jika.. dan hanya jika.."
:::tip _Tabel Kebenaran Biimplikasi_
|   p   |   q   | p ↔ q |
| :---: | :---: | :---: |
|   B   |   B   |   B   |
|   B   |   S   |   S   |
|   S   |   B   |   S   |
|   S   |   S   |   B   |
:::
- contoh : Aku membawa pensil 2B **jika dan hanya jika** ujian menggunakan lembar LJK.

### Implikasi
1. Invers 
- $\sim$p → $\sim$q
:::tip _Tabel Invers_
| ~p → ~q |
| :-----: |
|    B    |
|    B    |
|    S    |
|    B    |
:::
- contoh : Jika mawar tidak berwarna merah maka melati tidak berwarna putih

2. konvers
- q $\to$ p
:::tip _Table Konvers_
| q → p |
| :---: |
|   B   |
|   B   |
|   S   |
|   B   |
:::
- contoh : jika hari tidak hujan maka matahari bersinar

3. Kontraposisi
- $\sim$q $\to$ $\sim$p
:::tip _Tabel Kontraversi_
| ∼q → ∼p |
| :-----: |
|    B    |
|    S    |
|    B    |
|    B    |
:::
- contoh :  Jika hari hujan maka matahari tidak bersinar

## Penarikan kesimpulan
1. Modus Ponens
>Jika Pernyataan 1 berimplikasi dengan dengan pernyataan 2 bernilai benar, dan pernyataan 2 bernilai benar maka pernyataan 2 dianggap konklusi

Premis