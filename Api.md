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
### Useful for randomizing than 
### Math.random(), and not recommended ### for not using the NetworkProvider, 
### since it returns RandomPromise<>, 
### which is like a Promise, but better, ### and inputs in the
``` javascript
 NetworkProvider.Train({ input: "" // this is})
```