# Python OOP and Decorators Examples

This repository contains practical examples of advanced Python concepts, such as **Object-Oriented Programming (OOP)** with abstract classes and the implementation of **Decorators** for validation, all accompanied by unit tests using `pytest`.

## Project Structure

The project is divided into two main exercises:

1.  **Transportation (OOP/Abstract Classes):** Demonstrates the use of abstract base classes (`ABC`) to define a common interface (`Transporte`) and concrete classes (`Carro`, `Bicicleta`) that implement this interface.
2.  **Validation with Decorator:** Shows how to use a decorator (`@valida_positivo`) to add reusable validation logic (ensuring numeric arguments are positive) to multiple functions (`raiz_quadrada`, `divisao`).

## Files

| File | Description | Main Concept |
| :--- | :--- | :--- |
| `exercicio1.py` | Implementation of `Transporte`, `Carro`, and `Bicicleta` classes. | OOP (Abstract Classes) |
| `test_exercicio2.py` | Unit tests for the classes in `exercicio1.py`. | Pytest (Class Testing) |
| `exercicio3.py` | Implementation of the `valida_positivo` decorator and its usage. | Decorators |
| `test_exercicio3.py` | Unit tests for the decorated functions in `exercicio3.py`. | Pytest (Exception Testing) |

## How to Run

### Prerequisites

⚠️ Make sure you have `pytest` installed

Running the Tests
To execute all unit tests in the project:
``pytest``

You should see an output similar to this, indicating all tests have passed:
```bash
============================= test session starts ==============================
...
collected 8 items

test_exercicio2.py ....                                                  [ 50%]
test_exercicio3.py ....                                                  [100%]

============================== 8 passed in X.XXs ===============================

