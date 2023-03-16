the revival of fine-grained reactivity, being referred to as Signals, across the front-end world.

https://dev.to/ryansolid/a-hands-on-introduction-to-fine-grained-reactivity-3ndf

https://dev.to/modderme123/super-charging-fine-grained-reactive-performance-47ph

https://dev.to/this-is-learning/the-evolution-of-signals-in-javascript-8ob

A Signal keeps a strong reference to its subscribers, so a long-lived Signal will retain all subscriptions unless manually disposed.

Getter, setter, and a value

have been called Observables, Atoms, Subjects, or Refs

Reactions
	Effects
	Autoruns (mobx)
	Watches
	Computed

Signal => observed
Reaction =>  observer

Fine-grained reactive systems execute their changes synchronously and immediately.

Fined-grained reactive libraries use a hybrid push/pull approach to maintain consistency

They are not purely "push" like events/streams, nor purely "pull" like generators.

[Reactive Library](Reactive%20Library.md)

[Reactive History](Reactivity%20History.md)
