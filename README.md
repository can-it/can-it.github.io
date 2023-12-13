# CanIt

Enhance your experience in implementing the authorization in your javascript/typescript projects.

<div style="width: 100%; display: flex; justify-content: center;">
  <img  src="./assets/overview.png" width="500px" alt="Overview">
</div>

### Examples
[👉 Source code](https://github.com/can-it/examples)

## Core Packages
- **[@can-it/core](./packages/core/):** This is the core package that forms the foundation of CanIt.
[![npm version](https://img.shields.io/npm/v/@can-it/core.svg?style=flat-square)](https://www.npmjs.org/package/@can-it/core)

## Operator Packages and Documentation

These packages can be used along with the `@can/it-core` package or its utilization packages mentioned below.

- **[@can-it/operators-relation](./packages/operators/relation/):** Provides a relational matching comparator and its generator.
  [![npm version](https://img.shields.io/npm/v/@can-it/operators-relation.svg?style=flat-square)](https://www.npmjs.org/package/@can-it/operators-relation)

  For example, your system can allow the `edit` action to perform the `view` action. Accessing `settings` can also grant access to `payments` and `profiles`.

- **[@can-it/operators-nested](./packages/operators/nested/):** Enables a nested structure matching comparator.
  [![npm version](https://img.shields.io/npm/v/@can-it/operators-nested.svg?style=flat-square)](https://www.npmjs.org/package/@can-it/operators-nested)

  For example, your system can allow access to all members in any organization by defining the value as `organizations::*::members`. Accessing members of organization A will have the value `organizations::A::members`.

- **[@can-it/operators-exact](./packages/operators/exact/):** Provides an exact matching comparator in a case-sensitive manner.
  [![npm version](https://img.shields.io/npm/v/@can-it/operators-exact.svg?style=flat-square)](https://www.npmjs.org/package/@can-it/operators-exact)


## Utilization Packages

- **[@can-it/ngx](./packages/ngx/):** Integration package for Angular applications. [![npm version](https://img.shields.io/npm/v/@can-it/ngx.svg?style=flat-square)](https://www.npmjs.org/package/@can-it/ngx)

- **[@can-it/react](./packages/react):** Integration package for React applications. [![npm version](https://img.shields.io/npm/v/@can-it/react.svg?style=flat-square)](https://www.npmjs.org/package/@can-it/react)

- **[@can-it/nest](./packages/nest)**: Integration package for Nestjs applications. [![npm version](https://img.shields.io/npm/v/@can-it/nest.svg?style=flat-square)](https://www.npmjs.org/package/@can-it/nest)

- **[@can-it/express](./packages/express)**: Integration package for Express applications.
- **@can-it/fastify**: Integration package for Fastify applications. (💪 *Coming soon* ⏰)

For other purposes or usage with different JavaScript/TypeScript frameworks, you can directly use the `@can-it/core` package and [comparator packages](https://www.npmjs.com/search?q=keywords:can-it-operators) above.

# Full Documentation (coming soon) 🚀🚀🚀

📚 More detailed documentation, including usage guides, examples, and advanced features, is currently in progress. We appreciate your patience and encourage you to check back soon for a comprehensive resource to help you make the most out of CanIt. Stay tuned!
