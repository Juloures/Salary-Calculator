# Salary Calculator

This Python script performs basic salary calculations, including:

1. **Gross Salary Input**: The user enters their gross salary.
2. **Tax Calculation**: The script calculates the tax as 10% of the gross salary.
3. **Net Salary Calculation**: The net salary is calculated by subtracting the tax from the gross salary.
4. **Display Net Salary**: The net salary is displayed with two decimal places.

## How to Use

1. Run the script.
2. Enter the gross salary when prompted.
3. The script will calculate and display the net salary after deducting a 10% tax.

## Example

```python
# Gross salary input
gross_salary = float(input('Enter your gross salary: R$'))

# Tax calculation and net salary calculation
tax = gross_salary * 0.10
net_salary = gross_salary - tax

# Display the net salary
print(f'Net Salary: R${net_salary:.2f}')
