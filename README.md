https://codeburst.io/angular-bad-practices-eab0e594ce92

- [ ] Do define one thing, such as a service or component, per file.
- [ ] Do define small functions. Consider limiting to no more than 75 lines.
- [ ] Do use consistent names for all symbols. Do follow a pattern that describes the symbol's feature then its type. The recommended pattern is feature.type.ts.
- [ ] Do use dashes to separate words in the descriptive name. Do use dots to separate the descriptive name from the type.Do use consistent type names for all components following a pattern that describes the component's feature then its type. A recommended pattern is feature.type.ts.
- [ ] Do use consistent names for all symbols. Do follow a pattern that describes the symbol's feature then its type. The recommended pattern is feature.type.ts.
- [ ] Do use dashes to separate words in the descriptive name. Do use dots to separate the descriptive name from the type. Do use consistent type names for all components following a pattern that describes the component's feature then its type. A recommended pattern is feature.type.ts.
- [ ] Do use consistent names for all assets named after what they represent.
- [ ] Do use consistent names for all services named after their feature.
- [ ] Do put bootstrapping and platform logic for the app in a file named main.ts.
- [ ] Do use a hyphenated, lowercase element selector value (e.g. admin-users).
- [ ] Do name an interface using upper camel case. Consider naming an interface without an I prefix.
- [ ] Do use lower camel case to name properties and methods.
- [ ] Consider leaving one empty line between third party imports and application imports.

- [ ] Do make locating code intuitive, simple and fast.
- [ ] Do name the file such that you instantly know what it contains and represents.
- [ ] Do keep a flat folder structure as long as possible.
- [ ] Do be DRY (Don't Repeat Yourself).
- [ ] Less common component should not be in the common/shared to avoid increase of common components
- [ ] Do create folders named for the feature area they represent.

- [ ] Do create an NgModule for all distinct features in an application; for example, a Heroes feature.
Why? A feature module can expose or hide its implementation from other modules.

Why? A feature module identifies distinct sets of related components that comprise the feature area.

Why? A feature module can easily be routed to both eagerly and lazily.

Why? A feature module defines clear boundaries between specific functionality and other application features.

Why? A feature module helps clarify and make it easier to assign development responsibilities to different teams.

Why? A feature module can easily be isolated for testing.

- [ ] Do create a feature module named SharedModule in a shared folder; for example, app/shared/shared.module.ts defines SharedModule. Consider using the name SharedModule when the contents of a shared module are referenced across the entire application.

- [ ] Consider collecting numerous, auxiliary, single-use classes inside a core module to simplify the apparent structure of a feature module.




