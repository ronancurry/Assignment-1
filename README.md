# Assignment-1

## Exercises

### Exercise 1: Profit Margin Calculator

Reads revenue and cost as floats, then calculates profit and profit margin. Revenue must be greater than zero to calculate the margin; otherwise, the program reports invalid revenue.

Sample run:

```text
What's the revenue? 5000.0
What's the cost? 3500.0
Profit: $1,500.00 | Margin: 30.00%
```

### Exercise 2: Credit Score Evaluator

Reads an integer credit score and categorizes it as Excellent, Good, Fair, or Poor. Scores outside the assumed 300-850 range are invalid. Approved scores receive a low-interest-rate message; other scores receive a credit-improvement message.

Sample run:

```text
What's your credit score? 720
Good - Loan Approved with Review. Interest rate: Low
```

### Exercise 3: Customer Greeting Formatter

Formats a customer's first name with a default `Customer` title. The function strips whitespace, normalizes capitalization, splits full names, and returns a fallback greeting for empty input.

Sample run:

```text
What's your full name?   john doe
Hello, John (Customer)!
```

### Exercise 4: Tax Bracket Determiner

Uses a function to return a tax bracket for a float income and calculates estimated tax using the bracket's illustrative rate. Negative income is treated as invalid.

Sample run:

```text
What's your annual income? 75000.0
Your bracket: Medium (20%). Estimated tax: 15000.0
```

### Exercise 5: Product Category Matcher

Normalizes a product name with `strip()` and `lower()`, then uses `match` cases and `startswith()` to select a pricing category. Uppercase input and extra surrounding spaces are supported.

Sample run:

```text
What's the product name?  Tech Phone
Product: tech phone | Category: High Margin
```

### Bonus: Integrated Decision Tool

Combines revenue, cost, and product category decisions. A helper function returns whether the business is profitable, and profitable products receive an investment recommendation based on their category.

Sample run:

```text
What's the revenue? 5000
What's the cost? 3500
What's the product category? electronics
Category: High Margin
Profit: $1,500.00
Suggestion: Reinvest
```

## Assumptions

- The programs are run with Python 3.10 or newer because Exercise 5 and the bonus use `match` statements.
- Numeric prompts receive valid numeric input unless the exercise explicitly tests invalid ranges.
- Exercise 2 assumes credit scores are normally between 300 and 850.
- Exercise 4 uses simple flat illustrative tax rates of 10%, 20%, and 30%; it is not tax advice.
- Product categories are compared after trimming whitespace and converting input to lowercase.