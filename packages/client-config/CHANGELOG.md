# @aws-amplify/client-config

## 0.9.0-beta.12

### Patch Changes

- 1e93535: chore: auto-generate cognito domain when external providers are configured
- bb5a446: fix: populate analytics legacy v5 config
- Updated dependencies [1e93535]
  - @aws-amplify/backend-output-schemas@0.7.0-beta.1
  - @aws-amplify/deployed-backend-client@0.4.0-beta.7
  - @aws-amplify/model-generator@0.5.0-beta.9

## 0.9.0-beta.11

### Patch Changes

- 54c69c4: chore: rename the new client config file name
- Updated dependencies [6c6af9b]
- Updated dependencies [a494aca]
  - @aws-amplify/platform-core@0.5.0-beta.5
  - @aws-amplify/model-generator@0.5.0-beta.8
  - @aws-amplify/deployed-backend-client@0.4.0-beta.6

## 0.9.0-beta.10

### Patch Changes

- 394b72e: chore: updates to client config schema and config generation
- 592bd4f: refactor log abstraction in `client-config`, `form-generator`, and `model-generator` packages
- Updated dependencies [592bd4f]
  - @aws-amplify/model-generator@0.5.0-beta.7

## 0.9.0-beta.9

### Patch Changes

- Updated dependencies [aec89f9]
- Updated dependencies [2a69684]
  - @aws-amplify/platform-core@0.5.0-beta.4
  - @aws-amplify/deployed-backend-client@0.4.0-beta.5
  - @aws-amplify/model-generator@0.5.0-beta.6

## 0.9.0-beta.8

### Patch Changes

- 8d73779: refactor model generation from schema uri
- Updated dependencies [8d73779]
  - @aws-amplify/model-generator@0.5.0-beta.5

## 0.9.0-beta.7

### Patch Changes

- d95ab02: dir options create the target dir if it does not exist

## 0.9.0-beta.6

### Patch Changes

- 4cd282e: fix: populate top level region in the client config

## 0.9.0-beta.5

### Minor Changes

- 5e12247: feat(client-config): Generate client configuration based on a unified JSON schema

### Patch Changes

- Updated dependencies [b0112e3]
- Updated dependencies [5e12247]
  - @aws-amplify/deployed-backend-client@0.4.0-beta.4
  - @aws-amplify/platform-core@0.5.0-beta.3
  - @aws-amplify/model-generator@0.5.0-beta.4

## 0.9.0-beta.4

### Patch Changes

- Updated dependencies [05c3c9b]
- Updated dependencies [937086b]
- Updated dependencies [b931980]
  - @aws-amplify/model-generator@0.5.0-beta.3
  - @aws-amplify/platform-core@0.5.0-beta.2
  - @aws-amplify/deployed-backend-client@0.4.0-beta.3

## 0.9.0-beta.3

### Minor Changes

- 79cff6d: fix(client-config): add legacy analytics configuration key

## 0.8.1-beta.2

### Patch Changes

- Updated dependencies [415c4c1]
  - @aws-amplify/deployed-backend-client@0.4.0-beta.2
  - @aws-amplify/model-generator@0.4.1-beta.2

## 0.8.1-beta.1

### Patch Changes

- Updated dependencies [ab7533d]
- Updated dependencies [4995bda]
  - @aws-amplify/deployed-backend-client@0.4.0-beta.1
  - @aws-amplify/backend-output-schemas@0.7.0-beta.0
  - @aws-amplify/platform-core@0.5.0-beta.1
  - @aws-amplify/model-generator@0.4.1-beta.1

## 0.8.1-beta.0

### Patch Changes

- Updated dependencies [74cbda0]
  - @aws-amplify/platform-core@0.5.0-beta.0
  - @aws-amplify/deployed-backend-client@0.3.11-beta.0
  - @aws-amplify/model-generator@0.4.1-beta.0

## 0.8.0

### Minor Changes

- b1c3e0d49: Add typings for geo category in client config
- 6daae6be5: Add typings for notifications and analytics categories in client config

## 0.7.0

### Minor Changes

- 85ced84f2: Add ability to add custom outputs

### Patch Changes

- 348717b55: Fix bug in frontend config where oauth would not be output if domain prefix was not defined.
- Updated dependencies [85ced84f2]
- Updated dependencies [1814f1a69]
  - @aws-amplify/backend-output-schemas@0.6.0
  - @aws-amplify/model-generator@0.4.0
  - @aws-amplify/deployed-backend-client@0.3.10
  - @aws-amplify/platform-core@0.4.4

## 0.6.0

### Minor Changes

- 4c1485aa4: print out file written for amplify generate commands

### Patch Changes

- Updated dependencies [4c1485aa4]
  - @aws-amplify/model-generator@0.3.0

## 0.5.3

### Patch Changes

