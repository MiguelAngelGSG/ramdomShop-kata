# Random Shop

## Description

Welcome to **Random Shop**, where we embrace chaos as our brand identity. Our goal is to provide an unpredictable shopping experience where customers never know what they're going to buy or how much they're going to pay for it. Our current stock includes pets, gourmet products, Magic: The Gathering cards, and footwear (outlet).

## Pricing Details

### Magic: The Gathering Cards

- Blue: 5 euros
- Red: 3.5 euros
- Green: 4.40 euros
- Black: 6.80 euros
- Brown: 2.0 euros
- Black Lotus: 40,000 euros (collector's item)

### Pets

- Terrestrial Animals: 4.2 euros per leg
- Fish:
  - Blue: 0.10 euros
  - Gold: 100 euros
  - Others: base price

### Gourmet Products

- Wine: 20 euros per year
- Stinky Cheese: 10 euros per year

### Special Cases

- **Magic Cards**:
  - Blue and Red cards cost half the price when older than 10 years.
  - Black and Green cards cost 20% more when older than 20 years.
  
- **Pet Spiders**:
  - 1.20 euros per leg
  - +2 euros if red
  - +3 euros if gold
  - Stinky spiders are half price

## Requirements

### Modifications and New Functionalities

1. **Magic Cards Modification**:
   - Blue and Red cards older than 10 years cost half the price.
   - Black and Green cards older than 20 years cost 20% more.

2. **Pet Spiders Addition**:
   - Price calculation: 1.20 euros per leg, +2 euros if red, +3 euros if gold.
   - Stinky spiders are half price.

### Refactoring

To improve code maintainability and clarity, we have refactored our codebase into the following classes:

- `TerrestrialAnimal`
- `AquaticAnimal`
- `GourmetProduct`
- `MagicCards`

Each class has corresponding unit tests to ensure the functionalities are working correctly.


## Unit Tests

The project includes comprehensive unit tests for each class. Here is the structure of the test files:

```markdown
- src/test/java/org/example/
  - TerrestrialAnimalTest.java
  - AquaticAnimalTest.java
  - GourmetProductTest.java
  - MagicCardsTest.java
