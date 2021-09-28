## Solidity Types
- Solidity Elementary (value) types:
1. Boolean- bool <variable name>, default to false
2. Integer- signed or unsigned integers(int and uint), default to 0
uint is the same as uint256, suffix must be a multiple of 8, ex. uint8, uint16,  etc.
3. Address- a 20 byte value with Balance, transfer, send(use address.transfer instead), call(returns true if the function terminates, false if exception), callcode(use delegatecall() instead), delegatecall(delegate a function call to address with aspects of calling address like storage, balance, etc.
4. Byte arrays 
5. Enums- user defined type, enum ActionChoices { GoLeft, GoRight, GoStraight, SitStill }, explicitly convertible to integer types, requires at least one member.

- Complex(reference) types:
1. Arrays
2. Structs

Logical negation(!), logical conjunction(&&), logical disjunction(||), equality(==) and inequality(!=).

Adding the public attribute public will automatically create a getter function to retrieve the variables value.
