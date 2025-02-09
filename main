let max = 100, min = 1;
const num = Math.trunc(Math.random() * (max-min) + min);
let num2 = Math.trunc((1 + 100) / 2);

console.log(`Компьютер 1 загадал число: ${num}.`);
console.log(`Компьютер 2: Пробую число ${num2}.`);
while (num2 != num) {
    if (num2 > num) {
        console.log('Компьютер 1: Меньше.');
        max = num2;
        num2 = Math.trunc((num2 + min) / 2);
    }
    else {
        console.log('Компьютер 1: Больше.');
        min = num2;
        num2 = Math.trunc((num2 + max) / 2);
    }
    console.log(`Компьютер 2: Пробую число ${num2}.`);
}
console.log('Компьютер 1: Угадал!')