- 618a2ea71: Add allowUnauthenticatedIdentities to config output.
- Updated dependencies [618a2ea71]
  - @aws-amplify/backend-output-schemas@0.5.2
  - @aws-amplify/deployed-backend-client@0.3.9
  - @aws-amplify/model-generator@0.2.7

## 0.5.2

### Patch Changes

- @aws-amplify/deployed-backend-client@0.3.8
- @aws-amplify/model-generator@0.2.6

## 0.5.1

### Patch Changes

- 04f067837: Implement consistent dependency declaration check. Bumped dependencies where necessary.
- Updated dependencies [04f067837]
  - @aws-amplify/deployed-backend-client@0.3.7
  - @aws-amplify/backend-output-schemas@0.5.1
  - @aws-amplify/model-generator@0.2.5

## 0.5.0

### Minor Changes

- 6a1c252e1: Expose domainPrefix as an input property to the Auth construct.

### Patch Changes

- 6a1c252e1: Cognito domains are now created by default, and oauth settings are exported to frontend config.
- Updated dependencies [6a1c252e1]
- Updated dependencies [6a1c252e1]
  - @aws-amplify/backend-output-schemas@0.5.0
  - @aws-amplify/deployed-backend-client@0.3.5
  - @aws-amplify/model-generator@0.2.4

## 0.4.2

### Patch Changes

- c47e03e20: add missing graphql fields to mobile config to support dart libs

## 0.4.1

### Patch Changes

- 50934da02: include additional fields in mobile config generation

## 0.4.0

### Minor Changes

- 07b0dfc9f: Adding zero-config auth config to amplifyconfiguration.json

### Patch Changes

- 01ebbc497: handle client config formats used in mobile app development
- Updated dependencies [07b0dfc9f]
  - @aws-amplify/backend-output-schemas@0.4.0
  - @aws-amplify/deployed-backend-client@0.3.1
  - @aws-amplify/model-generator@0.2.2

## 0.3.0

### Minor Changes

- 71a63a16: Change stack naming strategy to include deployment type as a suffix

### Patch Changes

- Updated dependencies [71a63a16]
  - @aws-amplify/deployed-backend-client@0.3.0
  - @aws-amplify/backend-output-schemas@0.3.0
  - @aws-amplify/model-generator@0.2.1

## 0.2.3

### Patch Changes

- 0bd8a3f3: add missing dev deps

## 0.2.2

### Patch Changes

- 79a6e09f: Change stackOutputKey to platformOutputKey
- 79a6e09f: Add aws_project_region to amplifyconfiguration.json
- Updated dependencies [79a6e09f]
- Updated dependencies [79a6e09f]
  - @aws-amplify/deployed-backend-client@0.2.1
  - @aws-amplify/backend-output-schemas@0.2.1

## 0.2.1

### Patch Changes

- a216255e: Add successfulDeletion event to remove amplify configuration on deletion

## 0.2.0

### Minor Changes

- e233eab6: make default amplifyconfig format json, change js format to mjs, and add dart format
- 1a87500d: Generate model introspection schema when producing client config.
- ce008a2c: Add model generation package.
- b4f82717: Create a new deployed-backend-client package that provides a convenient interface for retrieving stack outputs
- 05f97b26: Add AppSync outputs to client config
- f75fa531: Refactor OutputStorageStrategy into stateless shared dependency

### Patch Changes

- 2bbf3f20: Remove trailing whitespace for ts and js config files
- 23fc5b13: Lint fixes
- c3383926: Run npm init as part of create-amplify if necessary. List aws-cdk as a peerDependency of sandbox. Fix sandbox stack naming and lookup
- b2b0c2da: force version bump
- 7296e9d9: Initial publish
- 3bda96ff: update methods to use arrow notation
- 395c8f0d: Add identityPoolId to output, and set delete policy on user pool to delete.
- 01320d4b: add `amplify generate config --format` option
- 36d93e46: add license to package.json
- bb3bf89a: add backend metadata manager
- 407a09ff: Implements backend secret feature, include backend secret resolver and the backend-secret pkg.
- 2525b582: add reader for cms metadata
- f6618771: add deployment type to stack outputs
- f201c94a: add support for external auth providers
- 512f0778: move UniqueBackendIdentifier to platform-core package
- e0e1488b: fix config export lint error
- Updated dependencies [f0ef7c6a]
- Updated dependencies [92950f99]
- Updated dependencies [23fc5b13]
- Updated dependencies [e9c0c9b5]
- Updated dependencies [47bfb317]
- Updated dependencies [ac3df080]
- Updated dependencies [b2b0c2da]
- Updated dependencies [a351b261]
- Updated dependencies [1a87500d]
- Updated dependencies [b48dae80]
- Updated dependencies [56fbcc5f]
- Updated dependencies [7296e9d9]
- Updated dependencies [53779253]
- Updated dependencies [5585f473]
- Updated dependencies [b40d2d7b]
- Updated dependencies [c5d18967]
- Updated dependencies [b40d2d7b]
- Updated dependencies [395c8f0d]
- Updated dependencies [1cefbdd4]
- Updated dependencies [ce008a2c]
- Updated dependencies [36d93e46]
- Updated dependencies [4d411b67]
- Updated dependencies [f46f69fb]
- Updated dependencies [bb3bf89a]
- Updated dependencies [47456c26]
- Updated dependencies [0b029cb5]
- Updated dependencies [b4f82717]
- Updated dependencies [5b9aac15]
- Updated dependencies [05f97b26]
- Updated dependencies [d925b097]
- Updated dependencies [2525b582]
- Updated dependencies [1a6dd467]
- Updated dependencies [f75fa531]
- Updated dependencies [f6618771]
- Updated dependencies [f201c94a]
- Updated dependencies [5c1d9de8]
- Updated dependencies [512f0778]
- Updated dependencies [883d9da7]
  - @aws-amplify/deployed-backend-client@0.2.0
  - @aws-amplify/model-generator@0.2.0
  - @aws-amplify/backend-output-schemas@0.2.0

