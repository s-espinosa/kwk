# Unwrapping Optionals

---

# Warmup

* What is an optional?
* What might be some benefits of optional values?
* What have you done this far to work with optionals in your code?
* Have you had any problems?

---

# Goals

* High level introduction to optionals
* Prep for homework
* Prep for tomorrow's classes with Amy

---

# What are optionals?

In some ways, an optional is like a box:

* It could hold a value
* It could be empty

Swift wants to *force* you to account for both cases.

---

# Example

```
var fuelPrices = [
  "St. Louis" : 1.79,
  "Phoenix" : 1.84,
  "Denver" : 1.65,
  "SLC" : 1.95
]
```

* What happens if try to access `fuelPrices["St. Louis"]`?
* What happens if try to access `fuelPrices["Houston"]`?

---

# Unwrapping Optionals: Optional Binding

Best way to account for both cases:

```
func findCurrentPrice(location: String) -> Double {
  var localPrice = fuelPrices[location]

  if let currentPrice = localPrice {
    return currentPrice
  } else {
    return 0.0
  }
}
```

* Annotate the code above with a partner. What's happening in each line?
* Why might we call this optional binding?

---

# Unwrapping Optionals: Unconditional Unwrapping

```
func findCurrentPrice() -> Double {
  var localPrice = fuelPrices[location]!
  return localPrice
}
```

* Annotate the code above with a partner. What's happening in each line?
* What might the danger be in the above code?

---

# Homework

* Work through Iteration 0-1 tonight
* We will finish Iteration 2 as a group tomorrow, then reflect on the project, common issues, etc. to prepare to facilitate it at camp

Make sure to shut down/restart your computer daily! It will work much better that way with Xcode.


