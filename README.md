# 🚀 workshop or homework ສໍາຫລັບນັກສຶກສາ 🚀

ໂຈດໄວ້ສໍາຫຼັບ ເຝິກ javaScript ແລະ data structures

## ✍️ ສໍາຫຼັບວິທີການສົ່ງແມ່ນ Fork ແລ້ວ ສ້າງ Pull requests

## data structures

Stack, Queue, Linked List, Set, Hash Table, Tree, Trie, Graph

## ມີ array 1 ຊຸດ

```js
const numbers = [2, -1, 3, -10, 4, 90, -20, "Mark AI", true, 3.14];
const isAdmin = true;
const isUser = !isAdmin;
```

### 1. ຂຽນຄໍາສັ່ງສະແດງຄ່າ ແລະ ນັບຈໍານວນ ອອກທາງ console ⚡️

```js
// example
const numbers = [2, -1, 3, -10, 4, 90, -20, "Mark AI", true, 3.14];

console.log(numbers); // output: [0, -1, 3, -10, 4, 90, -20, "Mark AI", true, 3.14]
console.log(numbers.length); // output: 10
```

### 2. ຂຽນຄໍາສັ່ງນັບຈໍານວນ ແລະ ສະແດງ array number ທິ່ເປັນຄ່າ[-] ອອກທາງ console ⚡️

```js
// output: [-1,-10,-20]
// output: 3
```

### 3. ຂຽນຄໍາສັ່ງນັບຈໍານວນ ແລະ ສະແດງ array number ທິ່ເປັນຄ່າ[+] ອອກທາງ console ⚡️

```js
// output: [2, 3, 4, 90, 3.14]
// output: 5
```

### 4. ຂຽນປ່ຽນຄ່າ array number ເປັນຄ່າ[+] ທັງໝົດ ແລະ ສະແດງຜົນອອກທາງ console ⚡️

```js
let positiveNumber = [...numbers];
// output: [2, 1, 3, 10, 4, 90, 20, 3.14]
```

### 5. ຂຽນປ່ຽນຄ່າ array number ເປັນຄ່າ[-] ທັງໝົດ ແລະ ສະແດງຜົນອອກທາງ console ⚡️

```js
let negativeNumber = [...numbers];
// output: [-2, -1, -3, -10, -4, -90, -20, -3.14]
```

### 6. ຈົ່ງຊອກຫາຜົນລວມຂອງ array numbers ທິ່ເປັນຄ່າ[+] ທັງໝົດ ແລະ ສະແດງຜົນອອກທາງ console ⚡️

```js
// output: 102.14
```

### 7. ຈົ່ງຊອກຫາຜົນລວມຂອງ array numbers ທິ່ເປັນຄ່າ[-] ທັງໝົດ ແລະ ສະແດງຜົນອອກທາງ console ⚡️

```js
// output: -31
```
