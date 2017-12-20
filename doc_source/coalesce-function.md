# coalesce Function<a name="coalesce-function"></a>

`coalesce` returns the value of the first argument that is not null\. When a non\-null value is found, the remaining arguments in the list are not evaluated\. If all arguments are null, the result is null\. 0\-length strings are valid values and are not considered equivalent to null\.

## Syntax<a name="coalesce-function-syntax"></a>

```
coalesce(expression, expression [, expression, ...])
```

## Arguments<a name="coalesce-function-arguments"></a>

`coalesce` takes two or more expressions as arguments\. All of the expressions must have the same data type or be able to be implicitly cast to the same data type\.

 *expression*   
The expression must be a string\. It can be a field name like **address1**, a literal value like **'Unknown'**, or another function like `toString({sales amount})`\. 

## Return Type<a name="coalesce-function-return-type"></a>

`coalesce` returns a value of the same data type as the input arguments\.

## Example<a name="coalesce-function-example"></a>

The following example retrieves a customer's mailing address if it exists, her street address if there is no mailing address, or returns "No address listed" if neither address is available\.

```
coalesce(mailingAddress, streetAddress, 'No address listed')
```