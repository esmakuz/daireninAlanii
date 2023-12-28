# daireninAlanii
daireninAlani

const PI = 3.14159;

function alanHesapla(yaricap) {
  return PI * yaricap * yaricap;
}

const yaricap = prompt("Yarıçap değerini giriniz: ");
const alan = alanHesapla(yaricap);

console.log(`Yarıçapı ${yaricap} olan dairenin alanı: ${alan}`);

