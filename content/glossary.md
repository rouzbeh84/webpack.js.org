# webpack glossary index

## A

## B

## C

- [**Code Splitting**](/guides/code-splitting/): splitting/chunking your code into various bundles/chunks which you can then load on demand when a matching router is requested.

## D

- [**Dependency Graph**](/concepts/dependency-graph): Any time one file depends on another, webpack treats this as a *dependency*. Starting from entry point(s), webpack recursively builds a dependency graph that includes every module/asset your application needs

## E

- [**Entry Point**](/concepts/entry-points): The entry point tells webpack where to start and follows the graph of dependencies to know what to bundle. You can think of your application's entry point(s) as the **contextual root(s)** of what you want bundled

## F

## G

## H

- [**Hot Module Replacement aka (HMR)**](/concepts/hot-module-replacement): exchanges, adds, or removes `modules` while an application is running without a page reload

## I

## J

## K

## L

- [**Loaders**](/concepts/loaders): transformations that are applied on the source code of a module. They allow you to preprocess files as you `require()` or "load" them. Similar to a 'task-runner'

## M

- [**Module**](/concepts/modules): discrete chunks of functionality called a module providing a smaller surface area than a full program. Well-written modules provide solid abstractions and encapsulation boundaries to provide a coherent design and clear purpose

## N

## O

- [**Output**](/concepts/output): tell webpack how to write the compiled files to disk. *there can only be one*
## P

- [**Plugin**](/concepts/plugins): a JavaScript object that has an `apply` property. This `apply` property is called by the webpack compiler, giving access to the entire compilation lifecycle

## Q

## R

## S

## T

- [**Target**](/configuration/target/): user configured deployment target(s) [listed here](/configuration/target/) to compile for multiple environments. e.g. node, electron, web(default).

- [**Tree Shaking**](/guides/tree-shaking/): dead-code elimination, or more precisely, live-code importing

## U

## V

## W

- [**webpack**](/): a highly configurable [module](/concepts/moduels) bundler for modern JavaScript applications

## X

## Y

## Z
