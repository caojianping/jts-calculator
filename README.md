# jts-calculator
TypeScript版本的计算器库，提供了简单的加、减、乘、除基本四则运算功能，同时解决了精度丢失的问题。

## 安装
Using npm:
```bash
$ npm install jts-calculator
```

Using yarn:
```bash
$ yarn add jts-calculator
```

## 示例
```ts
import Calculator from 'jts-calculator';

// test for Calculator
Calculator.add(1, 2);// return 3;
Calculator.subtract(2, 1);// return 1;
Calculator.multiply(2, 5);// return 10;
Calculator.divide(12, 3);// return 4;
```

## API
##### Calculator.add(num1: number, num2: number, precision: number = 0): number
##### Calculator.subtract(num1: number, num2: number, precision: number = 0): number
##### Calculator.multiply(num1: number, num2: number, precision: number = 0): number
##### Calculator.divide(num1: number, num2: number, precision: number = 0): number
