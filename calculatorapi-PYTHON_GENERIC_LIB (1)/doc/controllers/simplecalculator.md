# Simplecalculator

```python
simplecalculator_controller = client.simplecalculator
```

## Class Name

`SimplecalculatorController`


# Calculate

This is calculator api.

```python
def calculate(self,
             x,
             y,
             x_query,
             x_query_query)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `x` | `float` | Query, Required | The LHS value |
| `y` | `float` | Query, Required | The RHS value |
| `x_query` | `float` | Query, Required | New parameter |
| `x_query_query` | `float` | Query, Required | new parameter 2 |

## Response Type

`float`

## Example Usage

```python
x = 222.14

y = 165.14

x_query = 57.66

x_query_query = 167.94

result = simple_calculator_controller.calculate(
    x,
    y,
    x_query,
    x_query_query
)
print(result)
```

