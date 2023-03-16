- BackBone.js oct. 2010 
	- model driven re-renders
- knockout.js  July 2010
	- fine-grained updates
	- difficult to follow the path of change
	- [data Binding](Data-Binding.md)
- Angular.js
	- dirty-checking
	- need to check the whole tree
	- [data Binding](Data-Binding.md)
-  [React](React.md) 2015
	- UI as a function of state
	- recreate all
- [Solid.js](Solid.js.md) 


## [Exploring the state of reactivity patterns in 2020](https://indepth.dev/posts/1280/exploring-the-state-of-reactivity-patterns-in-2020)

Reactive programming

fined-grained reactivity is different from streams like rxjs, similar but not exactly the same
fined-grained reactivity => tracking reactive atoms and propagation of their change, wrapping executiuon in computed expressions

=> funcrional progaming  => const view = fn(state)