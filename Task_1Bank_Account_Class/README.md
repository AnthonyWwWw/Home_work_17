## TASK_1

# BankAccount Class

Цей клас представляє банківський рахунок.

## Використання

1. Створіть новий екземпляр класу BankAccount з початковим балансом.
2. Використовуйте методи для внесення та зняття грошей або отримання поточного балансу.

## Методи

### `constructor(initialBalance)`

Створює новий екземпляр класу BankAccount з вказаним початковим балансом.

### `deposit(amount)`

Додає вказану суму на баланс рахунку.

### `withdraw(amount)`

Знімає вказану суму з балансу рахунку, якщо на рахунку достатньо коштів.

### `getBalance()`

Повертає поточний баланс рахунку.

## Приклад використання

```javascript
const account = new BankAccount(1000);

console.log(account.getBalance()); // 1000

account.deposit(500);

console.log(account.getBalance()); // 1500

account.withdraw(200);

console.log(account.getBalance()); // 1300