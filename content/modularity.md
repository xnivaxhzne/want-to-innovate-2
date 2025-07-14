> A method of managing system complexity that involves dividing large systems into multiple, smaller self-contained systems.

- Modularity employs abstraction, information hiding, and a strict separation of concerns.
- A module’s visible information provides an external view of the module that lets other designers treat the module as a black box, letting them abstract from the complexity of the module.
- Compositionally is not just the ability to compose objects, but the ability to work with an object after intentionally forgetting how it was built.
- The part that is remembered is the “interface”, which may be a type, or a contract, or some other high-level description.
- Architecture’s hidden information vs Architecture’s visible information

Because modules are [[Black Box Method|black boxes]], you can change anything within the module, provided it doesn’t change the interface

- [[Modules give you the freedom to rapidly evolve the internals of a system without breaking any functionality.]]