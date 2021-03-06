## API Report File for "kibana"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { CoreSetup } from 'kibana/server';
import { CoreStart } from 'kibana/server';
import { Plugin } from 'kibana/server';

// Warning: (ae-forgotten-export) The symbol "EmbeddableStateWithType" needs to be exported by the entry point index.d.ts
// Warning: (ae-forgotten-export) The symbol "PersistableStateDefinition" needs to be exported by the entry point index.d.ts
// Warning: (ae-missing-release-tag) "EmbeddableRegistryDefinition" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export interface EmbeddableRegistryDefinition<P extends EmbeddableStateWithType = EmbeddableStateWithType> extends PersistableStateDefinition<P> {
    // (undocumented)
    id: string;
}

// Warning: (ae-forgotten-export) The symbol "PersistableStateService" needs to be exported by the entry point index.d.ts
// Warning: (ae-missing-release-tag) "EmbeddableSetup" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export interface EmbeddableSetup extends PersistableStateService<EmbeddableStateWithType> {
    // (undocumented)
    registerEmbeddableFactory: (factory: EmbeddableRegistryDefinition) => void;
    // (undocumented)
    registerEnhancement: (enhancement: EnhancementRegistryDefinition) => void;
}

// Warning: (ae-forgotten-export) The symbol "SerializableState" needs to be exported by the entry point index.d.ts
// Warning: (ae-missing-release-tag) "EnhancementRegistryDefinition" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export interface EnhancementRegistryDefinition<P extends SerializableState = SerializableState> extends PersistableStateDefinition<P> {
    // (undocumented)
    id: string;
}

// Warning: (ae-forgotten-export) The symbol "EmbeddableServerPlugin" needs to be exported by the entry point index.d.ts
// Warning: (ae-missing-release-tag) "plugin" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export const plugin: () => EmbeddableServerPlugin;


// (No @packageDocumentation comment for this package)

```
