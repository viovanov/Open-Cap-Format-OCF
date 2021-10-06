# TerminationWindow Type Schema

```txt
Enums.TerminationWindow.schema.json#/properties/reason
```

Enumeration of TerminationWindow types

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                                      |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :---------------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [TerminationWindow.schema.json*](../types/TerminationWindow.schema.json "open original schema") |

## reason Type

`string` ([TerminationWindow Type](terminationwindow-properties-terminationwindow-type.md))

## reason Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"CAUSE"`       |             |
| `"VOLUNTARY"`   |             |
| `"INVOLUNTARY"` |             |
| `"DEATH"`       |             |
| `"DISABILITY"`  |             |
| `"RETIREMENT"`  |             |