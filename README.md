# Assignment-1 - Ronan Curry

This assignment is a collection of small Python exercises based on everyday business situations. Each exercise focuses on a different programming concept, such as input, conditionals, functions, and string methods.

## Exercises

### Exercise 1: Profit Margin Calculator

This program asks for a product's revenue and cost, then calculates the profit and profit margin. If the revenue is zero or negative, it displays an invalid revenue message instead of trying to divide by zero.

Sample run:

```text
What's the revenue? 5000.0
What's the cost? 3500.0
Profit: $1,500.00 | Margin: 30.00%
```

### Exercise 2: Credit Score Evaluator

This program uses a credit score to decide whether a customer is likely to qualify for a loan. It places the score into an Excellent, Good, Fair, or Poor category. Scores below 300 or above 850 are treated as invalid.

Sample run:

```text
What's your credit score? 720
Good - Loan Approved with Review. Interest rate: Low
```

### Exercise 3: Customer Greeting Formatter

This program cleans up a customer's full name and creates a friendly greeting using the first name. It also has a default `Customer` title and uses a fallback greeting when no name is entered.

Sample run:

```text
What's your full name?   john doe
Hello, John (Customer)!
```

### Exercise 4: Tax Bracket Determiner

This program uses a person's annual income to find a tax bracket and estimate their tax. The rates are simple examples for this exercise, and negative income is treated as invalid.

Sample run:

```text
What's your annual income? 75000.0
Your bracket: Medium (20%). Estimated tax: 15000.0
```

### Exercise 5: Product Category Matcher

This program cleans up a product name and uses a `match` statement to place it into a pricing category. It recognizes common names such as electronics, clothing, and grocery items. Uppercase input and extra spaces are handled automatically.

Sample run:

```text
What's the product name?  Tech Phone
Product: tech phone | Category: High Margin
```

### Bonus: Integrated Decision Tool

This bonus program brings several earlier ideas together. It checks whether revenue is greater than cost, identifies the product category, and gives an investment suggestion when the business is profitable.

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

- I am running these programs with Python 3.10 or newer because the product matcher and bonus use `match` statements.
- The numeric prompts are expected to receive numbers. The exercises handle the invalid ranges that are specifically required in each task.
- Credit scores are assumed to normally fall between 300 and 850.
- The tax rates are simplified examples for practice and should not be treated as real tax advice.
- Product names are trimmed and converted to lowercase before they are compared.