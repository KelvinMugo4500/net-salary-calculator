# Net Salary Calculator

This is a JavaScript program that calculates an individual's net salary based on their basic salary and benefits. It takes into account Payee (Tax), NHIF Deductions, and NSSF Deductions according to the provided rates.

## Functions

- `calculatePayee(basicSalary)`: Calculates Payee (Tax) based on the provided basic salary.
- `calculateNHIF(basicSalary)`: Calculates NHIF Deductions based on the provided basic salary.
- `calculateNSSF(basicSalary)`: Calculates NSSF Deductions based on the provided basic salary.
- `calculateGrossSalary(basicSalary, benefits)`: Calculates Gross Salary based on the provided basic salary and benefits.
- `calculateNetSalary(basicSalary, benefits)`: Calculates Net Salary based on the provided basic salary and benefits.

## Example

```javascript
const basicSalary = 50000;
const benefits = 10000;
const netSalary = calculateNetSalary(basicSalary, benefits);
console.log("Net Salary:", netSalary);
