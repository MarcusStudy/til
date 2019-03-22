# Type Conversions
The three most widely used type conversions are to string, to number, and to boolean.
- ToString – Occurs when we output something. Can be performed with String(value). The conversion to string is usually obvious for primitive values.
- ToNumber – Occurs in math operations. Can be performed with Number(value).
- ToBoolean – Occurs in logical operations. Can be performed with Boolean(value).

### Please note: the string with zero "0" is true
- Some languages (namely PHP) treat "0" as false. But in JavaScript, a non-empty string is always true.
```
alert( Boolean("0") ); // true
alert( Boolean(" ") ); // spaces, also true (any non-empty string is true)
```

