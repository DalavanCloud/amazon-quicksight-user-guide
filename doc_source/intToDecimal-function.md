# intToDecimal Function<a name="intToDecimal-function"></a>

`intToDecimal` converts an integer value to the decimal data type\.

`intToDecimal` is supported for use with analyses based on SPICE data sets\.

## Syntax<a name="intToDecimal-function-syntax"></a>

```
intToDecimal(int)
```

## Arguments<a name="intToDecimal-function-arguments"></a>

 *int*   
A field that uses the integer data type, a literal value like **14**, or a call to another function that outputs an integer\.

## Return Type<a name="intToDecimal-function-return-type"></a>

Decimal

## Example<a name="intToDecimal-function-example"></a>

The following example converts an integer field to a decimal\.

```
intToDecimal(transaction_count)
```

The following are the given field values\.

```
20
892
57
```

For these field values, the following values are returned\.

```
20.0
892.0
58.0
```