## 0.2.0-alpha.12

### Minor Changes

- e233eab6: make default amplifyconfig format json, change js format to mjs, and add dart format

## 0.2.0-alpha.11

### Patch Changes

- 2bbf3f20: Remove trailing whitespace for ts and js config files

## 0.2.0-alpha.10

### Minor Changes

- 1a87500d: Generate model introspection schema when producing client config.

### Patch Changes

- Updated dependencies [1a87500d]
  - @aws-amplify/model-generator@0.2.0-alpha.5

## 0.2.0-alpha.9

### Patch Changes

- 2525b582: add reader for cms metadata
- Updated dependencies [2525b582]
  - @aws-amplify/deployed-backend-client@0.2.0-alpha.3
  - @aws-amplify/backend-output-schemas@0.2.0-alpha.6

## 0.2.0-alpha.8

### Patch Changes

- 36d93e46: add license to package.json
- Updated dependencies [36d93e46]
  - @aws-amplify/deployed-backend-client@0.2.0-alpha.2
  - @aws-amplify/backend-output-schemas@0.2.0-alpha.5

## 0.2.0-alpha.7

### Patch Changes

- 23fc5b13: Lint fixes
- bb3bf89a: add backend metadata manager
- f6618771: add deployment type to stack outputs
- 512f0778: move UniqueBackendIdentifier to platform-core package
- Updated dependencies [bb3bf89a]
- Updated dependencies [f6618771]
- Updated dependencies [512f0778]
  - @aws-amplify/deployed-backend-client@0.2.0-alpha.1
  - @aws-amplify/backend-output-schemas@0.2.0-alpha.4

## 0.2.0-alpha.6

### Minor Changes

- b4f82717: Create a new deployed-backend-client package that provides a convenient interface for retrieving stack outputs
- 05f97b26: Add AppSync outputs to client config
- f75fa531: Refactor OutputStorageStrategy into stateless shared dependency

### Patch Changes

- 1dada824: chore: Update eslint config to new flat config type
- 407a09ff: Implements backend secret feature, include backend secret resolver and the backend-secret pkg.
- e0e1488b: fix config export lint error
- Updated dependencies [ac3df080]
- Updated dependencies [53779253]
- Updated dependencies [1dada824]
- Updated dependencies [b4f82717]
- Updated dependencies [05f97b26]
- Updated dependencies [f75fa531]
  - @aws-amplify/backend-output-schemas@0.2.0-alpha.3
  - @aws-amplify/deployed-backend-client@0.2.0-alpha.0

## 0.2.0-alpha.5

### Patch Changes

- 01320d4: add `amplify generate config --format` option

## 0.2.0-alpha.4

### Minor Changes

- ce008a2: Add model generation package.

### Patch Changes

- f201c94: add support for external auth providers
- Updated dependencies [ce008a2]
- Updated dependencies [f201c94]
  - @aws-amplify/backend-output-schemas@0.2.0-alpha.2

## 0.1.1-alpha.3

### Patch Changes

- b2b0c2d: force version bump
- 395c8f0: Add identityPoolId to output, and set delete policy on user pool to delete.
- Updated dependencies [b2b0c2d]
- Updated dependencies [395c8f0]
  - @aws-amplify/backend-output-schemas@0.1.1-alpha.1

## 0.1.1-alpha.2

### Patch Changes

- 3bda96f: update methods to use arrow notation

## 0.1.1-alpha.1

### Patch Changes

- c338392: Run npm init as part of create-amplify if necessary. List aws-cdk as a peerDependency of sandbox. Fix sandbox stack naming and lookup

## 0.1.1-alpha.0

### Patch Changes

- 7296e9d: Initial publish
- Updated dependencies [7296e9d]
  - @aws-amplify/backend-output-schemas@0.1.1-alpha.0
