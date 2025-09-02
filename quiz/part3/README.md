# Belajar Looping | Part 3
## Soal 1

```js
// Problem
// Pada tugas ini kamu diminta untuk melakukan looping dalam JavaScript dengan menggunakan syntax while. 
// Untuk membuat tantangan ini lebih menarik, kamu juga diminta untuk membuat suatu looping yang menghitung maju dan 
// menghitung mundur. Jangan lupa tampilkan di console juga judul 'LOOPING PERTAMA' dan 'LOOPING KEDUA'.
//tampilkan output yang menunjukan kalau looping itu maju pada looping pertama dan mundur pada looping kedua
console.log("LOOPING PERTAMA");
let i = 1;
while (i <= 10) {
  console.log("Looping bertambah, ke-" + i);
  i += 1;
}

console.log("LOOPING KEDUA");
let j = 10;
while (j >= 1) {
  console.log("Looping berkurang, ke-" + j);
  j -= 1;
}
```
## Soal 2. Melakukan Looping Menggunakan For
```js
// Problem
// Pada tugas ini kamu diminta untuk melakukan looping dalam JavaScript dengan menggunakan syntax for. 
// Untuk membuat tantangan ini lebih menarik, kamu juga diminta untuk membuat suatu looping yang menghitung maju dan 
// menghitung mundur. Jangan lupa tampilkan di console juga judul 'LOOPING PERTAMA' dan 'LOOPING KEDUA'.
//tampilkan output yang menunjukan kalau looping itu maju pada looping pertama dan mundur pada looping kedua
console.log("LOOPING PERTAMA");

for (let i = 1; i <= 10; i += 1) {
  console.log("Looping bertambah, ke-" + i);
}
console.log("LOOPING KEDUA");

for (let j = 10; j >= 1; j -= 1) {
  console.log("Looping berkurang, ke-" + j);
}
```
## Soal 3. Angka Ganjil dan Genap

```js
// Hint: kamu akan menggunakan kondisional juga di kasus ini.

// Problem
// Buatlah sebuah perulangan 1 - 100 dengan pertambahan counter sebanyak 1
// Di dalam perulangan, periksa setiap angka counter:

// Apabila angka counter adalah angka genap, tuliskan GENAP
// Apabila angka counter adalah angka ganjil, tuliskan GANJIL
for (let i = 1; i <= 100; i++) {
  if (i % 2 === 0) {
    console.log(i + " - GENAP");
  } else {
    console.log(i + " - GANJIL");
  }
}

```
## Soal 4. counter kelipatan
```js
// Buatlah 3 perulangan baru dari 1 - 100, dengan pertambahan counter sebesar 2, 5, dan 9.
// Pada 3 perulangan baru ini periksa setiap angka counter:

// Apabila bukan kelipatan yang ditentukan tidak perlu menuliskan apa-apa
// Apabila angka counter adalah kelipatan 3 de  ngan pertambahan 2, kelipatan 6 dengan pertambahan 5, dan kelipatan 10 dengan pertambahan 9, tuliskan:
// "3 kelipatan 3"dan seterusnya.
console.log("Counter dengan pertambahan 2");
for(let i = 1; i<=100; i+=2){
    if(i % 3 === 0){
        console.log(i + " kelipatan 3");
    }
}
console.log("Counter dengan pertambahan 5");
for(let i = 1; i<=100; i+=5){
    if(i % 6 === 0){
        console.log(i + " kelipatan 6");
    }
}
console.log("Counter dengan pertambahan 9");
for(let i = 1; i<=100; i+=9){
    if(i % 10 === 0){
        console.log(i + " kelipatan 10");
    }
}
```
## Soal 5. Bintang asteriks
```js
// Problem buatlah bintang seperti berikut
let input = 5
//hasilnya
//*
//**
//***
//****
//*****
for(let i = 0; i<= input; i++) {
  let star = ''
  for(let j = 0; j<i; j++) {
    star+="*";
  };
  console.log(star);
};
```

---
Tips pengerjaan ada di video berikut :
[Looping](https://youtu.be/kyobpgoqx2c)

[Materi Looping](../../study-materials/part5.md)