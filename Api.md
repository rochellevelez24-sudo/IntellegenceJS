# The api.
( joke this is made of TypeScript )
# Classes

## new NetworkProvider ( Class )
### The network provider for your AI.
### Parameters: 
```javascript
new NetworkProvider() // Normal network
new NetworkProvider({
  trainType: "any"
}) // Advanced network (any train type)
new NetworkProvider ({
   networkIP: "https://intejs/api/1000"
})// Changed the IP. Normal is normalIP
```
### Methods:
```javascript
network.Train(trains: Trainer) // Normal training
network.input(input: InputProvider)
// Deprecated functions.
network.random(m, max) // Randomizes by [m] to [max], Use now the Randomizer.random()
```
# Constants (like: naviagator.mediaDevices)
## Randomizer 
### The randomizer for any number, 

### Problems:

### 1st: This returns a
### RandomizerPromise<>,
### which the network.Train() can ONLY
### read the RandomizerPromise generic ### type

### Constant Methods:
``` typescript
Randomizer.random(min: number, max: number): RandomizerPromise // Randomizes an number.

// more in the future!

```